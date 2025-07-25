---
title: add_area方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
将验证应用于该区域。



```python

def add_area(self, cell_area):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |该区域。|
### 注意事项

相当于使用 [`Validation.add_area`](/cells/python-net/zh/aspose.cells/validation/add_area)
检查交叉点和边缘。

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
将验证应用于该区域。



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |该区域。|
| check_intersection | bool |是否检查给定区域与现有验证区域的交集。<br/>如果在给定区域（或其中一部分）应用了一个验证，<br/>那么首先应该从给定区域中删除现有的验证。<br/>否则可能会导致生成的验证损坏。<br/>如果用户确定添加的区域不与任何现有区域相交，<br/>出于性能考虑，可以将此参数设置为false。|
| check_edge | bool |是否检查此验证应用区域的边缘。<br/>验证的内部设置取决于其应用范围的左上角，<br/>因此，如果给定区域将成为应用范围的新左上角区域，<br/>应更改并重建内部设置，否则可能会导致意外的结果。<br/>如果用户确定添加的区域不是左上角的区域，<br/>出于性能考虑，可以将此参数设置为false。|
### 注意事项

在这种方法中，我们将删除给定区域内的所有旧验证。
对于 Validation 应用范围的左上角，首先它的 StartRow 最小，
其次，它的 StartColumn 是具有相同最小 StartRow 的区域中最小的一个。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Validation`](/cells/python-net/zh/aspose.cells/validation)
