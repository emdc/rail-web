---
title: Объединения
layout: ru/article
permalink: /ru/doc/language/unions/
---

Для создания типа, который может трактоваться по-разному, в зависимости от ситуации, подойдут объединения:

```
class PacketHeader {
  let code :i32;
  let version :i32;
  let time :timestamp;
}

class Packet {
  union HeaderUnion [
    PacketHeader,
    [byte:16]
  ]
  
  public let header: HeaderUnion;
}

fn main () {
  let receivedData :Packet;
  
  console.writeLine((Packet.header as PacketHeader).code); // output: "0"
  console.writeLine(Packet.header as [byte]); // output: "[0x00 0x00 0x00 0x00 ...]"
}
```

Конструкция `field as type` указывает какой тип нужно использовать при работе с типом. Вместо `type` может выступать только те типы, которые объявлены в union.
