---
title: CalculationData类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/calculationdata/
is_root: false
---
## CalculationData类
表示计算一个函数时所需要的数据，如函数名、参数等。



CalculationData 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [calculated_value](/cells/python-net/zh/aspose.cells/calculationdata/calculated_value) |获取或设置此函数的计算值。|
| [workbook](/cells/python-net/zh/aspose.cells/calculationdata/workbook) |获取函数所在的工作簿对象。|
| [worksheet](/cells/python-net/zh/aspose.cells/calculationdata/worksheet) |获取函数所在的工作表对象。|
| [cell_row](/cells/python-net/zh/aspose.cells/calculationdata/cell_row) |获取函数所在单元格的行索引。|
| [cell_column](/cells/python-net/zh/aspose.cells/calculationdata/cell_column) |获取函数所在单元格的列索引。|
| [cell](/cells/python-net/zh/aspose.cells/calculationdata/cell) |获取函数所在的Cell对象。|
| [function_name](/cells/python-net/zh/aspose.cells/calculationdata/function_name) |获取要计算的函数名称。|
| [param_count](/cells/python-net/zh/aspose.cells/calculationdata/param_count) |获取参数的数量|


### 方法
|方法|描述|
| :- | :- |
| [`get_param_value(self, index)`](/cells/python-net/zh/aspose.cells/calculationdata/get_param_value/#int) |获取给定索引处参数的表示值对象。|
| [`get_param_value_in_array_mode(self, index, max_row_count, max_column_count)`](/cells/python-net/zh/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) |获取给定索引处的参数值。<br/>如果参数是某种需要计算的表达式，<br/>那么它将以数组模式进行计算。|
| [`get_param_text(self, index)`](/cells/python-net/zh/aspose.cells/calculationdata/get_param_text/#int) |获取给定索引处参数的文字文本。|



### 注意事项

此类提供的所有对象仅用于“读取”目的。
用户在公式计算过程中不应更改工作簿中的任何数据，
否则可能会导致意外结果或异常。

### 也可以看看
* 模块[`aspose.cells`](..)
