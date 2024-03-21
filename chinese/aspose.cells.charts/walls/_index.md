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
封装代表 3D 图表墙的对象。



**遗产：** [`Walls`](/cells/python-net/aspose.cells.charts/walls) → 
[`Floor`](/cells/python-net/aspose.cells.charts/floor) → 
[`Area`](/cells/python-net/zh/aspose.cells.drawing/area)



Walls 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [background_color](/cells/python-net/zh/aspose.cells.charts/walls/background_color) |获取或设置[`Area`](/cells/python-net/zh/aspose.cells.drawing/area)的背景颜色。|
| [foreground_color](/cells/python-net/zh/aspose.cells.charts/walls/foreground_color) |获取或设置前景色。|
| [formatting](/cells/python-net/zh/aspose.cells.charts/walls/formatting) |代表区域的格式。|
| [invert_if_negative](/cells/python-net/zh/aspose.cells.charts/walls/invert_if_negative) |如果该属性为 true 并且图表点的值为负数，<br/>前景色和背景色将被交换。|
| [fill_format](/cells/python-net/zh/aspose.cells.charts/walls/fill_format) |表示一个 [`Area.fill_format`](/cells/python-net/zh/aspose.cells.drawing/area#fill_format) 对象，其中包含指定图表或形状的填充格式属性。|
| [transparency](/cells/python-net/zh/aspose.cells.charts/walls/transparency) |返回或设置区域的透明度，其值范围为 0.0（不透明）到 1.0（透明）。|
| [border](/cells/python-net/zh/aspose.cells.charts/walls/border) |获取或设置边框 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)。|
| [center_x](/cells/python-net/zh/aspose.cells.charts/walls/center_x) |调用 Chart.Calculate() 方法后，获取 Wall 中心左下角的 x 坐标，单位为图表宽度的 1/4000。|
| [center_y](/cells/python-net/zh/aspose.cells.charts/walls/center_y) |调用Chart.Calculate()方法后，获取Wall中心左下角的y坐标，单位为图表高度的1/4000。|
| [width](/cells/python-net/zh/aspose.cells.charts/walls/width) |调用 Chart.Calculate() 方法后，以图表宽度的 1/4000 为单位获取从左到右的宽度。|
| [depth](/cells/python-net/zh/aspose.cells.charts/walls/depth) |调用 Chart.Calculate() 方法后，以图表宽度的 1/4000 为单位获取从前到后的深度。|
| [height](/cells/python-net/zh/aspose.cells.charts/walls/height) |调用 Chart.Calculate() 方法后，以图表高度的 1/4000 为单位获取从上到下的高度。|
| [center_x_px](/cells/python-net/zh/aspose.cells.charts/walls/center_x_px) |调用 Chart.Calculate() 方法后，获取墙中心左下角的 x 坐标（以像素为单位）。|
| [center_y_px](/cells/python-net/zh/aspose.cells.charts/walls/center_y_px) |调用 Chart.Calculate() 方法后，获取墙中心左下角的 y 坐标（以像素为单位）。|
| [width_px](/cells/python-net/zh/aspose.cells.charts/walls/width_px) |调用 Chart.Calculate() 方法后获取从左到右的宽度（以像素为单位）。|
| [depth_px](/cells/python-net/zh/aspose.cells.charts/walls/depth_px) |调用 Chart.Calculate() 方法后获取从前到后的深度（以像素为单位）。|
| [height_px](/cells/python-net/zh/aspose.cells.charts/walls/height_px) |调用 Chart.Calculate() 方法后，获取以像素为单位的从上到下的高度。|


### 方法
|方法|描述|
| :- | :- |
| [get_cube_point_count](/cells/python-net/zh/aspose.cells.charts/walls/get_cube_point_count/#) |调用Chart.Calculate()方法后获取立方体点数。|
| [get_cube_point_x_px](/cells/python-net/zh/aspose.cells.charts/walls/get_cube_point_x_px/#int) |调用 Chart.Calculate() 方法后获取墙立方体顶点的 x 坐标。<br/>墙体立方体的顶点数为八|
| [get_cube_point_y_px](/cells/python-net/zh/aspose.cells.charts/walls/get_cube_point_y_px/#int) |调用 Chart.Calculate() 方法后获取墙壁立方体顶点的 y 坐标。<br/>墙体立方体的顶点数为八。|



### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Area`](/cells/python-net/zh/aspose.cells.drawing/area)
* 类 [`Floor`](/cells/python-net/zh/aspose.cells.charts/floor)
* 类 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)
* 类 [`Walls`](/cells/python-net/zh/aspose.cells.charts/walls)
