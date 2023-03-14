---
title: VbaModuleCollection класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection класс
Представляет список [VbaModule](/cells/python-net/ru/aspose.cells.vba/vbamodule)



Тип VbaModuleCollection предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/capacity) | Получает или задает количество элементов, которые может содержать список массивов.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add(sheet)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add/#Worksheet) |Добавляет модуль для рабочего листа.|
| [add(type, name)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add/#VbaModuleType-str) | Добавляет модуль.|
| [copy_to(array)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала целевого списка массивов.|
| [copy_to(index, array, array_index, count)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) |Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [index_of(item, index)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/index_of/#VbaModule-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который простирается от указанного индекса до последнего элемента.|
| [index_of(item, index, count)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/index_of/#VbaModule-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of(item)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/last_index_of/#VbaModule) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массивов.|
| [last_index_of(item, index)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/last_index_of/#VbaModule-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массивов, который простирается от первого элемента до указанного индекса.|
| [last_index_of(item, index, count)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/last_index_of/#VbaModule-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массивов, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [add_designer_storage(name, data)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage(name)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Представляет данные конструктора.|
| [binary_search(item)](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/binary_search/#VbaModule) | Ищет элемент во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает отсчитываемый от нуля индекс элемента.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [aspose.cells.vba](..)
* класс [VbaModule](/cells/python-net/ru/aspose.cells.vba/vbamodule)
