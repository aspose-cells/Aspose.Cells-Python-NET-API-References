---
title: WorkbookMetadata صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata صف
يمثل البيانات الوصفية.



يكشف النوع WorkbookMetadata عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | إنشاء كائن البيانات الوصفية.|
| [`__init__(self, stream, options)`](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | إنشاء كائن البيانات الوصفية.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [options](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/options) | يحصل على خيارات البيانات الوصفية.|
| [built_in_document_properties](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | إرجاع مجموعة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty) التي تمثل كافة خصائص المستند المضمنة في جدول البيانات.|
| [custom_document_properties](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/custom_document_properties) | إرجاع مجموعة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty) التي تمثل كافة خصائص المستند المخصصة لجدول البيانات.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/save/#str) | احفظ البيانات الوصفية المعدلة في الملف.|
| [`save(self, stream)`](/cells/python-net/ar/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | احفظ البيانات الوصفية المعدلة في الدفق.|



###  مثال

المثال التالي ينشئ WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.metadata`](..)
* فئة [`DocumentProperty`](/cells/python-net/ar/aspose.cells.properties/documentproperty)
