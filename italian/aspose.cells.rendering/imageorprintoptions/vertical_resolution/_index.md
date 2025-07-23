---
title: vertical_resolution proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 400
url: /it/aspose.cells.rendering/imageorprintoptions/vertical_resolution/
is_root: false
---
##  vertical_resolution proprietà

Ottiene o imposta la risoluzione verticale delle immagini generate, in punti per pollice.

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
###  Definizione:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`ImageOrPrintOptions`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions)
