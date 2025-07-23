---
title: set_picture метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 220
url: /ru/aspose.cells/pagesetup/set_picture/
is_root: false
---
##  set_picture(self, is_first, is_even, is_header, section, image_data) {#bool-bool-bool-int-bytes}
Устанавливает изображение в верхний/нижний колонтитул рабочего листа.


###  Возврат

Возвращает объект [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def set_picture(self, is_first, is_even, is_header, section, image_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_first | bool | Указывает, установлена ли картинка верхнего/нижнего колонтитула первой страницы.|
| is_even | bool | Указывает, установлена ли картинка верхнего/нижнего колонтитула четной страницы.|
| is_header | bool | Указывает, установлена ли картинка верхнего/нижнего колонтитула.|
| section | int |0: Левая секция, 1: Центральная секция, 2: Правая секция.|
| image_data | bytes | Данные изображения.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PageSetup`](/cells/python-net/ru/aspose.cells/pagesetup)
* класс [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture)
