---
title: ExternalLinkCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 580
url: /ar/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection صف
يمثل مجموعة الروابط الخارجية في مصنف.



يكشف النوع ExternalLinkCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells/externallinkcollection/count) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة.|



يحصل على العنصر [`ExternalLink`](/cells/python-net/ar/aspose.cells/externallink) في الفهرس المحدد.
###  المفهرس
| اسم| وصف|
| :- | :- |
| [index] | مؤشر العنصر المبني على الصفر.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/ar/aspose.cells/externallinkcollection/add/#str-list) | إضافة رابط خارجي.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/ar/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | أضف رابط خارجي .|
| [`clear(self)`](/cells/python-net/ar/aspose.cells/externallinkcollection/clear/#) | إزالة كافة الروابط الخارجية.|
| [`clear(self, update_references_as_local)`](/cells/python-net/ar/aspose.cells/externallinkcollection/clear/#bool) | إزالة كافة الروابط الخارجية.|
| [`remove_at(self, index)`](/cells/python-net/ar/aspose.cells/externallinkcollection/remove_at/#int) | إزالة الرابط الخارجي المحدد من المصنف.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/ar/aspose.cells/externallinkcollection/remove_at/#int-bool) | إزالة الرابط الخارجي المحدد من المصنف.|



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
