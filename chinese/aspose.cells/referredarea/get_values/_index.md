---
title: get_values方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 30
url: /zh/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values() {#}
获取此区域中的单元格值。


### 返回

如果该区域无效，“#REF!”将被退回；
如果该区域是一个单元格，则返回单元格值对象；
否则为该区域中的所有值返回一个二维数组。


```python
def get_values(self):
    ...
```




##  get_values(calculate_formulas) {#bool}
获取此区域中的单元格值。


### 返回

如果该区域无效，“#REF!”将被退回；
如果该区域是一个单元格，则返回单元格值对象；
否则为该区域中的所有值返回一个二维数组。


```python
def get_values(self, calculate_formulas):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate_formulas | bool |在这个范围内，如果有一些公式没有计算出来，<br/>此标志表示是否应递归计算这些公式|



### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [ReferredArea](/cells/python-net/zh/aspose.cells/referredarea)
