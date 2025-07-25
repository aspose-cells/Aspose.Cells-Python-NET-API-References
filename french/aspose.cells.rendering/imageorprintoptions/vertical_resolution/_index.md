---
title: vertical_resolution propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 400
url: /fr/aspose.cells.rendering/imageorprintoptions/vertical_resolution/
is_root: false
---
##  vertical_resolution propriété

Obtient ou définit la résolution verticale des images générées, en points par pouce.

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
###  Définition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`ImageOrPrintOptions`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions)
