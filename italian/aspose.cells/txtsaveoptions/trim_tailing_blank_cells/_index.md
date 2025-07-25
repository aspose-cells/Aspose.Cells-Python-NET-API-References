---
title: trim_tailing_blank_cells proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 240
url: /it/aspose.cells/txtsaveoptions/trim_tailing_blank_cells/
is_root: false
---
##  trim_tailing_blank_cells proprietà

Indica se le celle vuote in coda in una riga devono essere eliminate. Il valore predefinito è "false".

###  Osservazioni

Quando si salva con la modalità LightCells e non è stato specificato [`TxtSaveOptions.export_area`](/cells/python-net/it/aspose.cells/txtsaveoptions#export_area),
questa opzione non ha effetto e una riga verrà estesa solo all'ultima cella fornita da
l'implementazione [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/it/aspose.cells/txtsaveoptions)
###  Definizione:
```python
@property
def trim_tailing_blank_cells(self):
    ...
@trim_tailing_blank_cells.setter
def trim_tailing_blank_cells(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`TxtSaveOptions`](/cells/python-net/it/aspose.cells/txtsaveoptions)
