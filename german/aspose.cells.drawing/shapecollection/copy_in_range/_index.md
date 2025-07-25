---
title: copy_in_range Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 410
url: /de/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
Kopieren Sie die Formen im Bereich in den Zielbereich.



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection) | Quellformen.|
| ca | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) | Der Quellbereich.|
| dest_row | int | Der Zielzeilenindex des Zielbereichs.|
| dest_column | int | Die Zielspalte des Zielbereichs.|
| is_contained | bool | Ob nur die Formen kopiert werden, die im Bereich enthalten sind.<br/> Wenn „true“, werden nur die Formen im Bereich kopiert.<br/> Ansonsten funktioniert es wie MS Office.|

###  Beispiel

```python
from aspose.cells import CellArea

# add a shape
shapes.add_rectangle(2, 0, 2, 0, 130, 130)
area2 = CellArea()
area2.start_column = 1
area2.start_row = 1
area2.end_column = 5
area2.end_row = 11
# copy
shapes.copy_in_range(shapes, area2, 12, 1, False)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
