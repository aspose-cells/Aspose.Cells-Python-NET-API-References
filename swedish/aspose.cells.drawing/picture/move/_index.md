---
title: move metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 180
url: /sv/aspose.cells.drawing/picture/move/
is_root: false
---
##  move(self, upper_left_row, upper_left_column) {#int-int}
Flyttar bilden till en angiven plats.



```python

def move(self, upper_left_row, upper_left_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|

###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Adding a picture at the location of a cell whose row and column indices are 1 in the worksheet. It is "B2" cell
imgIndex = worksheet.pictures.add(1, 1, "example.jpeg")
# Get the inserted picture object
pic = worksheet.pictures[imgIndex]
# Set the new location of the picture
pic.move(2, 4)
# Save the excel file.
workbook.save("result.xlsx")

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)
