---
title: CellArea صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 120
url: /ar/aspose.cells/cellarea/
is_root: false
---
##  CellArea صف
تمثل منطقة من الخلايا.



يكشف النوع CellArea عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/cellarea/__init__/#) | إنشاء مثيل جديد لـ CellArea|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [start_row](/cells/python-net/ar/aspose.cells/cellarea/start_row) | يحصل على أو تعيين الصف الأولي لهذه المنطقة.|
| [end_row](/cells/python-net/ar/aspose.cells/cellarea/end_row) | يحصل على أو تعيين الصف النهائي لهذه المنطقة.|
| [start_column](/cells/python-net/ar/aspose.cells/cellarea/start_column) | يحصل على عمود البداية لهذه المنطقة أو يعينه.|
| [end_column](/cells/python-net/ar/aspose.cells/cellarea/end_column) | يحصل على أو تعيين العمود النهائي لهذه المنطقة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`create_cell_area(, start_row, start_column, end_row, end_column)`](/cells/python-net/ar/aspose.cells/cellarea/create_cell_area/#int-int-int-int) | إنشاء منطقة خلية.|
| [`create_cell_area(, start_cell_name, end_cell_name)`](/cells/python-net/ar/aspose.cells/cellarea/create_cell_area/#str-str) | إنشاء منطقة خلية.|
| [`compare_to(self, obj)`](/cells/python-net/ar/aspose.cells/cellarea/compare_to/#any) | قم بمقارنة كائنين من CellArea وفقًا للزاوية العلوية اليسرى.|



###  مثال

```python
from aspose.cells import CellArea

# Create Cell Area
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
