---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/horizontalpagebreakcollection/add/
is_root: false
---
##  add(self, row) {#int}
向集合中添加水平分页符。


### 返回

[`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak) 对象索引。


```python

def add(self, row):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int | Cell 行索引，从零开始。|
### 注意事项

在单元格的左上角添加了分页符。
请同时设置水平分页符和垂直分页符。

##  add(self, cell_name) {#str}
向集合中添加水平分页符。


### 返回

[`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak) 对象索引。


```python

def add(self, cell_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_name | str | Cell 名称。|
### 注意事项

在单元格的左上角添加了分页符。
请同时设置水平分页符和垂直分页符。

##  add(self, row, column) {#int-int}
向集合中添加水平分页符。


### 返回

[`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak) 对象索引。


```python

def add(self, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int | Cell 行索引，从零开始。|
| column | int | Cell 列索引，从零开始。|
### 注意事项

在单元格的左上角添加了分页符。
请同时设置水平分页符和垂直分页符。

##  add(self, row, start_column, end_column) {#int-int-int}
向集合中添加水平分页符。


### 返回

[`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak) 对象索引。


```python

def add(self, row, start_column, end_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |行索引，从零开始。|
| start_column | int |起始列索引，从零开始。|
| end_column | int |结束列索引，从零开始。|
### 注意事项

此方法用于 add 打印区域内的水平分页符。


### 也可以看看

* 模块[`aspose.cells`](../../)
* 类 [`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak)
* 类 [`HorizontalPageBreakCollection`](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection)
