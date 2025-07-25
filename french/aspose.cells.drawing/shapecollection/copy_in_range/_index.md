---
title: méthode copy_in_range
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 410
url: /fr/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
Copiez les formes de la plage vers la plage de destination.



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection) | Formes sources.|
| ca | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La gamme source.|
| dest_row | int | L'index de ligne de destination de la plage de destination.|
| dest_column | int | La colonne de destination de la plage de destination.|
| is_contained | bool | Copiez uniquement les formes contenues dans la plage.<br/> Si vrai, copie uniquement les formes de la plage.<br/> Sinon, cela fonctionne comme MS Office.|

###  Exemple

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



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
