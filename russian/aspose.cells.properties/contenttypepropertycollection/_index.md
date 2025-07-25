---
title: ContentTypePropertyCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.properties/contenttypepropertycollection/
is_root: false
---
##  ContentTypePropertyCollection класс
Коллекция из [`ContentTypeProperty`](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty) объектов, представляющих дополнительную информацию.



Тип ContentTypePropertyCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, name, value)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/add/#str-str) | Добавляет информацию о свойствах типа контента.|
| [`add(self, name, value, type)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/add/#str-str-str) | Добавляет информацию о свойствах типа контента.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/get/#str) | Получает свойство типа контента по имени свойства.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.properties/contenttypepropertycollection/binary_search/#aspose.cells.properties.contenttypeproperty) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [`aspose.cells.properties`](..)
* класс [`ContentTypeProperty`](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty)
