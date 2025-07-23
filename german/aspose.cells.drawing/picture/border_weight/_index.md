---
title: border_weight Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 360
url: /de/aspose.cells.drawing/picture/border_weight/
is_root: false
---
##  border_weight Eigentum

Ruft die Stärke der Rahmenlinie eines Bildes in pt-Einheiten ab oder legt sie fest.

###  Beispiel

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
# Set the border width of the picture
pic.border_weight = 3.0
# Save the excel file.
workbook.save("result.xlsx")

```
###  Definition:
```python
@property
def border_weight(self):
    ...
@border_weight.setter
def border_weight(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`Picture`](/cells/python-net/de/aspose.cells.drawing/picture)
