---
title: méthode to_image
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 250
url: /fr/aspose.cells.drawing/groupshape/to_image/
is_root: false
---
##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}
Crée l'image de forme et l'enregistre dans un flux au format spécifié.



```python

def to_image(self, stream, image_type):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase | Le flux de sortie.|
| image_type | [`ImageType`](/cells/python-net/fr/aspose.cells.drawing/imagetype) | Le type dans lequel enregistrer l'image.|
###  Remarques

Les formats suivants sont pris en charge :
.bmp, .gif, .jpg, .jpeg, .tiff, .emf.
###  Exemple

```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
Enregistre la forme dans un fichier.



```python

def to_image(self, image_file, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Exemple

```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


##  to_image(self, stream, options) {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Enregistre la forme dans un flux.



```python

def to_image(self, stream, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Exemple

```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`GroupShape`](/cells/python-net/fr/aspose.cells.drawing/groupshape)
