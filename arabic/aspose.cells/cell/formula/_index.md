---
title: formula عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 500
url: /ar/aspose.cells/cell/formula/
is_root: false
---
##  formula عقار

يحصل على أو يعين formula من [`Cell`](/cells/python-net/ar/aspose.cells/cell).

###  ملاحظات

 يبدأ السلسلة formula دائمًا بعلامة المساواة (=).
ومن فضلك استخدم دائمًا الفاصلة (,) كفاصل للمعلمات، مثل "=SUM(A1، E1، H2)".

###  مثال

```python
from aspose.cells import Workbook

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("B6").formula = "=SUM(B2:B5, E1) + sheet1!A1"

```
###  تعريف:
```python
@property
def formula(self):
    ...
@formula.setter
def formula(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
