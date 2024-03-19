---
title: AbstractCalculationEngine类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/abstractcalculationengine/
is_root: false
---
## AbstractCalculationEngine类
代表用户自定义计算引擎，扩展默认计算引擎Aspose.Cells。



AbstractCalculationEngine 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [is_param_literal_required](/cells/python-net/zh/aspose.cells/abstractcalculationengine/is_param_literal_required) |指示该引擎在计算时是否需要参数的文字文本。默认值为 false。|
| [is_param_array_mode_required](/cells/python-net/zh/aspose.cells/abstractcalculationengine/is_param_array_mode_required) |表示该引擎是否需要以数组方式计算参数。默认值为 false。<br/>如果计算定制时需要[`CalculationData.get_param_value_in_array_mode`](/cells/python-net/zh/aspose.cells/calculationdata/get_param_value_in_array_mode)<br/>函数和用户尚未更新它们的定义<br/>([`Workbook.update_custom_function_definition`](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition)),<br/>该属性需要设置为 true。|
| [process_built_in_functions](/cells/python-net/zh/aspose.cells/abstractcalculationengine/process_built_in_functions) |是否内置引擎已支持的内置功能<br/>应由该实现进行检查和处理。<br/>默认为 false。|


### 方法
|方法|描述|
| :- | :- |
| [calculate](/cells/python-net/zh/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) |使用给定数据计算一个函数。|



### 评论

用户不应在此实现中直接修改工作簿的任何部分（除了
自定义函数的计算结果，可以通过CalculationData.CalculatedValue属性设置）。
否则可能会导致意外结果或异常。
如果用户在某些自定义函数的实现中需要更改计算结果以外的其他数据，
例如，更改单元格的公式、样式等，用户应该在此实现中收集这些数据
并将其更改出公式计算范围。

### 也可以看看
* 模块[`aspose.cells`](..)
