---
title: ShapePath类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 540
url: /zh/aspose.cells.drawing/shapepath/
is_root: false
---
## ShapePath类
表示由一系列动作、线条和曲线组成的创作路径，组合起来会形成几何形状。



ShapePath 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.drawing/shapepath/__init__/#) |初始化 [`ShapePath`](/cells/python-net/zh/aspose.cells.drawing/shapepath) 类的新实例。|


### 属性
|属性|描述|
| :- | :- |
| [path_segement_list](/cells/python-net/zh/aspose.cells.drawing/shapepath/path_segement_list) |获取 [`ShapeSegmentPathCollection`](/cells/python-net/zh/aspose.cells.drawing/shapesegmentpathcollection) 列表|
| [width_pixel](/cells/python-net/zh/aspose.cells.drawing/shapepath/width_pixel) |以像素为单位获取此路径的宽度。|
| [height_pixel](/cells/python-net/zh/aspose.cells.drawing/shapepath/height_pixel) |以像素为单位获取此路径的高度。|


### 方法
|方法|描述|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/zh/aspose.cells.drawing/shapepath/move_to/#float-float) |从指定点开始一个新图形，但不关闭当前图形。所有后续添加到路径的点都将添加到这个新图形中。|
| [`line_to(self, x, y)`](/cells/python-net/zh/aspose.cells.drawing/shapepath/line_to/#float-float) |将线段附加到当前图形。<br/>起点是当前图形的终点。|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/zh/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) |将三次贝塞尔曲线附加到当前图形。起点是当前图形的终点。|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/zh/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) |在当前图形后附加一条椭圆弧。起点是当前图形的终点。|
| [`close(self)`](/cells/python-net/zh/aspose.cells.drawing/shapepath/close/#) |关闭当前图形并开始一个新图形。如果当前图形包含一系列连接的直线和曲线，则该方法通过从端点到起点连接一条线来闭合循环。|



### 也可以看看
* 模块[`aspose.cells.drawing`](..)
* 类 [`ShapePath`](/cells/python-net/zh/aspose.cells.drawing/shapepath)
* 类 [`ShapeSegmentPathCollection`](/cells/python-net/zh/aspose.cells.drawing/shapesegmentpathcollection)
