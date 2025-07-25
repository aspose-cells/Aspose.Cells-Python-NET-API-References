---
title: auto_fill yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/range/auto_fill/
is_root: false
---
##  auto_fill(self, target) {#aspose.cells.Range}
Hedef aralığını otomatik olarak doldur.



```python

def auto_fill(self, target):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/tr/aspose.cells/range) | hedef aralığı.|

###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
cells.get("A1").put_value(1)
cells.get("A2").put_value(2)
source = cells.create_range("A1:A2")
target = cells.create_range("A3:A10")
# fill 3,4,5....10 to the range A3:A10
source.auto_fill(target)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  auto_fill(self, target, auto_fill_type) {#aspose.cells.Range-aspose.cells.AutoFillType}
Hedef aralığını otomatik olarak doldur.



```python

def auto_fill(self, target, auto_fill_type):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/tr/aspose.cells/range) | Hedeflenen menzil.|
| auto_fill_type | [`AutoFillType`](/cells/python-net/tr/aspose.cells/autofilltype) | Otomatik doldurma türü.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
