---
title: Column类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells/column/
is_root: false
---
## Column类
代表工作表中的单个列。



Column 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [index](/cells/python-net/zh/aspose.cells/column/index) |获取该列的索引。|
| [width](/cells/python-net/zh/aspose.cells/column/width) |获取和设置以字符为单位的列宽。|
| [group_level](/cells/python-net/zh/aspose.cells/column/group_level) |获取列的组级别。|
| [is_hidden](/cells/python-net/zh/aspose.cells/column/is_hidden) |指示该列是否隐藏。|
| [has_custom_style](/cells/python-net/zh/aspose.cells/column/has_custom_style) |指示该列是否具有自定义样式设置（与从工作簿继承的默认样式不同）。|
| [style](/cells/python-net/zh/aspose.cells/column/style) |获取该列的样式。|
| [is_collapsed](/cells/python-net/zh/aspose.cells/column/is_collapsed) |列是否折叠|


### 方法
|方法|描述|
| :- | :- |
| [apply_style](/cells/python-net/zh/aspose.cells/column/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) |应用整列的格式。|
| [get_style](/cells/python-net/zh/aspose.cells/column/get_style/#) |获取该列的样式。|
| [set_style](/cells/python-net/zh/aspose.cells/column/set_style/#aspose.cells.Style) |设置该列的样式。|



### 例子

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first Column
column = worksheet.cells.columns[0]
# Apply Style to first Column
column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
