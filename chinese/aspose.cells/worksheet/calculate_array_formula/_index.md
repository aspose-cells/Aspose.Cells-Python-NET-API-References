---
title: calculate_array_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula {#str-aspose.cells.CalculationOptions}
将公式计算为数组公式。



```python
def calculate_array_formula(self, formula, opts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |计算公式。|
| opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|


##  calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}
将公式计算为数组公式。


### 退货

计算公式结果。


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |计算公式。|
| opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
| max_row_count | int |结果数据的最大行数。
| max_column_count | int |结果数据的最大列数。
### 评论

该公式将作为动态数组公式来计算维度和结果。
用户指定的最大维度用于计算结果是大数据集的情况
（例如计算结果可能对应整行或整列数据）
但用户根据业务需求或者出于性能考虑并不需要这么大的数组。

##  calculate_array_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
将公式计算为数组公式。


### 退货

计算公式结果。


```python
def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |计算公式。|
| p_opts | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项|
| c_opts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
| base_cell_row | int |基本单元格的行索引。|
| base_cell_column | int |基本单元格的列索引。|
| max_row_count | int |结果数据的最大行数。
| max_column_count | int |结果数据的最大列数。
| calculation_data | [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata) |计算数据。这是用于情况
### 评论

该公式将作为动态数组公式来计算维度和结果。
用户指定的最大维度用于计算结果是大数据集的情况
（例如计算结果可能对应整行或整列数据）
但用户根据业务需求或者出于性能考虑并不需要这么大的数组。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)