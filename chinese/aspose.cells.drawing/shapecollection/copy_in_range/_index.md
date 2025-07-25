---
title: copy_in_range方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 410
url: /zh/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
将范围内的形状复制到目标范围。



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection) |源形状。|
| ca | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |源范围。|
| dest_row | int |目标范围的目标行索引。|
| dest_column | int |目标范围的目标列。|
| is_contained | bool |是否仅复制范围内包含的形状。<br/>如果为真，则仅复制范围内的形状。<br/>否则，它将像 MS Office 一样运行。|

### 例子

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



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
