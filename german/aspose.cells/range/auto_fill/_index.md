---
title: auto_fill Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/range/auto_fill/
is_root: false
---
##  auto_fill(self, target) {#aspose.cells.Range}
Zielbereich automatisch ausfüllen.



```python

def auto_fill(self, target):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/de/aspose.cells/range) | der Zielbereich.|

###  Beispiel

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
Zielbereich automatisch ausfüllen.



```python

def auto_fill(self, target, auto_fill_type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/de/aspose.cells/range) | Der Zielbereich.|
| auto_fill_type | [`AutoFillType`](/cells/python-net/de/aspose.cells/autofilltype) | Der automatische Fülltyp.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
