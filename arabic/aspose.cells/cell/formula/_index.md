---
title: formula عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 490
url: /ar/aspose.cells/cell/formula/
is_root: false
---
##  formula عقار

الحصول على أو تعيين formula من [`Cell`](/cells/python-net/ar/aspose.cells/cell).

###  ملاحظات

 تبدأ السلسلة formula دائمًا بعلامة التساوي (=).
ويرجى دائمًا استخدام الفاصلة (،) كمحدد للمعلمات، مثل "=SUM(A1, E1, H2)".

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
