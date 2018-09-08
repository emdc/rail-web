---
title: Перечисления
layout: ru/article
permalink: /ru/doc/language/enums/
---

## Основная информция

Перечисление — набор констант, объединенных в тип.

```
enum Error {
  None,
  Timeout,
  ValidationFailed
}
```

Каждая константа получает свой номер, начиная с нуля. Поэтому значения получатся следующими:

```
Error.None;               // 0
Error.Timeout;            // 1
Error.ValidationFailed;   // 2
```


