---
title: CalculationOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 130
url: /zh/aspose.cells/calculationoptions/
is_root: false
---
## CalculationOptions类
代表计算选项。



CalculationOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/calculationoptions/__init__/#) |构造 CalculationOptions 的新实例|


### 特性
|属性|描述|
| :- | :- |
| [ignore_error](/cells/python-net/zh/aspose.cells/calculationoptions/ignore_error) |指示是否应忽略计算公式时遇到的错误。<br/>错误可能是不支持的功能、外部链接等。<br/>默认值是true。|
| [recursive](/cells/python-net/zh/aspose.cells/calculationoptions/recursive) |指示计算一个单元格时是否递归计算依赖单元格，并且依赖于其他单元格。<br/>默认值是true。|
| [custom_engine](/cells/python-net/zh/aspose.cells/calculationoptions/custom_engine) |自定义公式计算引擎扩展了Aspose.Cells的默认计算引擎。|
| [calculation_monitor](/cells/python-net/zh/aspose.cells/calculationoptions/calculation_monitor) |供用户跟踪公式计算进度的监视器。|
| [calc_stack_size](/cells/python-net/zh/aspose.cells/calculationoptions/calc_stack_size) |用于递归计算单元格的堆栈大小。默认值为 200。|
| [precision_strategy](/cells/python-net/zh/aspose.cells/calculationoptions/precision_strategy) |指定计算处理精度的策略。|
| [linked_data_sources](/cells/python-net/zh/aspose.cells/calculationoptions/linked_data_sources) |指定公式中使用的外部链接的数据源。|
| [character_encoding](/cells/python-net/zh/aspose.cells/calculationoptions/character_encoding) |指定计算公式时用于编码/解码字符的编码。<br/>对于CHAR、CODE等函数，计算结果取决于环境的区域设置和默认字符集。<br/>使用此属性，用户可以指定用于这些函数的正确编码以获得预期结果。|



### 也可以看看
* 模块[`aspose.cells`](..)
