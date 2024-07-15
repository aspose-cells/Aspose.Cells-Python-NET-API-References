﻿---
title: original_width_inch property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1000
url: /aspose.cells.drawing/picture/original_width_inch/
is_root: false
---

## original_width_inch property


Gets the original width of picture, in unit of inches.

### Example 


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
picWidthInch = pic.original_width_inch
# Save the excel file.
workbook.save("result.xlsx")

```
### Definition:
```python
@property
def original_width_inch(self):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`Picture`](/cells/python-net/aspose.cells.drawing/picture)
