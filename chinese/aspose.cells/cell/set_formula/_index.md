---
title: set_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 350
url: /zh/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula(self, formula, value) {#str-any}
设置公式以及公式的值（计算结果）。



```python

def set_formula(self, formula, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| value | any |公式的值（计算结果）。|


##  set_formula(self, formula, options) {#str-aspose.cells.FormulaParseOptions}
设置公式以及公式的值（计算结果）。



```python

def set_formula(self, formula, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。|


##  set_formula(self, formula, options, value) {#str-aspose.cells.FormulaParseOptions-any}
设置公式以及公式的值（计算结果）。



```python

def set_formula(self, formula, options, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。|
| value | any |公式的值（计算结果）。|


##  set_formula(self, formula, is_r1c1, is_local, value) {#str-bool-bool-any}
设置公式和公式的值。



```python

def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |公式。|
| is_r1c1 | bool |公式是否为R1C1公式。|
| is_local | bool |公式是否采用区域设置格式。|
| value | any |公式的值。|
### 注意事项

注意：此类现已过时。取而代之的是
请使用Cell.SetFormula(string,FormulaParseOptions,object)。
该房产将于 2019 年 12 月起 12 个月后被移除。
Aspose 对于您所遇到的不便深表歉意。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
