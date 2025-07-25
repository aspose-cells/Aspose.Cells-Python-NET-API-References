---
title: get_leafs方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 160
url: /zh/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
获取直接引用此单元格的所有单元格，并且当此单元格被修改时需要更新。


### 返回

统计所有受抚养人的统计员（Cell）


```python

def get_leafs(self):
    ...
```


### 注意事项

注意：此类现已过时。取而代之的是
请使用 Cell.GetDependentsInCalculation(bool) 获取计算链中的所有受抚养人。
该房产将于 2022 年 5 月起 12 个月后拆除。
Aspose 对于您所遇到的不便深表歉意。

##  get_leafs(self, recursive) {#bool}
获取当此单元格被修改时将更新的所有单元格。


### 返回

统计所有受抚养人的统计员（Cell）


```python

def get_leafs(self, recursive):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| recursive | bool |是否返回那些不直接引用该单元格的叶子<br/>但参考这个细胞的其他叶子|
### 注意事项

注意：此类现已过时。取而代之的是
请使用 Cell.GetDependentsInCalculation(bool) 获取计算链中的所有受抚养人。
该房产将于 2022 年 5 月起 12 个月后拆除。
Aspose 对于您所遇到的不便深表歉意。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
