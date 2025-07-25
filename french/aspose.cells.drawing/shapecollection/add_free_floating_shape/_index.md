---
title: méthode add_free_floating_shape
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells.drawing/shapecollection/add_free_floating_shape/
is_root: false
---
##  add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-bytes-bool}
Ajoute une forme flottante libre à la feuille de calcul. S'applique uniquement à la forme de ligne/image.


###  Retour




```python

def add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/fr/aspose.cells.drawing/msodrawingtype) | Le type de forme.|
| top | int | Représente le décalage vertical de la forme par rapport à la ligne supérieure de la feuille de calcul, en unité de pixel.|
| left | int | Représente le décalage horizontal de la forme par rapport à la colonne de gauche de la feuille de calcul, en unité de pixel.|
| height | int | Représente la hauteur de LineShape, en unité de pixel.|
| width | int |Représente la largeur de LineShape, en unité de pixel.|
| image_data | bytes | Les données d'image s'appliquent uniquement à l'image.|
| is_original_size | bool | Si la forme utilise la taille d'origine si la forme est une image.|

###  Exemple

```python
from aspose import pycore
from aspose.cells.drawing import MsoDrawingType
import bytearray
import int

# add a line
floatingShape_Line = shapes.add_free_floating_shape(MsoDrawingType.LINE, 100, 100, 100, 50, None, False)
# add a picture
imageData = None
with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
floatingShape_Picture = shapes.add_free_floating_shape(MsoDrawingType.PICTURE, 200, 100, 100, 50, imageData, False)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
