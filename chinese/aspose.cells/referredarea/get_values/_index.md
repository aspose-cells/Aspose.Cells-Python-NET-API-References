---
title: get_values方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values(self) {#}
获取该区域中的单元格值。


### 返回

如果该区域无效，则显示“#REF!”将被退回；
如果该区域是一个单元格，则返回单元格值对象；
否则，返回该区域内所有值的一个二维数组。


```python

def get_values(self):
    ...
```




##  get_values(self, calculate_formulas) {#bool}
获取该区域中的单元格值。


### 返回

如果该区域无效，则显示“#REF!”将被退回；
如果该区域是一个单元格，则返回单元格值对象；
否则，返回该区域内所有值的一个二维数组。


```python

def get_values(self, calculate_formulas):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate_formulas | bool |在这个范围内，如果有一些公式没有计算出来，<br/>此标志表示这些公式是否应递归计算|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ReferredArea`](/cells/python-net/zh/aspose.cells/referredarea)
