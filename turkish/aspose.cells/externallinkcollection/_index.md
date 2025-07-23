---
title: ExternalLinkCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 580
url: /tr/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection sınıfı
Bir çalışma kitabındaki harici bağlantılar koleksiyonunu temsil eder.



ExternalLinkCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/externallinkcollection/count) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır.|



Belirtilen indeksteki [`ExternalLink`](/cells/python-net/tr/aspose.cells/externallink) öğesini alır.
###  Dizinleyici
| İsim| Tanım|
| :- | :- |
| [index] | Elemanın sıfırdan başlayan indeksi.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/tr/aspose.cells/externallinkcollection/add/#str-list) | Harici bir bağlantı ekler.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/tr/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | Harici bir bağlantı ekleyin.|
| [`clear(self)`](/cells/python-net/tr/aspose.cells/externallinkcollection/clear/#) | Tüm harici bağlantıları kaldırır.|
| [`clear(self, update_references_as_local)`](/cells/python-net/tr/aspose.cells/externallinkcollection/clear/#bool) | Tüm harici bağlantıları kaldırır.|
| [`remove_at(self, index)`](/cells/python-net/tr/aspose.cells/externallinkcollection/remove_at/#int) | Belirtilen dış bağlantıyı çalışma kitabından kaldırır.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/tr/aspose.cells/externallinkcollection/remove_at/#int-bool) | Belirtilen dış bağlantıyı çalışma kitabından kaldırır.|



###  Örnek

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`ExternalLink`](/cells/python-net/tr/aspose.cells/externallink)
