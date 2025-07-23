---
title: méthode get_display_style
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Obtient le style d'affichage de cette cellule.


###  Retour

style d'affichage de cette cellule


```python

def get_display_style(self):
    ...
```


###  Remarques

Même chose avec l'utilisation du [`BorderType.SIDE_BORDERS`](/cells/python-net/fr/aspose.cells/bordertype#SIDE_BORDERS)
pour [`Cell.get_display_style`](/cells/python-net/fr/aspose.cells/cell/get_display_style).
Autrement dit, cette méthode vérifiera et ajustera les bordures supérieure/inférieure/gauche/droite de cette cellule
selon le style ([`Cell.get_style`](/cells/python-net/fr/aspose.cells/cell/get_style)) de ses cellules adjacentes,
mais ne vérifiez pas les cellules fusionnées et ne vérifiez pas le style d'affichage des cellules adjacentes.

##  get_display_style(self, include_merged_borders) {#bool}
Obtient le style d'affichage de cette cellule.


###  Retour

style d'affichage de cette cellule


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| include_merged_borders | bool | Indique si les bordures des cellules fusionnées doivent être vérifiées.|
###  Remarques

Si l'indicateur spécifié est faux, il en va de même pour [`Cell.get_display_style`](/cells/python-net/fr/aspose.cells/cell/get_display_style).
Sinon, c'est la même chose avec l'utilisation
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
pour [`Cell.get_display_style`](/cells/python-net/fr/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Obtient le style d'affichage de cette cellule.


###  Retour

style d'affichage de cette cellule


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/fr/aspose.cells/bordertype) | Indique quelles bordures doivent être vérifiées et ajustées<br/> selon les bordures des cellules adjacentes.|
###  Remarques

Si cette cellule est également affectée par d'autres paramètres tels que la mise en forme conditionnelle, les objets de liste, etc.,
alors le style d'affichage peut être différent de [`Cell.get_style`](/cells/python-net/fr/aspose.cells/cell/get_style).

Pour les drapeaux d'ajustement des bordures en fonction des cellules adjacentes,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
indique si vérifier et combiner les bordures inférieure/supérieure/droite/gauche de
les cellules gauche/droite/haut/bas adjacentes à celle-ci.

Pour des raisons de performances et de compatibilité,
certaines énumérations sont utilisées pour désigner certaines opérations spéciales :

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
indique si la bordure inférieure/droite des cellules fusionnées doit être vérifiée et combinée à celle-ci.

[`BorderType.DIAGONAL`](/cells/python-net/fr/aspose.cells/bordertype#DIAGONAL) (c'est-à-dire [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/fr/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) et
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/fr/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) ont été définis) indique la vérification et la combinaison des bordures
à partir du style d'affichage des cellules adjacentes.

Veuillez noter que vous devez vérifier les bordures/styles des cellules adjacentes, en particulier les styles d'affichage,
est un processus chronophage. S'il n'est pas nécessaire de récupérer les bordures du style renvoyé,
utiliser [`BorderType.NONE`](/cells/python-net/fr/aspose.cells/bordertype#NONE) pour désactiver le processus des cellules adjacentes
donnera de meilleures performances.
Lors de l'obtention des bordures des cellules adjacentes à partir des styles définis sur ces cellules uniquement (sans définition
[`BorderType.DIAGONAL`](/cells/python-net/fr/aspose.cells/bordertype#DIAGONAL)), les performances peuvent également être meilleures car la vérification
le style d'affichage d'une cellule prend également du temps.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
