---
title: ExternalLinkCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 600
url: /tr/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection sınıfı
Bir çalışma kitabındaki dış bağlantı koleksiyonunu temsil eder.



ExternalLinkCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/externallinkcollection/count) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır.|



Belirtilen dizindeki [`ExternalLink`](/cells/python-net/tr/aspose.cells/externallink) öğesini alır.
###  Dizin oluşturucu
| İsim| Tanım|
| :- | :- |
| [index] | Öğenin sıfır tabanlı dizini.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells/externallinkcollection/add/#str-list) | Harici bir bağlantı ekler.|
| [add](/cells/python-net/tr/aspose.cells/externallinkcollection/add/#aspose.cells.DirectoryType-str-list) | Harici bir bağlantı ekleyin.|
| [clear](/cells/python-net/tr/aspose.cells/externallinkcollection/clear/#) | Tüm dış bağlantıları kaldırır.|
| [clear](/cells/python-net/tr/aspose.cells/externallinkcollection/clear/#bool) | Tüm dış bağlantıları kaldırır.|
| [remove_at](/cells/python-net/tr/aspose.cells/externallinkcollection/remove_at/#int) | Belirtilen dış bağlantıyı çalışma kitabından kaldırır.|
| [remove_at](/cells/python-net/tr/aspose.cells/externallinkcollection/remove_at/#int-bool) | Belirtilen dış bağlantıyı çalışma kitabından kaldırır.|



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
