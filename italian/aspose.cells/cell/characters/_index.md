---
title: Metodo characters
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/cell/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Restituisce un oggetto Characters che rappresenta un intervallo di characters all'interno del testo della cella.


###  ritorna

I personaggi si oppongono.


```python

def characters(self, start_index, length):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| start_index | int | L'indice dell'inizio del carattere.|
| length | int | Il numero di caratteri.|
###  Osservazioni

Questo metodo funziona solo sulle celle con valore stringa.
###  Esempio


```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("A1").put_value("Helloworld")
cells.get("A1").characters(5, 5).font.is_bold = True
cells.get("A1").characters(5, 5).font.color = Color.blue

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
