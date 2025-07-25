---
title: get_value方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/referredarea/get_value/
is_root: false
---
##  get_value(self, row_offset, col_offset) {#int-int}
获取距该区域左上角给定偏移量的单元格值。


### 返回

“#REF！”如果该区域无效；
如果给定的偏移量超出该区域，则为“#N/A”；
否则返回给定位置的单元格值。


```python

def get_value(self, row_offset, col_offset):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row_offset | int |距该区域起始行的行偏移量|
| col_offset | int |列距该区域起始行的偏移量|


##  get_value(self, row_offset, col_offset, calculate_formulas) {#int-int-bool}
获取距该区域左上角给定偏移量的单元格值。


### 返回

“#REF！”如果该区域无效；
如果给定的偏移量超出该区域，则为“#N/A”；
否则返回给定位置的单元格值。


```python

def get_value(self, row_offset, col_offset, calculate_formulas):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row_offset | int |距该区域起始行的行偏移量|
| col_offset | int |列距该区域起始行的偏移量|
| calculate_formulas | bool |如果指定的引用是公式，是否递归计算|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ReferredArea`](/cells/python-net/zh/aspose.cells/referredarea)
