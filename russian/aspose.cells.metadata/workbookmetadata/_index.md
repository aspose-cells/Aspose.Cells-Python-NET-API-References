---
title: WorkbookMetadata класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata класс
Представляет метаданные.



Тип WorkbookMetadata предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Создайте объект метаданных.|
| [`__init__(self, stream, options)`](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Создайте объект метаданных.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [options](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/options) | Получает параметры метаданных.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все пользовательские свойства документа электронной таблицы.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/save/#str) | Сохраните измененные метаданные в файле.|
| [`save(self, stream)`](/cells/python-net/ru/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Сохраните измененные метаданные в потоке.|



###  Пример

В следующем примере создается WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.metadata`](..)
* класс [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty)
