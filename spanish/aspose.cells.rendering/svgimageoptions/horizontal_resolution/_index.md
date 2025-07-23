---
title: horizontal_resolution propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells.rendering/svgimageoptions/horizontal_resolution/
is_root: false
---
##  horizontal_resolution propiedad

Obtiene o establece la resolución horizontal de las imágenes generadas, en puntos por pulgada.

###  Observaciones

El valor predeterminado es 96.


Configuración [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) y [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
Afecta el ancho y la altura de la imagen de salida en píxeles.

###  Ejemplo

 El siguiente código establece la resolución a 192, el ancho y la altura de la imagen generada es el doble de
El que tiene la resolución como valor predeterminado 96.

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
###  Definición:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.rendering`](../../)
* clase [`SvgImageOptions`](/cells/python-net/es/aspose.cells.rendering/svgimageoptions)
