---
title: ExternalLinkCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 600
url: /ar/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection صف
يمثل مجموعة الروابط الخارجية في المصنف.



يكشف النوع ExternalLinkCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells/externallinkcollection/count) | الحصول على عدد العناصر الموجودة بالفعل في المجموعة.|



يحصل على العنصر [`ExternalLink`](/cells/python-net/ar/aspose.cells/externallink) في الفهرس المحدد.
###  مفهرس
| اسم| وصف|
| :- | :- |
| [index] | الفهرس الصفري للعنصر.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells/externallinkcollection/add/#str-list) | يضيف رابط خارجي.|
| [add](/cells/python-net/ar/aspose.cells/externallinkcollection/add/#aspose.cells.DirectoryType-str-list) | إضافة رابط خارجي .|
| [clear](/cells/python-net/ar/aspose.cells/externallinkcollection/clear/#) | يزيل كافة الروابط الخارجية.|
| [clear](/cells/python-net/ar/aspose.cells/externallinkcollection/clear/#bool) | يزيل كافة الروابط الخارجية.|
| [remove_at](/cells/python-net/ar/aspose.cells/externallinkcollection/remove_at/#int) | إزالة الارتباط الخارجي المحدد من المصنف.|
| [remove_at](/cells/python-net/ar/aspose.cells/externallinkcollection/remove_at/#int-bool) | إزالة الارتباط الخارجي المحدد من المصنف.|



###  مثال

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`ExternalLink`](/cells/python-net/ar/aspose.cells/externallink)
