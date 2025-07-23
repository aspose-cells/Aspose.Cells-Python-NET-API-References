---
title: Metodo copy_comments_in_range
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 400
url: /it/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
Copia tutti i commenti nell'intervallo.



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection) | Le forme della sorgente.|
| ca | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | L'intervallo di origine.|
| dest_row | int | Riga di inizio dell'intervallo di destinazione.|
| dest_column | int | Colonna di inizio dell'intervallo di destinazione.|

###  Esempio

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



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
