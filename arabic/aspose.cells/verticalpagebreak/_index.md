---
title: VerticalPageBreak صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1540
url: /ar/aspose.cells/verticalpagebreak/
is_root: false
---
##  VerticalPageBreak صف
يقوم بتغليف الكائن الذي يمثل كسر الصفحة الرأسي.



يكشف النوع VerticalPageBreak عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [start_row](/cells/python-net/ar/aspose.cells/verticalpagebreak/start_row) | يحصل على مؤشر الصف الأول لكسر الصفحة الرأسي.|
| [end_row](/cells/python-net/ar/aspose.cells/verticalpagebreak/end_row) | يحصل على مؤشر الصف النهائي لكسر الصفحة الرأسي.|
| [column](/cells/python-net/ar/aspose.cells/verticalpagebreak/column) | يحصل على فهرس العمود لكسر الصفحة الرأسي.|



###  مثال

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
