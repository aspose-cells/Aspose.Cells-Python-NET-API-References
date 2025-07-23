---
title: set_dynamic_array_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 340
url: /zh/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
设置动态数组公式，并使公式尽可能溢出到相邻的单元格。


### 返回

公式应该溢出的范围。


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |公式表达式|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。<br/> “解析”选项将被忽略，公式将始终立即解析|
| calculate_value | bool |是否为溢出范围内的单元格计算此动态数组公式。|
### 注意事项

返回的范围可能与该动态数组公式溢出的实际范围不同。
如果范围内有非空单元格，则公式将仅为当前单元格设置并标记为“#SPILL！”。
但对于这种情况我们仍然返回这个公式应该溢出的整个范围。

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
设置动态数组公式，并使公式尽可能溢出到相邻的单元格。


### 返回

公式应该溢出的范围。


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |公式表达式|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。<br/> “解析”选项将被忽略，公式将始终立即解析|
| values | list |具有给定动态数组公式的单元格的值（计算结果）|
| calculate_range | bool |是否计算此动态数组公式的溢出范围。<br/>如果“values”参数不为空且此标志为假，<br/>那么溢出范围的高度将为 values.Length，宽度将为 values[0].Length。|
| calculate_value | bool |当“值”为空时，是否为溢出范围内的单元格计算此动态数组公式<br/>或者一个单元格的“值”中对应的项为空。|
### 注意事项

返回的范围可能与该动态数组公式溢出的实际范围不同。
如果范围内有非空单元格，则公式将仅为当前单元格设置并标记为“#SPILL！”。
但对于这种情况我们仍然返回这个公式应该溢出的整个范围。

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
设置动态数组公式，并使公式尽可能溢出到相邻的单元格。


### 返回

公式应该溢出的范围。


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |公式表达式|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。<br/> “解析”选项将被忽略，公式将始终立即解析|
| values | list |具有给定动态数组公式的单元格的值（计算结果）|
| calculate_range | bool |是否计算此动态数组公式的溢出范围。<br/>如果“values”参数不为空且此标志为假，<br/>那么溢出范围的高度将为 values.Length，宽度将为 values[0].Length。|
| calculate_value | bool |当“值”为空时，是否为溢出范围内的单元格计算此动态数组公式<br/>或者一个单元格的“值”中对应的项为空。|
| copts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项。<br/>通常，出于性能考虑，[`CalculationOptions.recursive`](/cells/python-net/zh/aspose.cells/calculationoptions#recursive) 属性应该为 false。|
### 注意事项

返回的范围可能与该动态数组公式溢出的实际范围不同。
如果范围内有非空单元格，则公式将仅为当前单元格设置并标记为“#SPILL！”。
但对于这种情况我们仍然返回这个公式应该溢出的整个范围。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
