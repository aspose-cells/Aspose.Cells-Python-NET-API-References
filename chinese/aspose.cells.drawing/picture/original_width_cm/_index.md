---
title: original_width_cm属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 990
url: /zh/aspose.cells.drawing/picture/original_width_cm/
is_root: false
---
## original_width_cm属性

获取图片的原始宽度，单位为厘米。

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
# Gets the original width of the picture.
picWidthCM = pic.original_width_cm
# Save the excel file.
workbook.save("result.xlsx")

```
### 定义：
```python
@property
def original_width_cm(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
