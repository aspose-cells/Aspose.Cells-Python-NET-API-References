---
title: merged_cells_shrink_type fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/deleteblankoptions/merged_cells_shrink_type/
is_root: false
---
##  merged_cells_shrink_type fastighet

Anger hur sammanslagna celler ska bearbetas när tomma rader/kolumner tas bort.

###  Anmärkningar

För [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/sv/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY) kommer alla celler i den att tas som tomma förutom den icke-tomma cellen längst upp till vänster. Det är standardvärdet för den här egenskapen.

För [`MergedCellsShrinkType.NONE`](/cells/python-net/sv/aspose.cells/mergedcellsshrinktype#NONE) kommer alla celler i den att tas som icke-tomma.

För [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/sv/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT) kommer alla celler utanför innehållsvisningsområdet att tas som tomma.
###  Definition:
```python
@property
def merged_cells_shrink_type(self):
    ...
@merged_cells_shrink_type.setter
def merged_cells_shrink_type(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`DeleteBlankOptions`](/cells/python-net/sv/aspose.cells/deleteblankoptions)
* klass [`MergedCellsShrinkType`](/cells/python-net/sv/aspose.cells/mergedcellsshrinktype)
