---
title: merged_cells_shrink_type Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells/deleteblankoptions/merged_cells_shrink_type/
is_root: false
---
##  merged_cells_shrink_type Eigentum

Gibt an, wie verbundene Zellen beim Löschen leerer Zeilen/Spalten verarbeitet werden sollen.

###  Bemerkungen

Für [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/de/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY) werden alle Zellen außer der Zelle oben links als leer betrachtet. Dies ist der Standardwert dieser Eigenschaft.

Für [`MergedCellsShrinkType.NONE`](/cells/python-net/de/aspose.cells/mergedcellsshrinktype#NONE) werden alle darin enthaltenen Zellen als nicht leer betrachtet.

Für [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/de/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT) werden alle Zellen außerhalb des Inhaltsanzeigebereichs als leer betrachtet.
###  Definition:
```python
@property
def merged_cells_shrink_type(self):
    ...
@merged_cells_shrink_type.setter
def merged_cells_shrink_type(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`DeleteBlankOptions`](/cells/python-net/de/aspose.cells/deleteblankoptions)
* Klasse [`MergedCellsShrinkType`](/cells/python-net/de/aspose.cells/mergedcellsshrinktype)
