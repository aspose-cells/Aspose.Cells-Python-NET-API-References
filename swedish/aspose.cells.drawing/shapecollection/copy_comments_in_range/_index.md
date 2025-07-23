---
title: copy_comments_in_range metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 400
url: /sv/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
Kopiera alla kommentarer i intervallet.



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection) | Källformerna.|
| ca | [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) | Källintervallet.|
| dest_row | int | Startraden för målintervallet.|
| dest_column | int | Startkolumnen för målintervallet.|

###  Exempel

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



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
