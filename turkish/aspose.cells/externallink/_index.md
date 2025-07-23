---
title: ExternalLink sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 570
url: /tr/aspose.cells/externallink/
is_root: false
---
##  ExternalLink sınıfı
Bir çalışma kitabındaki harici bir bağlantıyı temsil eder.



ExternalLink türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [type](/cells/python-net/tr/aspose.cells/externallink/type) | Dış bağlantının türünü alır.|
| [path_type](/cells/python-net/tr/aspose.cells/externallink/path_type) | Bu harici bağlantının yol türünü alın|
| [original_data_source](/cells/python-net/tr/aspose.cells/externallink/original_data_source) | Dış bağlantının saklanan veri kaynağını temsil eder.|
| [data_source](/cells/python-net/tr/aspose.cells/externallink/data_source) | Dış bağlantının veri kaynağını temsil eder.|
| [is_referred](/cells/python-net/tr/aspose.cells/externallink/is_referred) | Bu harici bağlantının başkaları tarafından referans alınıp alınmadığını gösterir.|
| [is_visible](/cells/python-net/tr/aspose.cells/externallink/is_visible) | Bu harici bağlantının MS Excel'de görünür olup olmadığını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/tr/aspose.cells/externallink/add_external_name/#str-str) | Harici bir ad ekler.|



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
