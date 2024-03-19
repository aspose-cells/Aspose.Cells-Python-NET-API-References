---
title: get_array_mode_parameters方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
获取需要以数组模式计算的给定自定义函数参数的索引。


### 退货

对于给定的自定义函数，需要以数组模式计算的参数的索引。
默认为null，自定义函数没有需要以数组方式计算的参数。


```python
def get_array_mode_parameters(self, function_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| function_name | str |自定义函数的名称。|
### 评论

对于需要计算的表达式，以A:A+B:B为例：
通常在值模式下，它将根据当前单元格基数计算为单个值。
但在数组模式下，A1+B1,A2+B2,A3+B3,...的所有值都会被计算并用于计算。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CustomFunctionDefinition`](/cells/python-net/zh/aspose.cells/customfunctiondefinition)
