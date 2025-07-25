---
title: VbaProjectReferenceCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 50
url: /ru/aspose.cells.vba/vbaprojectreferencecollection/
is_root: false
---
##  VbaProjectReferenceCollection класс
Представляет все ссылки проекта VBA.



Тип VbaProjectReferenceCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`add_registered_reference(self, name, libid)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/add_registered_reference/#str-str) | Добавьте ссылку на библиотеку типов автоматизации.|
| [`add_control_refrernce(self, name, libid, twiddledlibid, extended_libid)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/add_control_refrernce/#str-str-str-str) |Добавьте ссылку на библиотеку изменяемых типов и ее расширенную библиотеку типов.|
| [`add_project_refrernce(self, name, absolute_libid, relative_libid)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/add_project_refrernce/#str-str-str) | Добавляет ссылку на внешний проект VBA.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreferencecollection/binary_search/#aspose.cells.vba.vbaprojectreference) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add vba project reference
vbaProject.references.add_registered_reference("stdole", "*\\G{00020430-0000-0000-C000-000000000046}#2.0#0#C:\\Windows\\system32\\stdole2.tlb#OLE Automation")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [`aspose.cells.vba`](..)
