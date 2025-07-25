---
title: horizontal_resolution Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 180
url: /de/aspose.cells.rendering/svgimageoptions/horizontal_resolution/
is_root: false
---
##  horizontal_resolution Eigentum

Ruft die horizontale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt sie fest.

###  Bemerkungen

Der Standardwert ist 96.


Einstellung [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) und [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
beeinflusst die Breite und Höhe des Ausgabebildes in Pixeln.

###  Beispiel

 Der folgende Code setzt die Auflösung auf 192, die Breite und Höhe des generierten Bildes ist doppelt so groß wie
die mit der Auflösung belassen als Standardwert 96.

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

###  Siehe auch
* Modul [`aspose.cells.rendering`](../../)
* Klasse [`SvgImageOptions`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions)
