---
title: IconSet类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 850
url: /zh/aspose.cells/iconset/
is_root: false
---
## IconSet类
描述IconSet条件格式规则。
此条件格式规则将图标应用于单元格
根据他们的价值观。



IconSet 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [cf_icons](/cells/python-net/zh/aspose.cells/iconset/cf_icons) |从集合中获取[`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon)|
| [cfvos](/cells/python-net/zh/aspose.cells/iconset/cfvos) |获取 CFValueObjects 实例。|
| [type](/cells/python-net/zh/aspose.cells/iconset/type) |获取或设置要显示的图标集类型。<br/>设置类型将自动检查当前 Cfvos 的数量是否<br/>符合新型号。如果不符合，旧的Cfvos将被清洗，并<br/>将添加默认 Cfvos。|
| [is_custom](/cells/python-net/zh/aspose.cells/iconset/is_custom) |指示图标集是否是自定义的。<br/>默认值为 false。|
| [show_value](/cells/python-net/zh/aspose.cells/iconset/show_value) |获取或设置标志，指示是否显示应用此图标集的单元格的值。<br/>默认值为 true。|
| [reverse](/cells/python-net/zh/aspose.cells/iconset/reverse) |获取或设置指示是否反转此图标集中图标的默认顺序的标志。<br/>默认值为 false。|



### 例子

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

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
idx = fcs.add_condition(FormatConditionType.ICON_SET)
fcs.add_area(ca)
cond = fcs[idx]
# Get Icon Set
iconSet = cond.icon_set
# Set Icon Type
iconSet.type = IconSetType.ARROWS3
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
* 类 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon)
