---
title: update_custom_function_definition方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 410
url: /zh/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition {#aspose.cells.CustomFunctionDefinition}
更新自定义函数的定义。



```python
def update_custom_function_definition(self, definition):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/zh/aspose.cells/customfunctiondefinition) |针对用户的特殊需求专门定义自定义功能。|
### 评论

该方法可用于一些特殊场景。例如，如果用户需要一些参数
一些自定义函数以数组模式计算，然后用户可以提供自己的定义并实现
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/zh/aspose.cells/customfunctiondefinition/get_array_mode_parameters) 用于这些功能。
公式数据更新后，指定的参数会自动以数组方式计算
计算相应的自定义函数时。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
