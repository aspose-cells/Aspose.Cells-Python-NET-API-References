---
title: calculate_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(self, formula) {#str}
计算公式。


### 返回

计算公式结果。


```python

def calculate_formula(self, formula):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要计算的公式。|


##  calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
直接计算公式表达式。


### 返回

给定公式的计算结果。
返回的对象可能的类型为 [`Cell.value`](/cells/python-net/zh/aspose.cells/cell#value) 或 ReferredArea。


```python

def calculate_formula(self, formula, opts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要计算的公式。|
| opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
### 注意事项

公式将按照设置到单元格 A1 的方式进行计算。
并且该公式将被视为正常公式。
如果需要将公式作为数组公式进行计算并获取计算结果的数组，
请改用 [`Worksheet.calculate_array_formula`](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula)。

##  calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}
计算此工作表中的所有公式。



```python

def calculate_formula(self, options, recursive):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算选项|
| recursive | bool | True 表示如果工作表的单元格依赖于其他工作表的单元格，<br/>其他工作表中的相关单元格也将被计算。<br/> False 表示工作表中的所有公式都已计算并且值正确。|


##  calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
直接计算公式表达式。


### 返回

给定公式的计算结果。
返回的对象可能的类型为 [`Cell.value`](/cells/python-net/zh/aspose.cells/cell#value) 或 ReferredArea。


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要计算的公式。|
| p_opts | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。|
| c_opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项。|
| base_cell_row | int |基准单元格的行索引。|
| base_cell_column | int |基准单元格的列索引。|
| calculation_data | [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata) |计算数据。它用于以下情况<br/>用户在实现自定义计算引擎时需要计算一些静态公式。<br/>对于这种情况，用户需要使用提供的计算数据进行指定<br/>对于 Aspose.Cells.AbstractCalculationEngine.Calculate。|
### 注意事项

公式将按照设置到指定基准单元格的方式进行计算。
公式将被视为普通公式。如果需要将公式作为数组公式计算
要获取计算结果的数组，请使用
[`Worksheet.calculate_array_formula`](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula)。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
