---
title: formula mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 500
url: /tr/aspose.cells/cell/formula/
is_root: false
---
##  formula mülk

[`Cell`](/cells/python-net/tr/aspose.cells/cell)'in formula'ini alır veya ayarlar.

###  Notlar

 formula dizesi her zaman eşittir işaretiyle (=) başlar.
Ve lütfen parametre ayracı olarak her zaman virgül(,) kullanın, örneğin "=SUM(A1, E1, H2)".

###  Örnek

```python
from aspose.cells import Workbook

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("B6").formula = "=SUM(B2:B5, E1) + sheet1!A1"

```
###  Tanım:
```python
@property
def formula(self):
    ...
@formula.setter
def formula(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
