---
title: get_picture метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 120
url: /ru/aspose.cells/pagesetup/get_picture/
is_root: false
---
##  get_picture(self, is_header, section) {#bool-int}
Получает объект [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture) верхнего/нижнего колонтитула.


###  Возврат

Возвращает объект [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).
Возвращает null, если изображения нет.


```python

def get_picture(self, is_header, section):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_header | bool | Указывает, находится ли он в верхнем или нижнем колонтитуле.|
| section | int |0: Левая секция, 1: Центральная секция, 2: Правая секция.|


##  get_picture(self, is_first, is_even, is_header, section) {#bool-bool-bool-int}
Получает объект [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture) верхнего/нижнего колонтитула.


###  Возврат

Возвращает объект [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def get_picture(self, is_first, is_even, is_header, section):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_first | bool | Указывает, следует ли получать изображение верхнего/нижнего колонтитула первой страницы.|
| is_even | bool | Указывает, следует ли получать изображение четного верхнего/нижнего колонтитула страницы.|
| is_header | bool | Указывает, следует ли получать изображение верхнего/нижнего колонтитула.|
| section | int |0: Левая секция, 1: Центральная секция, 2: Правая секция.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PageSetup`](/cells/python-net/ru/aspose.cells/pagesetup)
* класс [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture)
