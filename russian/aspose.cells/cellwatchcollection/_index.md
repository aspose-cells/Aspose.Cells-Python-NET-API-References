---
title: CellWatchCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 180
url: /ru/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection класс
Представляет коллекцию ячеек на этом листе, просматриваемую в «окне просмотра».



Тип CellWatchCollection предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/cellwatchcollection/__init__/#) | Создает новый экземпляр CellWatchCollection.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/cellwatchcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells/cellwatchcollection/add/#int-int) | Добавляет [`CellWatch`](/cells/python-net/ru/aspose.cells/cellwatch) со строкой и столбцом.|
| [add](/cells/python-net/ru/aspose.cells/cellwatchcollection/add/#str) | Добавляет [`CellWatch`](/cells/python-net/ru/aspose.cells/cellwatch) с именем ячейки.|
| [copy_to](/cells/python-net/ru/aspose.cells/cellwatchcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [binary_search](/cells/python-net/ru/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



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
