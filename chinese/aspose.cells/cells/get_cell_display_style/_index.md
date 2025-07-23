---
title: get_cell_display_style方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 320
url: /zh/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
获取给定单元格的显示样式。


### 返回

给定单元格的显示样式。


```python

def get_cell_display_style(self, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |给定单元格的行索引|
| column | int |给定单元格的列|
### 注意事项

与[`Cell.get_display_style`](/cells/python-net/zh/aspose.cells/cell/get_display_style)相同，
与使用 [`BorderType.SIDE_BORDERS`](/cells/python-net/zh/aspose.cells/bordertype#SIDE_BORDERS) 相同
适用于 [`Cells.get_cell_display_style`](/cells/python-net/zh/aspose.cells/cells/get_cell_display_style)。

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
获取给定单元格的显示样式。


### 返回

给定单元格的显示样式。


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |给定单元格的行索引|
| column | int |给定单元格的列|
| adjacent_borders | [`BorderType`](/cells/python-net/zh/aspose.cells/bordertype) |指示哪些边界需要根据相邻单元格的边界进行检查和调整。<br/>请参阅相同参数的描述<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
### 注意事项

如果单元格还受到其他设置（如条件格式、列表对象等）的影响，
那么显示样式可能与[`Cells.get_cell_style`](/cells/python-net/zh/aspose.cells/cells/get_cell_style)不同。
并且由于这些设置也可能适用于空（不存在）单元格，
使用这种方法可以避免这些空单元格的实例化
因此性能将比从 Cells 获取 Cell 实例更好
然后拨打[`Cell.get_display_style`](/cells/python-net/zh/aspose.cells/cell/get_display_style)。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
