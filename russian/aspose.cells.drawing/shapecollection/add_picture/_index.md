---
title: add_picture метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 230
url: /ru/aspose.cells.drawing/shapecollection/add_picture/
is_root: false
---
##  add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Добавляет картинку в коллекцию.


###  Возврат

[`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture) Объект изображения.


```python

def add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| lower_right_row | int | Индекс нижней правой строки|
| lower_right_column | int | Индекс нижнего правого столбца|
| stream | io.RawIOBase | Объект потока, содержащий данные изображения.|

###  Пример

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 0, 1, 0, fs)

```


##  add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Добавляет картинку в коллекцию.


###  Возврат

[`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture) Объект изображения.


```python

def add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| stream | io.RawIOBase | Объект потока, содержащий данные изображения.|
| width_scale | int | Масштаб ширины изображения, процент.|
| height_scale | int | Масштаб высоты изображения, процент.|

###  Пример

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 1, fs, 50, 60)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
