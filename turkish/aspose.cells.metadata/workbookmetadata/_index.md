---
title: WorkbookMetadata sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata sınıfı
Meta verileri temsil eder.



WorkbookMetadata türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Meta veri nesnesini oluşturun.|
| [`__init__(self, stream, options)`](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Meta veri nesnesini oluşturun.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [options](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/options) | Meta verinin seçeneklerini alır.|
| [built_in_document_properties](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | E-tablonun tüm yerleşik belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.|
| [custom_document_properties](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Elektronik tablonun tüm özel belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/save/#str) | Değiştirilen meta verileri dosyaya kaydedin.|
| [`save(self, stream)`](/cells/python-net/tr/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Değiştirilen meta verileri akışa kaydedin.|



###  Örnek

Aşağıdaki örnek WorkbookMetadata'i oluşturur.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.metadata`](..)
* sınıf [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty)
