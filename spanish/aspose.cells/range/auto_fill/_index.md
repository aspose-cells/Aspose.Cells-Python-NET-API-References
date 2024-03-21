---
title: método auto_fill
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/range/auto_fill/
is_root: false
---
##  auto_fill {#aspose.cells.Range}
Completa automáticamente el rango objetivo.



```python
def auto_fill(self, target):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/es/aspose.cells/range) | el rango objetivo.|

###  Ejemplo

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


##  auto_fill {#aspose.cells.Range-aspose.cells.AutoFillType}
Completa automáticamente el rango objetivo.



```python
def auto_fill(self, target, auto_fill_type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/es/aspose.cells/range) | El rango objetivo.|
| auto_fill_type | [`AutoFillType`](/cells/python-net/es/aspose.cells/autofilltype) | El tipo de autocompletar.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
