---
title: ExternalLink صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 570
url: /ar/aspose.cells/externallink/
is_root: false
---
##  ExternalLink صف
يمثل رابطًا خارجيًا في مصنف.



يكشف النوع ExternalLink عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [type](/cells/python-net/ar/aspose.cells/externallink/type) | يحصل على نوع الرابط الخارجي.|
| [path_type](/cells/python-net/ar/aspose.cells/externallink/path_type) | احصل على نوع المسار لهذا الرابط الخارجي|
| [original_data_source](/cells/python-net/ar/aspose.cells/externallink/original_data_source) | يمثل مصدر البيانات المخزنة للرابط الخارجي.|
| [data_source](/cells/python-net/ar/aspose.cells/externallink/data_source) | يمثل مصدر البيانات للرابط الخارجي.|
| [is_referred](/cells/python-net/ar/aspose.cells/externallink/is_referred) | يشير إلى ما إذا كان هذا الرابط الخارجي يتم الإشارة إليه من قبل الآخرين.|
| [is_visible](/cells/python-net/ar/aspose.cells/externallink/is_visible) | يشير إلى ما إذا كان هذا الرابط الخارجي مرئيًا في MS Excel.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/ar/aspose.cells/externallink/add_external_name/#str-str) | يضيف اسمًا خارجيًا.|



###  مثال

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
