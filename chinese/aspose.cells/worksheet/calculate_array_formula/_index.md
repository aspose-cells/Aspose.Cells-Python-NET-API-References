---
title: calculate_array_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
将公式计算为数组公式。



```python

def calculate_array_formula(self, formula, opts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要计算的公式。|
| opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
将公式计算为数组公式。


### 返回

计算公式结果。


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要计算的公式。|
| opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
| max_row_count | int |结果数据的最大行数。<br/>如果它为非正数或大于实际行数，则将使用实际行数。|
| max_column_count | int |结果数据的最大列数。<br/>如果它是非正数或者大于实际行数，则将使用实际列数。|
### 注意事项

该公式将作为动态数组公式来计算维度和结果。
当计算结果为大数据集时，使用用户指定的最大维度
（例如，计算结果可能对应一整行或一整列的数据）
但根据业务需求或者性能考虑，用户并不需要那么大的数组。

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
将公式计算为数组公式。


### 返回

计算公式结果。


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要计算的公式。|
| p_opts | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项|
| c_opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
| base_cell_row | int |基准单元格的行索引。|
| base_cell_column | int |基准单元格的列索引。|
| max_row_count | int |结果数据的最大行数。<br/>如果它为非正数或大于实际行数，则将使用实际行数。|
| max_column_count | int |结果数据的最大列数。<br/>如果它是非正数或者大于实际行数，则将使用实际列数。|
| calculation_data | [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata) |计算数据。它用于以下情况<br/>用户在实现自定义计算引擎时需要计算一些静态公式。<br/>对于这种情况，用户需要使用提供的计算数据进行指定<br/>对于 Aspose.Cells.AbstractCalculationEngine.Calculate。|
### 注意事项

该公式将作为动态数组公式来计算维度和结果。
当计算结果为大数据集时，使用用户指定的最大维度
（例如，计算结果可能对应一整行或一整列的数据）
但根据业务需求或者性能考虑，用户并不需要那么大的数组。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
