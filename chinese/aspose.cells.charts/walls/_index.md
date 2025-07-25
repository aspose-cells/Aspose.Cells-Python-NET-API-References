---
title: Walls类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 360
url: /zh/aspose.cells.charts/walls/
is_root: false
---
## Walls类
封装代表三维图表墙的对象。



**继承：** [`Walls`](/cells/python-net/aspose.cells.charts/walls) → 
[`Floor`](/cells/python-net/aspose.cells.charts/floor) → 
[`Area`](/cells/python-net/zh/aspose.cells.drawing/area)



Walls 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [background_color](/cells/python-net/zh/aspose.cells.charts/walls/background_color) |获取或设置 [`Area`](/cells/python-net/zh/aspose.cells.drawing/area) 的背景颜色。|
| [foreground_color](/cells/python-net/zh/aspose.cells.charts/walls/foreground_color) |获取或设置前景色。|
| [formatting](/cells/python-net/zh/aspose.cells.charts/walls/formatting) |代表该区域的格式。|
| [invert_if_negative](/cells/python-net/zh/aspose.cells.charts/walls/invert_if_negative) |如果该属性为真，且图表点的值为负数，<br/>前景色和背景色将会交换。|
| [fill_format](/cells/python-net/zh/aspose.cells.charts/walls/fill_format) |表示包含指定图表或形状的填充格式属性的 [`Area.fill_format`](/cells/python-net/zh/aspose.cells.drawing/area#fill_format) 对象。|
| [transparency](/cells/python-net/zh/aspose.cells.charts/walls/transparency) |返回或设置该区域的透明度，范围是 0.0（不透明）到 1.0（透明）。|
| [border](/cells/python-net/zh/aspose.cells.charts/walls/border) |获取或设置边框 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)。|
| [center_x](/cells/python-net/zh/aspose.cells.charts/walls/center_x) |调用Chart.Calculate()方法获取墙中心左下角的x坐标，以图表宽度的1/4000为单位。|
| [center_y](/cells/python-net/zh/aspose.cells.charts/walls/center_y) |调用Chart.Calculate()方法获取墙中心左下角的y坐标，以图表高度的1/4000为单位。|
| [width](/cells/python-net/zh/aspose.cells.charts/walls/width) |调用Chart.Calculate()方法后，以图表宽度的1/4000为单位获取从左到右的宽度。|
| [depth](/cells/python-net/zh/aspose.cells.charts/walls/depth) |调用Chart.Calculate()方法后，获取图表宽度从前到后的深度（以1/4000为单位）。|
| [height](/cells/python-net/zh/aspose.cells.charts/walls/height) |调用Chart.Calculate()方法后，获取图表顶部到底部的高度，以1/4000为单位。|
| [center_x_px](/cells/python-net/zh/aspose.cells.charts/walls/center_x_px) |调用Chart.Calculate()方法获取Wall中心左下角的x坐标，以像素为单位。|
| [center_y_px](/cells/python-net/zh/aspose.cells.charts/walls/center_y_px) |调用Chart.Calculate()方法获取墙中心左下角的y坐标，以像素为单位。|
| [width_px](/cells/python-net/zh/aspose.cells.charts/walls/width_px) |调用Chart.Calculate()方法获取从左到右的宽度（以像素为单位）。|
| [depth_px](/cells/python-net/zh/aspose.cells.charts/walls/depth_px) |调用Chart.Calculate()方法获取以像素为单位的前后深度。|
| [height_px](/cells/python-net/zh/aspose.cells.charts/walls/height_px) |调用Chart.Calculate()方法获取以像素为单位的顶部到底部的高度。|


### 方法
|方法|描述|
| :- | :- |
| [`get_cube_point_count(self)`](/cells/python-net/zh/aspose.cells.charts/walls/get_cube_point_count/#) |调用Chart.Calculate()方法获取立方体点的数量。|
| [`get_cube_point_x_px(self, index)`](/cells/python-net/zh/aspose.cells.charts/walls/get_cube_point_x_px/#int) |调用 Chart.Calculate() 方法后获取墙壁立方体顶点的 x 坐标。<br/>立方体墙壁的顶点数为八个|
| [`get_cube_point_y_px(self, index)`](/cells/python-net/zh/aspose.cells.charts/walls/get_cube_point_y_px/#int) |调用 Chart.Calculate() 方法后获取墙壁立方体顶点的 y 坐标。<br/>墙壁立方体的顶点数为八个。|



### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Area`](/cells/python-net/zh/aspose.cells.drawing/area)
* 类 [`Floor`](/cells/python-net/zh/aspose.cells.charts/floor)
* 类 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)
* 类 [`Walls`](/cells/python-net/zh/aspose.cells.charts/walls)
