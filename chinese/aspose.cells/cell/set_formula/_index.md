---
title: set_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 340
url: /zh/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
设置公式和公式的值（计算结果）。



```python
def set_formula(self, formula, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| value | any |公式的值（计算结果）。|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
设置公式和公式的值（计算结果）。



```python
def set_formula(self, formula, options, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |用于解析公式的选项。|
| value | any |公式的值（计算结果）。|


##  set_formula {#str-bool-bool-any}
设置公式和公式的值。



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| is_r1c1 | bool |式子是否为R1C1式子。|
| is_local | bool |公式是否采用区域设置格式。|
| value | any |公式的值。|
### 评论

注意：该类现已过时。反而，
请使用 Cell.SetFormula(string,FormulaParseOptions,object)。
该房产将于 2019 年 12 月起 12 个月后被移除。
Aspose 对于给您带来的任何不便，我们深表歉意。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
