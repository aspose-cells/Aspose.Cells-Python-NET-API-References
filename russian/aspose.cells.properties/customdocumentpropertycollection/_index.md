---
title: CustomDocumentPropertyCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection класс
Коллекция пользовательских свойств документа.



**Наследование:** [`CustomDocumentPropertyCollection`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection)



Тип CustomDocumentPropertyCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`add(self, name, value)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Создает новое пользовательское свойство документа**PropertyType.String** тип данных.|
| [`add(self, name, value)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Создает новое пользовательское свойство документа**PropertyType.Number** тип данных.|
| [`add(self, name, value)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Создает новое пользовательское свойство документа**PropertyType.DateTime** тип данных.|
| [`add(self, name, value)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Создает новое пользовательское свойство документа**PropertyType.Boolean** тип данных.|
| [`add(self, name, value)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Создает новое пользовательское свойство документа**PropertyType.Float** тип данных.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |Создает новое пользовательское свойство документа, ссылающееся на контент.|
| [`update_linked_property_value(self)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | Обновить значение свойства документа, ссылающегося на контент.|
| [`update_linked_range(self)`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Обновить значение пользовательского свойства документа до связанного диапазона.|



###  Примечания

Каждый объект [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty) представляет собой пользовательское свойство документа-контейнера.

###  Пример

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Смотрите также
* модуль [`aspose.cells.properties`](..)
* класс [`CustomDocumentPropertyCollection`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection)
* класс [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty)
