---
title: PictureCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 440
url: /ru/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection класс
Инкапсулирует коллекцию из [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture) объектов.



Тип PictureCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.drawing/picturecollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Добавляет картинку в коллекцию.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Добавляет картинку в коллекцию.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Добавляет картинку в коллекцию.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/add/#int-int-str) | Добавляет картинку в коллекцию.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Добавляет картинку в коллекцию.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Добавляет картинку в коллекцию.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`camera(self, row, column, range)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Делает фотоснимок полигона.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture)
