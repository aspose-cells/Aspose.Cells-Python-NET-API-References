---
title: signature_line Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1080
url: /de/aspose.cells.drawing/picture/signature_line/
is_root: false
---
##  signature_line Eigentum

Ruft die Signaturzeile ab und setzt sie

###  Beispiel

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing import SignatureLine
import str

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Adding a picture at the location of a cell whose row and column indices are 1 in the worksheet. It is "B2" cell
imgIndex = worksheet.pictures.add(1, 1, pycore.cast(str, None))
# Get the inserted picture object
pic = worksheet.pictures[imgIndex]
#  Create signature line object
s = SignatureLine()
s.signer = "Simon"
s.title = "Development"
s.email = "simon@aspose.com"
#  Assign the signature line object to Picture.
pic.signature_line = s
# Save the excel file.
workbook.save("result.xlsx")

```
###  Definition:
```python
@property
def signature_line(self):
    ...
@signature_line.setter
def signature_line(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`Picture`](/cells/python-net/de/aspose.cells.drawing/picture)
* Klasse [`SignatureLine`](/cells/python-net/de/aspose.cells.drawing/signatureline)
