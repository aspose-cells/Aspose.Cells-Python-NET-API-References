---
title: custom_function_definition属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/formulaparseoptions/custom_function_definition/
is_root: false
---
## custom_function_definition属性

解析自定义函数的定义。

### 评论

对于一些特殊的需求，比如在用户自定义引擎中计算自定义函数时，
其某些参数需要以数组方式计算，使用该属性可以标记这些参数
解析公式时作为数组模式。否则用户需要稍后更新这些自定义功能
[`Workbook.update_custom_function_definition`](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition) 得到相同的结果。
### 定义：
```python
@property
def custom_function_definition(self):
    ...
@custom_function_definition.setter
def custom_function_definition(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CustomFunctionDefinition`](/cells/python-net/zh/aspose.cells/customfunctiondefinition)
* 类 [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions)
