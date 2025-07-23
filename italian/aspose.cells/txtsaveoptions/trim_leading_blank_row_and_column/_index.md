---
title: trim_leading_blank_row_and_column proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 230
url: /it/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column proprietà

Indica se le righe e le colonne vuote iniziali devono essere tagliate, come fa Microsoft Excel.
L'impostazione predefinita è vero.

###  Osservazioni

Lo stesso vale per la regola in ms excel, una riga/colonna non verrà considerata vuota se ha uno stile personalizzato,
anche se non contiene dati di celle.
Questa opzione non ha alcun effetto se si salva in modalità LightCells.
L'utente deve controllare l'intervallo di output tramite l'implementazione di [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/it/aspose.cells/txtsaveoptions)
oppure specificando [`TxtSaveOptions.export_area`](/cells/python-net/it/aspose.cells/txtsaveoptions#export_area)
###  Definizione:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`TxtSaveOptions`](/cells/python-net/it/aspose.cells/txtsaveoptions)
