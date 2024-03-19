---
title: ExternalLink sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 590
url: /tr/aspose.cells/externallink/
is_root: false
---
##  ExternalLink sınıfı
Çalışma kitabındaki dış bağlantıyı temsil eder.



ExternalLink türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [type](/cells/python-net/tr/aspose.cells/externallink/type) | Dış bağlantının türünü alır.|
| [original_data_source](/cells/python-net/tr/aspose.cells/externallink/original_data_source) | Harici bağlantının depolanan veri kaynağını temsil eder.|
| [data_source](/cells/python-net/tr/aspose.cells/externallink/data_source) | Dış bağlantının veri kaynağını temsil eder.|
| [is_referred](/cells/python-net/tr/aspose.cells/externallink/is_referred) | Bu harici bağlantıya başkaları tarafından başvurulup başvurulmadığını belirtir.|
| [is_visible](/cells/python-net/tr/aspose.cells/externallink/is_visible) | Bu dış bağlantının MS Excel'de görünür olup olmadığını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add_external_name](/cells/python-net/tr/aspose.cells/externallink/add_external_name/#str-str) | Harici bir ad ekler.|



###  Örnek

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
