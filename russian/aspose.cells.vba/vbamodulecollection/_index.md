---
title: VbaModuleCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection класс
Представляет собой список [`VbaModule`](/cells/python-net/ru/aspose.cells.vba/vbamodule)



Тип VbaModuleCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Добавляет модуль для рабочего листа.|
| [`add(self, type, name)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Добавляет модуль.|
| [`get(self, index)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/get/#int) | Получает [`VbaModule`](/cells/python-net/ru/aspose.cells.vba/vbamodule) в списке по индексу.|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/get/#str) | Добавляет [`VbaModule`](/cells/python-net/ru/aspose.cells.vba/vbamodule) в список по имени.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Представляет данные Designer.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Вставьте пользовательскую форму в проект VBA.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Удаляет модуль для рабочего листа.|
| [`remove_by_name(self, name)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Удалить модуль по имени|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



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
* модуль [`aspose.cells.vba`](..)
* класс [`VbaModule`](/cells/python-net/ru/aspose.cells.vba/vbamodule)
