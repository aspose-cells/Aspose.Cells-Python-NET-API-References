---
title: ValidationCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1530
url: /ru/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection класс
Представляет собой сбор данных для проверки.



Тип ValidationCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/validationcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self)`](/cells/python-net/ru/aspose.cells/validationcollection/add/#) | Добавляет проверку данных в коллекцию.|
| [`add(self, ca)`](/cells/python-net/ru/aspose.cells/validationcollection/add/#aspose.cells.cellarea) | Добавляет проверку данных в коллекцию.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/validationcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/ru/aspose.cells/validationcollection/remove_a_cell/#int-int) | Удаляет все настройки проверки для ячейки.|
| [`remove_area(self, ca)`](/cells/python-net/ru/aspose.cells/validationcollection/remove_area/#aspose.cells.cellarea) | Удаляет все настройки проверки для диапазона.|
| [`get_validation_in_cell(self, row, column)`](/cells/python-net/ru/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Получает проверку, примененную к заданной ячейке.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/validationcollection/binary_search/#aspose.cells.validation) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  Смотрите также
* модуль [`aspose.cells`](..)
