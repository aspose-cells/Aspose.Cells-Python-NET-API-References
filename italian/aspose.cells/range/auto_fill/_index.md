---
title: Metodo auto_fill
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells/range/auto_fill/
is_root: false
---
##  auto_fill(self, target) {#aspose.cells.Range}
Riempi automaticamente l'intervallo di destinazione.



```python

def auto_fill(self, target):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/it/aspose.cells/range) | l'intervallo di destinazione.|

###  Esempio

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
Riempi automaticamente l'intervallo di destinazione.



```python

def auto_fill(self, target, auto_fill_type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/it/aspose.cells/range) | La gamma mirata.|
| auto_fill_type | [`AutoFillType`](/cells/python-net/it/aspose.cells/autofilltype) | Tipo di riempimento automatico.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
