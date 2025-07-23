---
title: méthode set_desired_size
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.rendering/svgimageoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Définit la largeur et la hauteur souhaitées de l'image.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| desired_width | int | largeur souhaitée en pixels|
| desired_height | int | hauteur souhaitée en pixels|
###  Remarques

REMARQUE : Ce membre est désormais obsolète. À la place,
veuillez utiliser [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/set_desired_size) en définissant le paramètre keepAspectRatio sur false.
 Cette propriété sera supprimée 12 mois plus tard soit en mai 2023.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Définit la largeur et la hauteur souhaitées de l'image.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| desired_width | int | largeur souhaitée en pixels|
| desired_height | int | hauteur souhaitée en pixels|
| keep_aspect_ratio | bool | s'il faut conserver le rapport hauteur/largeur de l'image d'origine|
###  Remarques

La largeur et la hauteur de l'image de sortie en pixels seront uniquement basées sur
l'ensemble largeur et hauteur souhaitées.


Le [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) et le [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
n'affectera pas la largeur et la hauteur de l'image de sortie dans ce cas.


###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`SvgImageOptions`](/cells/python-net/fr/aspose.cells.rendering/svgimageoptions)
