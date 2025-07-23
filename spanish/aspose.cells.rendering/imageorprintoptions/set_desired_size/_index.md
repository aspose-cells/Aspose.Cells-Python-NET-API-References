---
title: método set_desired_size
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.rendering/imageorprintoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Establece el ancho y alto deseados de la imagen.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| desired_width | int | ancho deseado en píxeles|
| desired_height | int | altura deseada en píxeles|
###  Observaciones

NOTA: Este miembro ya no está disponible. En su lugar,
Utilice [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/set_desired_size) configurando el parámetro keepAspectRatio en falso.
 Esta propiedad será eliminada 12 meses después desde mayo de 2023.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Establece el ancho y alto deseados de la imagen.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| desired_width | int | ancho deseado en píxeles|
| desired_height | int | altura deseada en píxeles|
| keep_aspect_ratio | bool | si se debe mantener la relación de aspecto de la imagen de origen|
###  Observaciones

El ancho y la altura de la imagen de salida en píxeles se basarán únicamente en
el ancho y alto deseados.


El [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) y el [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
no afectará el ancho ni la altura de la imagen de salida en este caso.


###  Ver también
* módulo [`aspose.cells.rendering`](../../)
* clase [`ImageOrPrintOptions`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions)
