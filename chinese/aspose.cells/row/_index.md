---
title: Row类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1340
url: /zh/aspose.cells/row/
is_root: false
---
## Row类
代表工作表中的一行。



Row 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [is_blank](/cells/python-net/zh/aspose.cells/row/is_blank) |指示该行是否包含任何数据|
| [is_collapsed](/cells/python-net/zh/aspose.cells/row/is_collapsed) |该行是否折叠|
| [height](/cells/python-net/zh/aspose.cells/row/height) |获取和设置行高（以 Point 为单位）。|
| [is_hidden](/cells/python-net/zh/aspose.cells/row/is_hidden) |指示该行是否隐藏。|
| [index](/cells/python-net/zh/aspose.cells/row/index) |获取该行的索引。|
| [group_level](/cells/python-net/zh/aspose.cells/row/group_level) |获取行的组级别。|
| [is_height_matched](/cells/python-net/zh/aspose.cells/row/is_height_matched) |指示行高是否与工作簿当前的默认字体设置匹配。<br/>此属性为 True 还表示行高是“自动”的，无需用户设置自定义高度值。|
| [has_custom_style](/cells/python-net/zh/aspose.cells/row/has_custom_style) |指示该行是否具有自定义样式设置（与从工作簿继承的默认样式设置不同）。|
| [first_cell](/cells/python-net/zh/aspose.cells/row/first_cell) |获取行中的第一个单元格对象。|
| [first_data_cell](/cells/python-net/zh/aspose.cells/row/first_data_cell) |获取行中的第一个非空白单元格。|
| [last_cell](/cells/python-net/zh/aspose.cells/row/last_cell) |获取行中的最后一个单元格对象。|
| [last_data_cell](/cells/python-net/zh/aspose.cells/row/last_data_cell) |获取行中最后一个非空白单元格。|



获取单元格。
### 索引器
|名称|描述|
| :- | :- |
| [index] |列索引|


### 方法
|方法|描述|
| :- | :- |
| [get_cell_by_index](/cells/python-net/zh/aspose.cells/row/get_cell_by_index/#int) |获取该行单元格集合中特定索引的单元格。|
| [get_enumerator](/cells/python-net/zh/aspose.cells/row/get_enumerator/#bool-bool) |获取一个枚举器，该枚举器遍历该行的单元格。|
| [get_cell_or_null](/cells/python-net/zh/aspose.cells/row/get_cell_or_null/#int) |获取特定索引中的单元格或 null。|
| [get_style](/cells/python-net/zh/aspose.cells/row/get_style/#) |获取该行的样式。|
| [set_style](/cells/python-net/zh/aspose.cells/row/set_style/#aspose.cells.Style) |设置该行的样式。|
| [copy_settings](/cells/python-net/zh/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) |复制行的设置，例如样式、高度、可见性等。|
| [apply_style](/cells/python-net/zh/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) |对整行应用格式。|
| [equals](/cells/python-net/zh/aspose.cells/row/equals/#aspose.cells.Row) |检查此对象是否与另一个行对象引用同一行。|



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
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
