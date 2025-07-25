---
title: vertical_resolution Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 430
url: /de/aspose.cells.rendering/svgimageoptions/vertical_resolution/
is_root: false
---
##  vertical_resolution Eigentum

Ruft die vertikale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt sie fest.

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

###  Siehe auch
* Modul [`aspose.cells.rendering`](../../)
* Klasse [`SvgImageOptions`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions)
