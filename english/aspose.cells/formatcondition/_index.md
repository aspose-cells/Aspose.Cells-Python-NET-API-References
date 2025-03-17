﻿---
title: FormatCondition class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 770
url: /aspose.cells/formatcondition/
is_root: false
---

## FormatCondition class

Represents conditional formatting condition.



The FormatCondition type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [formula1](/cells/python-net/aspose.cells/formatcondition/formula1) | Gets and sets the value or expression associated with conditional formatting. |
| [formula2](/cells/python-net/aspose.cells/formatcondition/formula2) | Gets and sets the value or expression associated with conditional formatting. |
| [operator](/cells/python-net/aspose.cells/formatcondition/operator) | Gets and sets the conditional format operator type. |
| [stop_if_true](/cells/python-net/aspose.cells/formatcondition/stop_if_true) | True, no rules with lower priority may be applied over this rule, when this rule evaluates to true.<br/>Only applies for Excel 2007; |
| [priority](/cells/python-net/aspose.cells/formatcondition/priority) | The priority of this conditional formatting rule. This value is used to determine which<br/>format should be evaluated and rendered. Lower numeric values are higher priority than<br/>higher numeric values, where '1' is the highest priority. |
| [style](/cells/python-net/aspose.cells/formatcondition/style) | Gets or setts style of conditional formatted cell ranges. |
| [type](/cells/python-net/aspose.cells/formatcondition/type) | Gets and sets whether the conditional format Type. |
| [icon_set](/cells/python-net/aspose.cells/formatcondition/icon_set) | Get the conditional formatting's "IconSet" instance.<br/>The default instance's IconSetType is TrafficLights31.<br/>Valid only for type = IconSet. |
| [data_bar](/cells/python-net/aspose.cells/formatcondition/data_bar) | Get the conditional formatting's "DataBar" instance.<br/>The default instance's color is blue.<br/>Valid only for type is DataBar. |
| [color_scale](/cells/python-net/aspose.cells/formatcondition/color_scale) | Get the conditional formatting's "ColorScale" instance.<br/>The default instance is a "green-yellow-red" 3ColorScale .<br/>Valid only for type = ColorScale. |
| [top10](/cells/python-net/aspose.cells/formatcondition/top10) | Get the conditional formatting's "Top10" instance.<br/>The default instance's rule highlights cells whose<br/>values fall in the top 10 bracket.<br/>Valid only for type is Top10. |
| [above_average](/cells/python-net/aspose.cells/formatcondition/above_average) | Get the conditional formatting's "AboveAverage" instance.<br/>The default instance's rule highlights cells that are <br/>above the average for all values in the range.<br/>Valid only for type = AboveAverage. |
| [text](/cells/python-net/aspose.cells/formatcondition/text) | The text value in a "text contains" conditional formatting rule. <br/>Valid only for type = containsText, notContainsText, beginsWith and endsWith.<br/>The default value is null. |
| [time_period](/cells/python-net/aspose.cells/formatcondition/time_period) | The applicable time period in a "date occurring…" conditional formatting rule. <br/>Valid only for type = timePeriod.<br/>The default value is TimePeriodType.Today. |


### Methods
| Method | Description |
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/aspose.cells/formatcondition/get_formula1/#bool-bool) | Gets the value or expression associated with this format condition. |
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Gets the value or expression of the conditional formatting of the cell. |
| [`get_formula1(self, row, column)`](/cells/python-net/aspose.cells/formatcondition/get_formula1/#int-int) | Gets the formula of the conditional formatting of the cell. |
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/aspose.cells/formatcondition/get_formula2/#bool-bool) | Gets the value or expression associated with this format condition. |
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Gets the value or expression of the conditional formatting of the cell. |
| [`get_formula2(self, row, column)`](/cells/python-net/aspose.cells/formatcondition/get_formula2/#int-int) | Gets the formula of the conditional formatting of the cell. |
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Sets the value or expression associated with this format condition. |
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Sets the value or expression associated with this format condition. |
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Sets the value or expression associated with this format condition. |



### Example 


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

### See Also
* module [`aspose.cells`](..)
