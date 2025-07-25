---
title: set_outline_borders方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 250
url: /zh/aspose.cells/range/set_outline_borders/
is_root: false
---
##  set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.cells.CellsColor}
设置具有相同边框样式和颜色的单元格区域周围的轮廓边框。



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/zh/aspose.cells/cellbordertype) |边框样式。|
| border_color | [`CellsColor`](/cells/python-net/zh/aspose.cells/cellscolor) |边框颜色。|


##  set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.pydrawing.Color}
设置具有相同边框样式和颜色的单元格区域周围的轮廓边框。



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/zh/aspose.cells/cellbordertype) |边框样式。|
| border_color | aspose.pydrawing.Color |边框颜色。|


##  set_outline_borders(self, border_styles, border_colors) {#list-aspose.pydrawing.Color[]}
设置单元格区域周围的线边框。



```python

def set_outline_borders(self, border_styles, border_colors):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| border_styles | list |边框样式。|
| border_colors | aspose.pydrawing.Color[] |边框颜色。|
### 注意事项

borderStyles 和 borderStyles 的长度都必须为 4。
borderStyles和borderStyles的顺序必须是top,bottom,left,right


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
