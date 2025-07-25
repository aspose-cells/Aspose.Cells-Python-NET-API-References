---
title: méthode add
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/verticalpagebreakcollection/add/
is_root: false
---
##  add(self, column) {#int}
Ajoute un saut de page vertical à la collection.


###  Retour

[`VerticalPageBreak`](/cells/python-net/fr/aspose.cells/verticalpagebreak) index d'objet.


```python

def add(self, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| column | int | Cell index de colonne, basé sur zéro.|
###  Remarques

Le saut de page est ajouté en haut à gauche de la cellule.
Veuillez définir simultanément un saut de page horizontal et un saut de page vertical.

##  add(self, cell_name) {#str}
Ajoute un saut de page vertical à la collection.


###  Retour

[`VerticalPageBreak`](/cells/python-net/fr/aspose.cells/verticalpagebreak) index d'objet.


```python

def add(self, cell_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_name | str | Cell nom.|
###  Remarques

Le saut de page est ajouté en haut à gauche de la cellule.
Veuillez définir simultanément un saut de page horizontal et un saut de page vertical.

##  add(self, row, column) {#int-int}
Ajoute un saut de page vertical à la collection.


###  Retour

[`VerticalPageBreak`](/cells/python-net/fr/aspose.cells/verticalpagebreak) index d'objet.


```python

def add(self, row, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row | int | Cell index de ligne, basé sur zéro.|
| column | int | Cell index de colonne, basé sur zéro.|
###  Remarques

Le saut de page est ajouté en haut à gauche de la cellule.
Veuillez définir simultanément un saut de page horizontal et un saut de page vertical.

##  add(self, start_row, end_row, column) {#int-int-int}
Ajoute un saut de page vertical à la collection.


###  Retour

[`VerticalPageBreak`](/cells/python-net/fr/aspose.cells/verticalpagebreak) index d'objet.


```python

def add(self, start_row, end_row, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start_row | int | Index de ligne de départ, basé sur zéro.|
| end_row | int | Index de fin de ligne, basé sur zéro.|
| column | int | Index de colonne, basé sur zéro.|
###  Remarques

Cette méthode est utilisée pour add un saut de page vertical dans une zone d'impression.


###  Voir également

* module [`aspose.cells`](../../)
* classe [`VerticalPageBreak`](/cells/python-net/fr/aspose.cells/verticalpagebreak)
* classe [`VerticalPageBreakCollection`](/cells/python-net/fr/aspose.cells/verticalpagebreakcollection)
