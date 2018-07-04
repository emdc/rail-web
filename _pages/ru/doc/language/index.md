---
title: Введение
layout: ru/article
permalink: /ru/doc/language/
---

> **Внимание!**
> Это черновик. Проектирование еще в процессе, поэтому информация может сильно изменяться со временем.
> Если у Вас есть предложения или замечания, просьба <a href="mailto:proposals@rail-lang.org">сообщить о них</a>.

Язык **Rail** создается в качестве альтернативы системным языкам [Rust](https://www.rust-lang.org/ru-RU/), [C](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8_(%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)), [C++](https://ru.wikipedia.org/wiki/C%2B%2B). Трудно переоценить значение С и С++ для индустрии в целом, но С уже слишком мало предоставляет возможностей для современных темпов разработки ПО, а С++ с каждым новым обновлением становится все сложнее и сложнее; относительно недавно появившийся язык Rust является глотком свежего воздуха среди системных языков программирования, однако не очень удобочитаемый синтаксис и отсутсвие классического ООП усложняет работу с ним. Но здесь мы опустим сравнение языков и выявление недостатков — целью **Rail** есть гармонично собрать то лучшее, что есть во многих популярных языках.

В тексте далее важные вещи будут **выделяться жирным шрифтом**, второстепенные вещи, требующие внимания, будут _выделяться курсивом_. Исходный код будет обрамляться или в `однострочные блоки`, если это короткие примеры, либо в многострочные блоки:
```
Например, такие блоки кода
с несколькими строками
```

В руководство по языку так же включены и требования и рекомендации по оформлению кода, так как от оформления очень сильно зависит читаемость кода.