---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
Добавляет картинку в коллекцию.


###  Возврат

Индекс объекта [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| stream | io.RawIOBase | Объект потока, содержащий данные изображения.|

###  Пример

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(self, upper_left_row, upper_left_column, file_name) {#int-int-str}
Добавляет картинку в коллекцию.


###  Возврат

Индекс объекта [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| file_name | str | Имя файла изображения.|

###  Пример

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Добавляет картинку в коллекцию.


###  Возврат

Индекс объекта [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
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
    pictures.add(1, 1, 5, 5, fs)

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
Добавляет картинку в коллекцию.


###  Возврат

Индекс объекта [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| lower_right_row | int | Индекс нижней правой строки|
| lower_right_column | int | Индекс нижнего правого столбца|
| file_name | str | Имя файла изображения.|

###  Пример

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Добавляет картинку в коллекцию.


###  Возврат

Индекс объекта [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
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
    pictures.add(1, 1, fs, 50, 50)

```


##  add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
Добавляет картинку в коллекцию.


###  Возврат

Индекс объекта [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| file_name | str | Имя файла изображения.|
| width_scale | int | Масштаб ширины изображения, процент.|
| height_scale | int | Масштаб высоты изображения, процент.|

###  Пример

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture)
* класс [`PictureCollection`](/cells/python-net/ru/aspose.cells.drawing/picturecollection)
