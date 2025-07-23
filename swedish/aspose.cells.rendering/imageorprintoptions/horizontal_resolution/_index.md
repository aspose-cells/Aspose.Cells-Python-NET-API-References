---
title: horizontal_resolution fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 150
url: /sv/aspose.cells.rendering/imageorprintoptions/horizontal_resolution/
is_root: false
---
##  horizontal_resolution fastighet

Hämtar eller ställer in den horisontella upplösningen för genererade bilder, i punkter per tum.

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
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
opts = ImageOrPrintOptions()
# Set output image type: png.
opts.image_type = ImageType.PNG
# Set resolution to 192.
opts.horizontal_resolution = 192
opts.vertical_resolution = 192
# Render worksheet page to image.
sr = SheetRender(wb.worksheets[0], opts)
sr.to_image(0, "Sheet_Page1.png")

```
###  Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`ImageOrPrintOptions`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions)
