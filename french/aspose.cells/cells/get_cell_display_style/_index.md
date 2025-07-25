---
title: méthode get_cell_display_style
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 320
url: /fr/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Obtenez le style d'affichage de la cellule donnée.


###  Retour

le style d'affichage de la cellule donnée.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row | int | index de ligne de la cellule donnée|
| column | int | colonne de la cellule donnée|
###  Remarques

Idem avec [`Cell.get_display_style`](/cells/python-net/fr/aspose.cells/cell/get_display_style),
et de même avec l'utilisation du [`BorderType.SIDE_BORDERS`](/cells/python-net/fr/aspose.cells/bordertype#SIDE_BORDERS)
pour [`Cells.get_cell_display_style`](/cells/python-net/fr/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Obtenez le style d'affichage de la cellule donnée.


###  Retour

le style d'affichage de la cellule donnée.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row | int | index de ligne de la cellule donnée|
| column | int | colonne de la cellule donnée|
| adjacent_borders | [`BorderType`](/cells/python-net/fr/aspose.cells/bordertype) | Indique quelles bordures doivent être vérifiées et ajustées en fonction des bordures des cellules adjacentes.<br/>Veuillez consulter la description du même paramètre de<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Remarques

Si la cellule est également affectée par d'autres paramètres tels que la mise en forme conditionnelle, les objets de liste, etc.,
alors le style d'affichage peut être différent de [`Cells.get_cell_style`](/cells/python-net/fr/aspose.cells/cells/get_cell_style).
Et parce que ces paramètres peuvent également être appliqués à des cellules vides (inexistantes),
l'utilisation de cette méthode peut éviter l'instanciation de ces cellules vides
donc les performances seront meilleures que si l'on obtenait l'instance Cell à partir de Cells
et ensuite appeler le [`Cell.get_display_style`](/cells/python-net/fr/aspose.cells/cell/get_display_style).


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
