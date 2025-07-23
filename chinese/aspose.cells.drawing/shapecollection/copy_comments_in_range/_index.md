---
title: copy_comments_in_range方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 400
url: /zh/aspose.cells.drawing/shapecollection/copy_comments_in_range/
is_root: false
---
##  copy_comments_in_range(self, shapes, ca, dest_row, dest_column) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int}
复制范围内的所有注意事项。



```python

def copy_comments_in_range(self, shapes, ca, dest_row, dest_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| shapes | [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection) |源形状。|
| ca | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |源范围。|
| dest_row | int |目标范围的起始行。|
| dest_column | int |目标范围起始列。|

### 例子

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



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
