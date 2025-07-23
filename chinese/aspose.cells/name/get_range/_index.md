---
title: get_range方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/name/get_range/
is_root: false
---
##  get_range(self) {#}
如果此名称指的是一个范围，则获取该范围。


### 返回

范围。


```python

def get_range(self):
    ...
```




##  get_range(self, recalculate) {#bool}
如果此名称指的是一个范围，则获取该范围


### 返回

范围。


```python

def get_range(self, recalculate):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| recalculate | bool |如果此名称在本次调用之前已经计算过，是否重新计算。|


##  get_range(self, sheet_index, row, column) {#int-int-int}
如果此名称指的是一个范围，则获取该范围。
如果该名称的引用不是绝对的，则不同单元格的范围可能会不同。


### 返回

范围。


```python

def get_range(self, sheet_index, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| sheet_index | int |相应的工作表索引。|
| row | int |相应的行索引。|
| column | int |相应的列索引|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Name`](/cells/python-net/zh/aspose.cells/name)
