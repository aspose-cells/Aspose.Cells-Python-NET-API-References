---
title: FormatCondition类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 700
url: /zh/aspose.cells/formatcondition/
is_root: false
---
## FormatCondition类
表示条件格式条件。



FormatCondition 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [formula1](/cells/python-net/zh/aspose.cells/formatcondition/formula1) |获取并设置与条件格式相关的值或表达式。|
| [formula2](/cells/python-net/zh/aspose.cells/formatcondition/formula2) |获取并设置与条件格式相关的值或表达式。|
| [operator](/cells/python-net/zh/aspose.cells/formatcondition/operator) |获取并设置条件格式运算符类型。|
| [stop_if_true](/cells/python-net/zh/aspose.cells/formatcondition/stop_if_true) |真，当此规则评估为真时，不能应用任何优先级较低的规则。<br/>仅适用于 Excel 2007；|
| [priority](/cells/python-net/zh/aspose.cells/formatcondition/priority) |此条件格式规则的优先级。此值用于确定<br/>格式应被评估和渲染。数值越小，优先级越高<br/>更高的数值，其中“1”表示最高优先级。|
| [style](/cells/python-net/zh/aspose.cells/formatcondition/style) |获取或设置条件格式单元格范围的样式。|
| [type](/cells/python-net/zh/aspose.cells/formatcondition/type) |获取和设置条件格式类型。|
| [icon_set](/cells/python-net/zh/aspose.cells/formatcondition/icon_set) |获取条件格式的“IconSet”实例。<br/>默认实例的 IconSetType 是 TrafficLights31。<br/>仅对类型 = IconSet 有效。|
| [data_bar](/cells/python-net/zh/aspose.cells/formatcondition/data_bar) |获取条件格式的“DataBar”实例。<br/>默认实例的颜色是蓝色。<br/>仅对 DataBar 类型有效。|
| [color_scale](/cells/python-net/zh/aspose.cells/formatcondition/color_scale) |获取条件格式的“ColorScale”实例。<br/>默认实例是“绿-黄-红” 3ColorScale 。<br/>仅对类型 = ColorScale 有效。|
| [top10](/cells/python-net/zh/aspose.cells/formatcondition/top10) |获取条件格式的“Top10”实例。<br/>默认实例的规则突出显示单元格<br/>价值处于前 10 名。<br/>仅对类型为 Top10 有效。|
| [above_average](/cells/python-net/zh/aspose.cells/formatcondition/above_average) |获取条件格式的“AboveAverage”实例。<br/>默认实例的规则突出显示以下单元格<br/>高于范围内所有值的平均值。<br/>仅对类型 = AboveAverage 有效。|
| [text](/cells/python-net/zh/aspose.cells/formatcondition/text) | “文本包含”条件格式规则中的文本值。<br/>仅对 type = containsText、notContainsText、beginsWith 和 endsWith 有效。<br/>默认值为空。|
| [time_period](/cells/python-net/zh/aspose.cells/formatcondition/time_period) | “发生日期...”条件格式规则中适用的时间段。<br/>仅对 type = timePeriod 有效。<br/>默认值为 TimePeriodType.Today。|


### 方法
|方法|描述|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/formatcondition/get_formula1/#bool-bool) |获取与此格式条件关联的值或表达式。|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/zh/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) |获取单元格条件格式的值或表达式。|
| [`get_formula1(self, row, column)`](/cells/python-net/zh/aspose.cells/formatcondition/get_formula1/#int-int) |获取单元格条件格式的公式。|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/formatcondition/get_formula2/#bool-bool) |获取与此格式条件关联的值或表达式。|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/zh/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) |获取单元格条件格式的值或表达式。|
| [`get_formula2(self, row, column)`](/cells/python-net/zh/aspose.cells/formatcondition/get_formula2/#int-int) |获取单元格条件格式的公式。|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) |设置与此格式条件关联的值或表达式。|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/formatcondition/set_formula1/#str-bool-bool) |设置与此格式条件关联的值或表达式。|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/formatcondition/set_formula2/#str-bool-bool) |设置与此格式条件关联的值或表达式。|



### 例子

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
