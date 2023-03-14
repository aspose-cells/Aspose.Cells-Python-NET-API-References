---
title: add méthode
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
Ajoute une image à la collection.


###  Retour

[Picture](/cells/python-net/fr/aspose.cells.drawing/picture) indice d'objet.


```python
def add(self, upper_left_row, upper_left_column, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de ligne en haut à gauche.|
| upper_left_column | int | Index de la colonne en haut à gauche.|
| stream | io.RawIOBase | Objet de flux qui contient les données d'image.|

###  Exemple

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(upper_left_row, upper_left_column, file_name) {#int-int-str}
Ajoute une image à la collection.


###  Retour

[Picture](/cells/python-net/fr/aspose.cells.drawing/picture) indice d'objet.


```python
def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de ligne en haut à gauche.|
| upper_left_column | int | Index de la colonne en haut à gauche.|
| file_name | str | Nom du fichier image.|

###  Exemple

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Ajoute une image à la collection.


###  Retour

[Picture](/cells/python-net/fr/aspose.cells.drawing/picture) indice d'objet.


```python
def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de ligne en haut à gauche.|
| upper_left_column | int | Index de la colonne en haut à gauche.|
| lower_right_row | int | Index de ligne en bas à droite|
| lower_right_column | int | Index de la colonne en bas à droite|
| stream | io.RawIOBase | Objet de flux qui contient les données d'image.|

###  Exemple

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, 5, 5, fs)

```


##  add(upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
Ajoute une image à la collection.


###  Retour

[Picture](/cells/python-net/fr/aspose.cells.drawing/picture) indice d'objet.


```python
def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de ligne en haut à gauche.|
| upper_left_column | int | Index de la colonne en haut à gauche.|
| lower_right_row | int | Index de ligne en bas à droite|
| lower_right_column | int | Index de la colonne en bas à droite|
| file_name | str | Nom du fichier image.|

###  Exemple

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Ajoute une image à la collection.


###  Retour

[Picture](/cells/python-net/fr/aspose.cells.drawing/picture) indice d'objet.


```python
def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de ligne en haut à gauche.|
| upper_left_column | int | Index de la colonne en haut à gauche.|
| stream | io.RawIOBase | Objet de flux qui contient les données d'image.|
| width_scale | int | Échelle de la largeur de l'image, un pourcentage.|
| height_scale | int | Échelle de la hauteur de l'image, un pourcentage.|

###  Exemple

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs, 50, 50)

```


##  add(upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
Ajoute une image à la collection.


###  Retour

[Picture](/cells/python-net/fr/aspose.cells.drawing/picture) indice d'objet.


```python
def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de ligne en haut à gauche.|
| upper_left_column | int | Index de la colonne en haut à gauche.|
| file_name | str | Nom du fichier image.|
| width_scale | int | Échelle de la largeur de l'image, un pourcentage.|
| height_scale | int | Échelle de la hauteur de l'image, un pourcentage.|

###  Exemple

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



###  Voir également
* module [aspose.cells.drawing](../../)
* classe [Picture](/cells/python-net/fr/aspose.cells.drawing/picture)
* classe [PictureCollection](/cells/python-net/fr/aspose.cells.drawing/picturecollection)
