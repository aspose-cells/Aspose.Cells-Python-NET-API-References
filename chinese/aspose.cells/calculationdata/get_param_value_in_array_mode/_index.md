---
title: get_param_value_in_array_mode方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode {#int-int-int}
获取给定索引处的参数值。
如果参数是某种需要计算的表达式，
然后将以数组方式计算。


### 退货

包含由指定参数表示的所有项目的数组。


```python
def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| index | int |参数索引（从0开始）|
| max_row_count | int |返回数组的行数限制。<br/>如果它为非正数或大于实际行数，则将使用实际行数。|
| max_column_count | int |返回数组的列数限制。<br/>如果它是非正数或大于实际行数，则将使用实际列数。|
### 评论

对于需要计算的表达式，以A:A+B:B为例：
在值模式下，它将根据当前单元格基础计算为单个值。
但在数组模式下，A1+B1,A2+B2,A3+B3,...的所有值都将被计算并用于构造返回的数组。
对于这种情况，最好指定行/列数的限制
（如根据[`Cells.max_data_row`](/cells/python-net/zh/aspose.cells/cells#max_data_row)和[`Cells.max_data_column`](/cells/python-net/zh/aspose.cells/cells#max_data_column)），
否则返回的大数组可能会增加内存成本并产生大量无用数据。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata)
