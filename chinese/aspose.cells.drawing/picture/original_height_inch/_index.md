---
title: original_height_inch属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 950
url: /zh/aspose.cells.drawing/picture/original_height_inch/
is_root: false
---
## original_height_inch属性

获取图片的原始高度，单位为英寸。

### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Adding a picture at the location of a cell whose row and column indices are 1 in the worksheet. It is "B2" cell
imgIndex = worksheet.pictures.add(1, 1, "example.jpeg")
# Get the inserted picture object
pic = worksheet.pictures[imgIndex]
# Gets the original height of the picture.
picHeightInch = pic.original_height_inch
# Save the excel file.
workbook.save("result.xlsx")

```
### 定义：
```python
@property
def original_height_inch(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
