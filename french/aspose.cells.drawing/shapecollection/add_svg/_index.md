---
title: méthode add_svg
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 330
url: /fr/aspose.cells.drawing/shapecollection/add_svg/
is_root: false
---
##  add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
Ajoute une image svg.


###  Retour




```python

def add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de la forme par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Le décalage horizontal de la forme par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | La hauteur de la forme, en unité de pixel.|
| width | int | La largeur de la forme, en unité de pixel.|
| svg_data | bytes | Les données d'image svg.|
| compatible_image_data | bytes | Données d'image converties à partir de svg afin d'être compatibles avec Excel 2016 ou les versions inférieures.|

###  Exemple

```python
from aspose import pycore
import bytearray
import int

#  add a svg
with open("image.svg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    picture = shapes.add_svg(4, 0, 5, 0, -1, -1, imageData, None)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
