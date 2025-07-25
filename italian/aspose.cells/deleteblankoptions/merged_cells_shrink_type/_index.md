---
title: merged_cells_shrink_type proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/deleteblankoptions/merged_cells_shrink_type/
is_root: false
---
##  merged_cells_shrink_type proprietà

Indica come elaborare le celle unite quando si eliminano righe/colonne vuote.

###  Osservazioni

Per [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/it/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY), tutte le celle al suo interno saranno considerate vuote, tranne la cella in alto a sinistra, che non è vuota. È il valore predefinito di questa proprietà.

Per [`MergedCellsShrinkType.NONE`](/cells/python-net/it/aspose.cells/mergedcellsshrinktype#NONE), tutte le celle in esso contenute saranno considerate non vuote.

Per [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/it/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT), tutte le celle esterne all'area di visualizzazione del contenuto verranno considerate vuote.
###  Definizione:
```python
@property
def merged_cells_shrink_type(self):
    ...
@merged_cells_shrink_type.setter
def merged_cells_shrink_type(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`DeleteBlankOptions`](/cells/python-net/it/aspose.cells/deleteblankoptions)
* classe [`MergedCellsShrinkType`](/cells/python-net/it/aspose.cells/mergedcellsshrinktype)
