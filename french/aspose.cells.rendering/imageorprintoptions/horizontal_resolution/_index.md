---
title: horizontal_resolution propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells.rendering/imageorprintoptions/horizontal_resolution/
is_root: false
---
##  horizontal_resolution propriété

Obtient ou définit la résolution horizontale des images générées, en points par pouce.

###  Remarques

La valeur par défaut est 96.


Réglage [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) et [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
affecte la largeur et la hauteur de l'image de sortie en pixels.

###  Exemple

 Le code suivant définit la résolution à 192, la largeur et la hauteur de l'image générée sont deux fois supérieures à
celui avec la résolution laissée comme valeur par défaut 96.

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
###  Définition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`ImageOrPrintOptions`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions)
