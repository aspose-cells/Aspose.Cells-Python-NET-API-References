---
title: DataBar类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 420
url: /zh/aspose.cells/databar/
is_root: false
---
## DataBar类
描述 DataBar 条件格式规则。
此条件格式规则显示分级
单元格范围内的数据栏。



DataBar 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [axis_color](/cells/python-net/zh/aspose.cells/databar/axis_color) |获取具有条件格式作为数据条的单元格的轴颜色。|
| [axis_position](/cells/python-net/zh/aspose.cells/databar/axis_position) |获取或设置条件格式规则指定的数据条的轴位置。|
| [bar_fill_type](/cells/python-net/zh/aspose.cells/databar/bar_fill_type) |获取或设置数据栏如何填充颜色。|
| [direction](/cells/python-net/zh/aspose.cells/databar/direction) |获取或设置数据栏的显示方向。|
| [bar_border](/cells/python-net/zh/aspose.cells/databar/bar_border) |获取指定数据栏边框的对象。|
| [negative_bar_format](/cells/python-net/zh/aspose.cells/databar/negative_bar_format) |获取与数据栏条件格式设置规则关联的 NegativeBarFormat 对象。|
| [min_cfvo](/cells/python-net/zh/aspose.cells/databar/min_cfvo) |获取或设置此 DataBar 的最小值对象。<br/>无法将 FormatConditionValueType.Max 类型设置为 null 或 CFValueObject。|
| [max_cfvo](/cells/python-net/zh/aspose.cells/databar/max_cfvo) |获取或设置此 DataBar 的最大值对象。<br/>无法将 FormatConditionValueType.Min 类型设置为 null 或 CFValueObject。|
| [color](/cells/python-net/zh/aspose.cells/databar/color) |获取或设置此数据栏的颜色。|
| [min_length](/cells/python-net/zh/aspose.cells/databar/min_length) |表示数据条的最小长度。|
| [max_length](/cells/python-net/zh/aspose.cells/databar/max_length) |表示数据条的最大长度。|
| [show_value](/cells/python-net/zh/aspose.cells/databar/show_value) |获取或设置指示是否显示应用此数据栏的单元格的值的标志。<br/>默认值为 true。|


### 方法
|方法|描述|
| :- | :- |
| [to_image](/cells/python-net/zh/aspose.cells/databar/to_image/#aspose.cells.Cell-aspose.cells.rendering.ImageOrPrintOptions) |将单元格中的数据条渲染为图像字节数组。|



### 例子

```python
from aspose.cells import CellArea, DataBarAxisPosition, DataBarBorderType, DataBarFillType, DataBarNegativeColorType, FormatConditionType, FormatConditionValueType, Workbook
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
ca.end_row = 2
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
# Adds condition.
idx = fcs.add_condition(FormatConditionType.DATA_BAR)
fcs.add_area(ca)
cond = fcs[idx]
# Get Databar
dataBar = cond.data_bar
dataBar.color = Color.orange
# Set Databar properties
dataBar.min_cfvo.type = FormatConditionValueType.PERCENTILE
dataBar.min_cfvo.value = 30
dataBar.show_value = False
dataBar.bar_border.type = DataBarBorderType.SOLID
dataBar.bar_border.color = Color.plum
dataBar.bar_fill_type = DataBarFillType.SOLID
dataBar.axis_color = Color.red
dataBar.axis_position = DataBarAxisPosition.MIDPOINT
dataBar.negative_bar_format.color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.color = Color.white
dataBar.negative_bar_format.border_color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.border_color = Color.yellow
# Put Cell Values
cell1 = sheet.cells.get("A1")
cell1.put_value(10)
cell2 = sheet.cells.get("A2")
cell2.put_value(120)
cell3 = sheet.cells.get("A3")
cell3.put_value(260)
# Saving the Excel file
workbook.save("book1.xlsx")

```

### 也可以看看
* 模块[`aspose.cells`](..)
