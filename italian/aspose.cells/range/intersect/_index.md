---
title: Metodo intersect
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 170
url: /it/aspose.cells/range/intersect/
is_root: false
---
##  intersect(self, range) {#aspose.cells.Range}
Restituisce un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) che rappresenta l'intersezione rettangolare di due intervalli.


###  ritorna

Restituisce un oggetto [`Range`](/cells/python-net/it/aspose.cells/range)


```python

def intersect(self, range):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/it/aspose.cells/range) | L'intervallo di intersezione.|
###  Osservazioni

Se i due intervalli non si intersecano, restituisce null.
###  Esempio


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



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
