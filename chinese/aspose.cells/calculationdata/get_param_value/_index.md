---
title: get_param_value方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
获取给定索引处参数的表示值对象。


### 返回

参数的计算值。


```python

def get_param_value(self, index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| index | int |参数的索引（从0开始）|
### 注意事项

对于一个参数：

如果是纯值，则返回纯值本身；


如果是引用，则返回ReferredArea对象；


如果它引用具有多个值的数据集，则返回对象数组；



如果是某种需要计算的表达式，那么就用值模式来计算
通常会根据当前单元格基数返回单个值。例如，
如果 D2 的公式有一个参数是 A:A+B:B，那么就会计算并返回 A2+B2。
然而，如果该参数已指定为数组模式
（由 [`Workbook.update_custom_function_definition`](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition)
或 [`FormulaParseOptions.custom_function_definition`](/cells/python-net/zh/aspose.cells/formulaparseoptions#custom_function_definition))，
然后将返回一个数组（object[][]），其项目为 A1+B1、A2+B2、....


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata)
