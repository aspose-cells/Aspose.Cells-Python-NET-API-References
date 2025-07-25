---
title: get_display_style方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
获取此单元格的显示样式。


### 返回

该单元格的显示样式


```python

def get_display_style(self):
    ...
```


### 注意事项

与使用 [`BorderType.SIDE_BORDERS`](/cells/python-net/zh/aspose.cells/bordertype#SIDE_BORDERS) 相同
适用于 [`Cell.get_display_style`](/cells/python-net/zh/aspose.cells/cell/get_display_style)。
也就是说，该方法将检查并调整此单元格的顶部/底部/左侧/右侧边框
根据其相邻单元格的样式（[`Cell.get_style`](/cells/python-net/zh/aspose.cells/cell/get_style)），
但不检查合并的单元格，也不检查相邻单元格的显示样式。

##  get_display_style(self, include_merged_borders) {#bool}
获取此单元格的显示样式。


### 返回

该单元格的显示样式


```python

def get_display_style(self, include_merged_borders):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| include_merged_borders | bool |指示是否检查合并单元格的边框。|
### 注意事项

如果指定的标志为假，则与 [`Cell.get_display_style`](/cells/python-net/zh/aspose.cells/cell/get_display_style) 相同。
否则与使用相同
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
适用于 [`Cell.get_display_style`](/cells/python-net/zh/aspose.cells/cell/get_display_style)。

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
获取此单元格的显示样式。


### 返回

该单元格的显示样式


```python

def get_display_style(self, adjacent_borders):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/zh/aspose.cells/bordertype) |指示哪些边界需要检查和调整<br/>根据相邻单元格的边界。|
### 注意事项

如果此单元格还受到其他设置（如条件格式、列表对象等）的影响，
那么显示样式可能与[`Cell.get_style`](/cells/python-net/zh/aspose.cells/cell/get_style)不同。

对于根据相邻单元格调整边界的标志，
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
表示是否检查并合并底部/顶部/右侧/左侧边框
与此单元格相邻的左/右/上/下单元格。

出于性能和兼容性的考虑，
一些枚举用于表示一些特殊操作：

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
表示是否检查并将合并单元格的底部/右边框合并到此单元格。

[`BorderType.DIAGONAL`](/cells/python-net/zh/aspose.cells/bordertype#DIAGONAL)（即 [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) 和
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) 已设置）表示检查并合并边界
来自相邻单元格的显示样式。

请注意，检查相邻单元格的边框/样式，特别是显示样式，
是一个耗时的过程。如果不需要获取返回样式的边框，
使用 [`BorderType.NONE`](/cells/python-net/zh/aspose.cells/bordertype#NONE) 禁用相邻单元的过程
将会有更好的表现。
当仅从这些单元格上定义的样式获取相邻单元格的边框时（不设置
[`BorderType.DIAGONAL`](/cells/python-net/zh/aspose.cells/bordertype#DIAGONAL)），性能也可能更好，因为检查
一个单元格的显示样式也比较耗时。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
