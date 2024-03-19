---
title: intersect Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells/range/intersect/
is_root: false
---
##  intersect {#aspose.cells.Range}
Gibt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt zurück, das den rechteckigen Schnittpunkt zweier Bereiche darstellt.


###  Kehrt zurück

Gibt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt zurück


```python
def intersect(self, range):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/de/aspose.cells/range) | Der Schnittbereich.|
###  Bemerkungen

Wenn sich die beiden Bereiche nicht überschneiden, wird null zurückgegeben.
###  Beispiel


```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A3:A10")
# Get intersected range of the two ranges.
intersectRange = range1.intersect(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
