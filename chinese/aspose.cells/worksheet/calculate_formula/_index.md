---
title: calculate_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
计算公式。


### 退货

计算公式结果。


```python
def calculate_formula(self, formula):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |计算公式。|


##  calculate_formula {#str-aspose.cells.CalculationOptions}
直接计算公式表达式。


### 退货

给定公式的计算结果。
返回的对象可能是 [`Cell.value`](/cells/python-net/zh/aspose.cells/cell#value) 或 ReferredArea 类型。


```python
def calculate_formula(self, formula, opts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |计算公式。|
| opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
### 评论

公式的计算方式与单元格 A1 中设置的公式相同。
并且该公式将被视为正常公式。
如果您需要将公式计算为数组公式并获取计算结果的数组，
请改用[`Worksheet.calculate_array_formula`](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula)。

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
计算此工作表中的所有公式。



```python
def calculate_formula(self, options, recursive):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算选项|
| recursive | bool | True 表示如果工作表的单元格依赖于其他工作表的单元格，<br/>其他工作表中的依赖单元格也会被计算。<br/> False 表示工作表中的所有公式均已计算且值正确。|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
直接计算公式表达式。


### 退货

给定公式的计算结果。
返回的对象可能是 [`Cell.value`](/cells/python-net/zh/aspose.cells/cell#value) 或 ReferredArea 类型。


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |计算公式。|
| p_opts | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。|
| c_opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项。|
| base_cell_row | int |基本单元格的行索引。|
| base_cell_column | int |基本单元格的列索引。|
| calculation_data | [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata) |计算数据。这是用于情况<br/>用户在实现自定义计算引擎时需要计算一些静态公式。<br/>对于这种情况，用户需要通过提供的计算数据来指定<br/>[`AbstractCalculationEngine.calculate`](/cells/python-net/zh/aspose.cells/abstractcalculationengine/calculate)。|
### 评论

公式的计算方式就像设置为指定的基本单元格一样。
并且该公式将被视为正常公式。如果您需要将公式计算为数组公式
要获取计算结果的数组，请使用
改为[`Worksheet.calculate_array_formula`](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula)。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
