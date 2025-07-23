---
title: copy_in_range metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 410
url: /sv/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
Kopiera former i området till målområdet.



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection) | Källformer.|
| ca | [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) | Källintervallet.|
| dest_row | int | Dest-radindexet för dest-intervallet.|
| dest_column | int | Dest-kolumnen i dest-intervallet.|
| is_contained | bool | Om endast de former som finns i intervallet ska kopieras.<br/> Om sant kopieras endast formerna inom intervallet.<br/> Annars fungerar det som MS Office.|

###  Exempel

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



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
