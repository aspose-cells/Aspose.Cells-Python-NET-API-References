---
title: original_height_inch عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 970
url: /ar/aspose.cells.drawing/picture/original_height_inch/
is_root: false
---
##  original_height_inch عقار

يحصل على الارتفاع الأصلي للصورة، بوحدة البوصة.

###  مثال

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
###  تعريف:
```python
@property
def original_height_inch(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture)
