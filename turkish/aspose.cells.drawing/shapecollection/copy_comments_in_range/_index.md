---
title: copy_comments_in_range yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 400
url: /tr/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
Aralıktaki tüm yorumları kopyalayın.



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection) | Kaynak şekiller.|
| ca | [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea) | Kaynak aralığı.|
| dest_row | int | Hedef aralığı başlangıç satırı.|
| dest_column | int | Hedef aralığı başlangıç sütunu.|

###  Örnek

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



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
