---
title: horizontal_resolution proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 180
url: /it/aspose.cells.rendering/svgimageoptions/horizontal_resolution/
is_root: false
---
##  horizontal_resolution proprietà

Ottiene o imposta la risoluzione orizzontale delle immagini generate, in punti per pollice.

###  Osservazioni

Il valore predefinito è 96.


Impostazione [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) e [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
influisce sulla larghezza e l'altezza dell'immagine in output in pixel.

###  Esempio

 Il codice seguente imposta la risoluzione a 192, la larghezza e l'altezza dell'immagine generata sono il doppio di
quello con risoluzione lasciata come valore predefinito 96.

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
###  Definizione:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SvgImageOptions`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions)
