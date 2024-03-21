---
title: data عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 390
url: /ar/aspose.cells.drawing/picture/data/
is_root: false
---
##  data عقار

يحصل على data من الصورة.

###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# insert first picture
imgIndex1 = worksheet.pictures.add(1, 1, "example1.png")
# Get the inserted picture object
pic1 = worksheet.pictures[imgIndex1]
# insert second picture
imgIndex2 = worksheet.pictures.add(1, 9, "example2.jpeg")
# Get the inserted picture object
pic2 = worksheet.pictures[imgIndex2]
# Assign the byte data of the first image to the second image
pic2.data = pic1.data
# Save the excel file.
workbook.save("result.xlsx")

```
###  تعريف:
```python
@property
def data(self):
    ...
@data.setter
def data(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture)
