---
title: BorderCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/bordercollection/
is_root: false
---
## BorderCollection类
封装 [`Border`](/cells/python-net/zh/aspose.cells/border) 个对象的集合。



BorderCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [diagonal_color](/cells/python-net/zh/aspose.cells/bordercollection/diagonal_color) |获取或设置对角线的颜色。|
| [diagonal_style](/cells/python-net/zh/aspose.cells/bordercollection/diagonal_style) |获取或设置对角线的样式。|


### 方法
|方法|描述|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/zh/aspose.cells/bordercollection/get/#aspose.cells.bordertype) |通过 .Net 添加 API for Python，因为不支持此[BorderType borderType]|
| [`set_color(self, color)`](/cells/python-net/zh/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) |设置集合中所有边框的颜色。|
| [`set_style(self, style)`](/cells/python-net/zh/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) |设置集合中所有边框的样式。|



### 例子

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Visit Aspose!")
style = cell.get_style()
# Setting the line style of the top border
style.borders.get(BorderType.TOP_BORDER).line_style = CellBorderType.THICK
# Setting the color of the top border
style.borders.get(BorderType.TOP_BORDER).color = Color.black
# Setting the line style of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).line_style = CellBorderType.THICK
# Setting the color of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).color = Color.black
# Setting the line style of the left border
style.borders.get(BorderType.LEFT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the left border
style.borders.get(BorderType.LEFT_BORDER).color = Color.black
# Setting the line style of the right border
style.borders.get(BorderType.RIGHT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the right border
style.borders.get(BorderType.RIGHT_BORDER).color = Color.black
cell.set_style(style)
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Border`](/cells/python-net/zh/aspose.cells/border)
