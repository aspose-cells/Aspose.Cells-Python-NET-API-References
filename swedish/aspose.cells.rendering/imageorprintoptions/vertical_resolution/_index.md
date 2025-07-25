---
title: vertical_resolution fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 400
url: /sv/aspose.cells.rendering/imageorprintoptions/vertical_resolution/
is_root: false
---
##  vertical_resolution fastighet

Hämtar eller ställer in den vertikala upplösningen för genererade bilder, i punkter per tum.

###  Anmärkningar

Standardvärdet är 96.


Inställning [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) och [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
påverkar bredden och höjden på utdatabilden i pixlar.

###  Exempel

 Följande kod ställer in upplösningen till 192, bredden och höjden på den genererade bilden är dubbelt så stor som
den med upplösningen kvar som standardvärde 96.

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

wb = Workbook("Book1.xlsx")
opts = ImageOrPrintOptions()
# Set output image type: png.
opts.image_type = ImageType.PNG
# Set resolution to 192.
opts.horizontal_resolution = 192
opts.vertical_resolution = 192
# Render Chart to image.
wb.worksheets[0].charts[0].to_image("Chart.png", opts)

```
###  Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`ImageOrPrintOptions`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions)
