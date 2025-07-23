---
title: add_add_in_function方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/cellshelper/add_add_in_function/
is_root: false
---
##  add_add_in_function（，函数，最小参数数量，最大参数数量，参数类型，函数值类型）{#str-int-int-list-aspose.cells.ParameterType}
添加插件功能。



```python

@staticmethod
def add_add_in_function(function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| function | str |函数名称。|
| min_count_of_parameters | int |此函数所需的最小参数数量|
| max_count_of_parameters | int |此函数允许的最大参数数量。|
| paramers_type | list |函数的例外参数类型|
| function_value_type | [`ParameterType`](/cells/python-net/zh/aspose.cells/parametertype) |函数值类型。|
### 注意事项

注意：此成员现已过时。相反，
请使用 WorksheetCollection.RegisterAddInFunction() 方法。
该方法将于 2022 年 1 月起 12 个月后取消。
Aspose 对于您所遇到的不便深表歉意。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CellsHelper`](/cells/python-net/zh/aspose.cells/cellshelper)
