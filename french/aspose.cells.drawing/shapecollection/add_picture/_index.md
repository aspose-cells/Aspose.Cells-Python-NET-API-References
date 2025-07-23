---
title: méthode add_picture
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 230
url: /fr/aspose.cells.drawing/shapecollection/add_picture/
is_root: false
---
##  add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Ajoute une image à la collection.


###  Retour

[`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture) Objet photo.


```python

def add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| lower_right_row | int | Index de la ligne inférieure droite|
| lower_right_column | int | Index de la colonne inférieure droite|
| stream | io.RawIOBase | Objet de flux qui contient les données d'image.|

###  Exemple

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 0, 1, 0, fs)

```


##  add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Ajoute une image à la collection.


###  Retour

[`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture) Objet photo.


```python

def add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| stream | io.RawIOBase | Objet de flux qui contient les données d'image.|
| width_scale | int | Échelle de largeur de l'image, un pourcentage.|
| height_scale | int | Échelle de hauteur de l'image, un pourcentage.|

###  Exemple

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 1, fs, 50, 60)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
