---
title: auto_fill metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/range/auto_fill/
is_root: false
---
##  auto_fill(self, target) {#aspose.cells.Range}
Fyll automatiskt målintervallet.



```python

def auto_fill(self, target):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/sv/aspose.cells/range) | målintervallet.|

###  Exempel

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
Fyll automatiskt målintervallet.



```python

def auto_fill(self, target, auto_fill_type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/sv/aspose.cells/range) | Det riktade intervallet.|
| auto_fill_type | [`AutoFillType`](/cells/python-net/sv/aspose.cells/autofilltype) | Typen för automatisk ifyllning.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
