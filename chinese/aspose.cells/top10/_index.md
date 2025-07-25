---
title: Top10类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1460
url: /zh/aspose.cells/top10/
is_root: false
---
## Top10类
描述Top10条件格式规则。
此条件格式规则突出显示
值按照规定属于前 N 个或后 N 个括号。



Top10 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/top10/__init__/#) |构造一个新的 Top10 实例|


### 属性
|属性|描述|
| :- | :- |
| [is_percent](/cells/python-net/zh/aspose.cells/top10/is_percent) |获取或设置“前/后 n”规则是否为“前/后 n 百分比”规则。<br/>默认值为 false。|
| [is_bottom](/cells/python-net/zh/aspose.cells/top10/is_bottom) |获取或设置“前/后 n”规则是否为“后 n”规则。<br/>默认值为 false。|
| [rank](/cells/python-net/zh/aspose.cells/top10/rank) |获取或设置“前 n/后 n”条件格式规则中“n”的值。<br/>如果 IsPercent 为真，则该值必须介于 0 到 100 之间。<br/>否则它必须介于 0 到 1000 之间。<br/>默认值为 10。|



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
ca = CellArea.create_cell_area(0, 0, 10, 10)
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.TOP10, OperatorType.NONE, None, None)
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
top10 = fc.top10
# Set the Top N
top10.rank = 5
# Saving the Excel file
workbook.save("output.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
