---
title: ValidationCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1620
url: /ru/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection класс
Представляет коллекцию проверки данных.



Тип ValidationCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/validationcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells/validationcollection/add/#) | Добавляет проверку данных в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Добавляет проверку данных в коллекцию.|
| [copy_to](/cells/python-net/ru/aspose.cells/validationcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [remove_a_cell](/cells/python-net/ru/aspose.cells/validationcollection/remove_a_cell/#int-int) | Удаляет все настройки проверки в ячейке.|
| [remove_area](/cells/python-net/ru/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Удаляет все настройки проверки в диапазоне.|
| [get_validation_in_cell](/cells/python-net/ru/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Получает проверку, примененную к данной ячейке.|
| [binary_search](/cells/python-net/ru/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



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
