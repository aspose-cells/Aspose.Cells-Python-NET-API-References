---
title: border_line_color 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 310
url: /zh/aspose.cells.drawing/picture/border_line_color/
is_root: false
---
## border_line_color 属性

表示图片边框线的颜色。

### 例子

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Adding a picture at the location of a cell whose row and column indices are 1 in the worksheet. It is "B2" cell
imgIndex = worksheet.pictures.add(1, 1, "example.jpeg")
# Get the inserted picture object
pic = worksheet.pictures[imgIndex]
# Set the border color of the picture
pic.border_line_color = Color.red
# Save the excel file.
workbook.save("result.xlsx")

```
### 定义：
```python
@property
def border_line_color(self):
    ...
@border_line_color.setter
def border_line_color(self, value):
    ...
```

### 也可以看看
* 模块 [aspose.cells.drawing](../../)
* 类 [Picture](/cells/python-net/zh/aspose.cells.drawing/picture)
