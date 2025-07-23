---
title: FormulaParseOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 720
url: /zh/aspose.cells/formulaparseoptions/
is_root: false
---
## FormulaParseOptions类
表示解析公式时的选项。



FormulaParseOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/formulaparseoptions/__init__/#) |构造一个新的 FormulaParseOptions 实例|


### 属性
|属性|描述|
| :- | :- |
| [locale_dependent](/cells/python-net/zh/aspose.cells/formulaparseoptions/locale_dependent) |公式是否采用语言环境格式。默认值为 false。|
| [r1c1_style](/cells/python-net/zh/aspose.cells/formulaparseoptions/r1c1_style) |公式是否为 R1C1 引用样式。默认为 false。|
| [check_add_in](/cells/python-net/zh/aspose.cells/formulaparseoptions/check_add_in) |对于没有外部链接的用户定义函数，是否检查当前工作簿中已有的外部链接中的插件。<br/>默认为 true（如果自定义函数与现有外部链接中的一个插件匹配，则将其作为插件）。|
| [parse](/cells/python-net/zh/aspose.cells/formulaparseoptions/parse) |是否解析给定的公式。默认为 true。<br/>如果为假，则给定的公式字符串将保留为单元格的原样，直到用户调用其他方法来解析它们<br/>或者计算公式等其他操作需要解析的公式数据。|
| [custom_function_definition](/cells/python-net/zh/aspose.cells/formulaparseoptions/custom_function_definition) |解析自定义函数的定义。|



### 也可以看看
* 模块[`aspose.cells`](..)
