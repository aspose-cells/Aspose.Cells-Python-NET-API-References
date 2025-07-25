---
title: método copy_comments_in_range
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 400
url: /es/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
Copiar todos los comentarios en el rango.



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection) | Las formas de la fuente.|
| ca | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) | El rango de origen.|
| dest_row | int | La fila de inicio del rango de destino.|
| dest_column | int | La columna de inicio del rango de destino.|

###  Ejemplo

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



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
