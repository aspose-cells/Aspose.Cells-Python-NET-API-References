---
title: add_shape方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 280
url: /zh/aspose.cells.drawing/shapecollection/add_shape/
is_root: false
---
##  add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-int-int}
向工作表添加形状。


### 返回

一个 Shape 对象。


```python

def add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/zh/aspose.cells.drawing/msodrawingtype) | Mso 绘图类型。|
| upper_left_row | int |左上行索引。|
| top | int |表示 Shape 距离其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示 Shape 距离其左列的水平偏移量，以像素为单位。|
| height | int |表示Shape的高度，以像素为单位。|
| width | int |表示Shape的宽度，以像素为单位。|
### 注意事项

类型不能是 Chart/Comment/Picture/OleObject/Polygon/DialogBox
### 例子


```python
from aspose.cells.drawing import MsoDrawingType

# Add a shape of the specified type
shapeByType = shapes.add_shape(MsoDrawingType.CELLS_DRAWING, 1, 0, 1, 0, 100, 50)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
