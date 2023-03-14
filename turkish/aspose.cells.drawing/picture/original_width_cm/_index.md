---
title: original_width_cm mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 960
url: /tr/aspose.cells.drawing/picture/original_width_cm/
is_root: false
---
##  original_width_cm mülk

Resmin orijinal genişliğini santimetre cinsinden alır.

###  Örnek

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
###  Tanım:
```python
@property
def original_width_cm(self):
    ...
```

###  Ayrıca bakınız
* modül [aspose.cells.drawing](../../)
* sınıf [Picture](/cells/python-net/tr/aspose.cells.drawing/picture)
