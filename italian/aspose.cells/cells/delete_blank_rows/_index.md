---
title: Metodo delete_blank_rows
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 210
url: /it/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Elimina tutte le righe vuote che non contengono dati o altri oggetti.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Elimina tutte le righe vuote che non contengono dati o oggetti speciali, come commenti visibili e tabelle pivot.



```python

def delete_blank_rows(self, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/it/aspose.cells/deleteoptions) | Opzioni di eliminazione dell'intervallo.|
###  Osservazioni

Per le righe vuote che verranno eliminate, non è solo necessario che [`Row.is_blank`](/cells/python-net/it/aspose.cells/row#is_blank) sia vero,
ma non dovrebbe esserci alcun commento visibile definito per nessuna cella in quelle righe,
e nessuna tabella pivot il cui intervallo li intersechi.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
