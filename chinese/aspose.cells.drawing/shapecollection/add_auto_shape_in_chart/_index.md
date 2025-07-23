---
title: add_auto_shape_in_chart方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 50
url: /zh/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/
is_root: false
---
##  add_auto_shape_in_chart(self, type, top, left, height, width) {#aspose.cells.drawing.AutoShapeType-int-int-int-int}
向图表添加自选图形。


### 返回

返回一个形状对象。


```python

def add_auto_shape_in_chart(self, type, top, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`AutoShapeType`](/cells/python-net/zh/aspose.cells.drawing/autoshapetype) |自动形状类型。|
| top | int |表示文本框与图表区域左上角的垂直偏移量，以 1/4000 为单位。|
| left | int |表示文本框与图表区域左上角的垂直偏移量，以 1/4000 为单位。|
| height | int |表示文本框的高度，以图表区域的1/4000为单位。|
| width | int |表示文本框的宽度，以图表区域的1/4000为单位。|
### 注意事项

类型不能是 Chart/Comment/Picture/OleObject/Polygon/DialogBox


### 也可以看看

* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
