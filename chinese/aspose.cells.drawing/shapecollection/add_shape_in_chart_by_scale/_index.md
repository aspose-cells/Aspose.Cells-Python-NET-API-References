---
title: add_shape_in_chart_by_scale方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 300
url: /zh/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/
is_root: false
---
##  add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom) {#aspose.cells.drawing.MsoDrawingType-aspose.cells.drawing.PlacementType-float-float-float-float}
向图表添加形状。所有单位均为图表区域的百分比比例。



```python

def add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/zh/aspose.cells.drawing/msodrawingtype) |绘图类型。|
| placement | [`PlacementType`](/cells/python-net/zh/aspose.cells.drawing/placementtype) |放置类型。|
| left | float |单位是图表区域宽度的百分比比例。|
| top | float |单位是图表区域高度的百分比比例。|
| right | float |单位是图表区域宽度的百分比比例。|
| bottom | float |单位是图表区域高度的百分比比例。|


##  add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data) {#aspose.cells.drawing.MsoDrawingType-aspose.cells.drawing.PlacementType-float-float-float-float-bytes}
向图表添加形状。所有单位都是图表面积的 1/4000。



```python

def add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/zh/aspose.cells.drawing/msodrawingtype) |绘图类型。|
| placement | [`PlacementType`](/cells/python-net/zh/aspose.cells.drawing/placementtype) |放置类型。|
| left | float |单位是图表区域宽度的百分比比例。|
| top | float |单位是图表区域高度的百分比比例。|
| right | float |单位是图表区域宽度的百分比比例。|
| bottom | float |单位是图表区域高度的百分比比例。|
| image_data | bytes |如果形状不是图片或 OLE 对象，则 imageData 应该为空。|



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
