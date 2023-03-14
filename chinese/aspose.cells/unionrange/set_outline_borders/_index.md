---
title: set_outline_borders方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 80
url: /zh/aspose.cells/unionrange/set_outline_borders/
is_root: false
---
##  set_outline_borders(border_styles, border_colors) {#list-aspose.pydrawing.Color[]}
在一系列单元格周围设置线条边框。



```python
def set_outline_borders(self, border_styles, border_colors):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| border_styles | list |边框样式。|
| border_colors | aspose.pydrawing.Color[] |边框颜色。|
### 评论

borderStyles 和 borderStyles 的长度都必须是 4。
borderStyles和borderStyles的顺序必须是top,bottom,left,right

##  set_outline_borders(border_style, border_color) {#CellBorderType-aspose.pydrawing.Color}
在具有相同边框样式和颜色的一系列单元格周围设置轮廓边框。



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| border_style | [CellBorderType](/cells/python-net/zh/aspose.cells/cellbordertype) |边框样式。|
| border_color | aspose.pydrawing.Color |边框颜色。|



### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [UnionRange](/cells/python-net/zh/aspose.cells/unionrange)
