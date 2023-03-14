---
title: table_style_type الملكية
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 290
url: /ar/aspose.cells.tables/listobject/table_style_type/
is_root: false
---
##  table_style_type الملكية

يحصل وأسلوب الجدول المدمج.

###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.tables import TableStyleType

workbook = Workbook("Book1.xlsx")
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.table_style_type = TableStyleType.TABLE_STYLE_DARK2
workbook.save("TableStyle.xlsx")

```
###  تعريف:
```python
@property
def table_style_type(self):
    ...
@table_style_type.setter
def table_style_type(self, value):
    ...
```

###  أنظر أيضا
* وحدة [aspose.cells.tables](../../)
* فئة [ListObject](/cells/python-net/ar/aspose.cells.tables/listobject)
* فئة [TableStyleType](/cells/python-net/ar/aspose.cells.tables/tablestyletype)
