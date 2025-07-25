---
title: méthode copy_comments_in_range
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 400
url: /fr/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
Copiez tous les commentaires de la plage.



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection) | Les formes de la source.|
| ca | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La gamme source.|
| dest_row | int | La ligne de départ de la plage de destination.|
| dest_column | int | La colonne de début de la plage de destination.|

###  Exemple

```python
from aspose.cells import CellArea

comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex = comments.add(0, 0)
comment = comments[commentIndex]
comment.note = "First note."
comment.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment = comments.get("B2")
comment.note = "Second note."
area1 = CellArea()
area1.start_column = 1
area1.start_row = 1
area1.end_column = 5
area1.end_row = 4
# copy
shapes.copy_comments_in_range(shapes, area1, 5, 1)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
