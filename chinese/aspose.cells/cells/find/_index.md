---
title: find方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 290
url: /zh/aspose.cells/cells/find/
is_root: false
---
##  find(self, what, previous_cell) {#any-aspose.cells.Cell}
查找包含输入对象的单元格。


### 返回

Cell 对象。


```python

def find(self, what, previous_cell):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| what | any |要搜索的对象。<br/>类型应为 int、double、DateTime、string、bool。|
| previous_cell | [`Cell`](/cells/python-net/zh/aspose.cells/cell) |具有相同对象的前一个单元格。<br/>如果从头开始搜索，则可以将此参数设置为空。|
### 注意事项

如果未找到单元格，则返回 null (Nothing)。

##  find(self, what, previous_cell, find_options) {#any-aspose.cells.Cell-aspose.cells.FindOptions}

查找包含输入对象的单元格。


### 返回

Cell 对象。


```python

def find(self, what, previous_cell, find_options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| what | any |要搜索的对象。<br/>类型应为 int、double、DateTime、string、bool。|
| previous_cell | [`Cell`](/cells/python-net/zh/aspose.cells/cell) |具有相同对象的前一个单元格。<br/>如果从头开始搜索，则可以将此参数设置为空。|
| find_options | [`FindOptions`](/cells/python-net/zh/aspose.cells/findoptions) |查找选项|
### 注意事项

如果未找到单元格，则返回 null (Nothing)。


### 也可以看看

* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
