---
title: CellWatchCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection класс
Представляет собой набор ячеек на этом рабочем листе, отслеживаемых в «окне наблюдения».



Тип CellWatchCollection предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/__init__/#) | Создает новый экземпляр CellWatchCollection|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/cellwatchcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/add/#int-int) | Добавляет [`CellWatch`](/cells/python-net/ru/aspose.cells/cellwatch) со строкой и столбцом.|
| [`add(self, cell_name)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/add/#str) | Добавляет [`CellWatch`](/cells/python-net/ru/aspose.cells/cellwatch) с именем ячейки.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get(self, cell_name)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/get/#str) | Получает и задает [`CellWatch`](/cells/python-net/ru/aspose.cells/cellwatch) по имени ячейки.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`CellWatch`](/cells/python-net/ru/aspose.cells/cellwatch)
