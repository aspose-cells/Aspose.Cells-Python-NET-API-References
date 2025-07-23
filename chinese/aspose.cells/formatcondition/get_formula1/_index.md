---
title: get_formula1方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/formatcondition/get_formula1/
is_root: false
---
##  get_formula1(self, is_r1c1, is_local) {#bool-bool}
获取与此格式条件关联的值或表达式。


### 返回

与此格式条件相关的值或表达式。


```python

def get_formula1(self, is_r1c1, is_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| is_r1c1 | bool |公式是否需要格式化为R1C1。|
| is_local | bool |公式是否需要根据语言环境进行格式化。|


##  get_formula1(self, row, column) {#int-int}
获取单元格条件格式的公式。


### 返回

公式。


```python

def get_formula1(self, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |行索引。|
| column | int |列索引。|


##  get_formula1(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
获取单元格条件格式的值或表达式。


### 返回

与单元格的条件格式相关的值或表达式。


```python

def get_formula1(self, is_r1c1, is_local, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| is_r1c1 | bool |公式是否需要格式化为R1C1。|
| is_local | bool |公式是否需要根据语言环境进行格式化。|
| row | int |行索引。|
| column | int |列索引。|
### 注意事项

给定的单元格必须包含在此条件格式中，否则将返回 null。


### 也可以看看

* 模块[`aspose.cells`](../../)
* 类 [`FormatCondition`](/cells/python-net/zh/aspose.cells/formatcondition)
