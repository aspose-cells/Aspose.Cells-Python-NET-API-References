---
title: método intersect
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells/range/intersect/
is_root: false
---
##  intersect {#aspose.cells.Range}
Devuelve un objeto [`Range`](/cells/python-net/es/aspose.cells/range) que representa la intersección rectangular de dos rangos.


###  Devoluciones

Devuelve un objeto [`Range`](/cells/python-net/es/aspose.cells/range)


```python
def intersect(self, range):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/es/aspose.cells/range) | El rango de intersección.|
###  Observaciones

Si los dos rangos no se cruzan, devuelve nulo.
###  Ejemplo


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



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
