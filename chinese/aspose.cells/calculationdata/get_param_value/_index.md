---
title: get_param_value方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
获取给定索引处参数的表示值对象。


### 退货

参数的计算值。


```python
def get_param_value(self, index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| index | int |参数索引（从0开始）|
### 评论

对于一个参数：

如果是纯值，则返回纯值本身；


如果是引用，则返回ReferredArea对象；


如果它引用具有多个值的数据集，则返回对象数组；



如果是某种表达式需要计算，那么就会以value方式计算
通常会根据当前单元格基数返回单个值。例如，
如果D2公式的一个参数是A:A+B:B，则计算并返回A2+B2。
但是，如果该参数已被指定为数组模式
([`Workbook.update_custom_function_definition`](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition)
或[`FormulaParseOptions.custom_function_definition`](/cells/python-net/zh/aspose.cells/formulaparseoptions#custom_function_definition)),
那么将返回一个数组(object[][])，其项目为A1+B1,A2+B2,....


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata)
