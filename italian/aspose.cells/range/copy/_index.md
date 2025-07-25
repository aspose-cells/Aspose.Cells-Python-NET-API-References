---
title: Metodo copy
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 100
url: /it/aspose.cells/range/copy/
is_root: false
---
##  copy(self, range) {#aspose.cells.Range}
Copia dati (incluse formule), formattazione, oggetti di disegno ecc. da un intervallo di origine.



```python

def copy(self, range):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/it/aspose.cells/range) | Oggetto sorgente [`Range`](/cells/python-net/it/aspose.cells/range).|

###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy(self, range, options) {#aspose.cells.Range-aspose.cells.PasteOptions}
Copia dell'intervallo con le opzioni Incolla speciale.



```python

def copy(self, range, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/it/aspose.cells/range) | L'intervallo di origine.|
| options | [`PasteOptions`](/cells/python-net/it/aspose.cells/pasteoptions) | Le opzioni Incolla speciale.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
