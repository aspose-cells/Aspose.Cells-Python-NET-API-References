---
title: Border类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/border/
is_root: false
---
## Border类
封装代表单元格边框的对象。



Border 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [theme_color](/cells/python-net/zh/aspose.cells/border/theme_color) |获取并设置边框的主题颜色。|
| [color](/cells/python-net/zh/aspose.cells/border/color) |获取或设置边框的颜色。|
| [argb_color](/cells/python-net/zh/aspose.cells/border/argb_color) |获取并设置具有 32 位 ARGB 值的颜色。|
| [line_style](/cells/python-net/zh/aspose.cells/border/line_style) |获取或设置单元格边框类型。|



### 例子

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
# Set top border style and color
border = style.borders.get(BorderType.TOP_BORDER)
border.line_style = CellBorderType.MEDIUM
border.color = Color.red
cell.set_style(style)

```

### 也可以看看
* 模块[`aspose.cells`](..)
