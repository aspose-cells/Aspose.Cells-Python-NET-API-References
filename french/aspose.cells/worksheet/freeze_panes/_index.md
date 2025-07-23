---
title: méthode freeze_panes
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 140
url: /fr/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Gèle les volets dans la cellule spécifiée dans la feuille de calcul.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_name | str | Cell nom.|
| freezed_rows | int | Nombre de lignes visibles dans le volet supérieur, pas plus que l'index de ligne.|
| freezed_columns | int | Nombre de colonnes visibles dans le volet de gauche, pas plus que l'index de colonne.|
###  Remarques

Les index de ligne et de colonne ne peuvent pas tous être nuls. Nombre de lignes et de colonnes
tout ne peut pas non plus être nul.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Gèle les volets dans la cellule spécifiée dans la feuille de calcul.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row | int | Index de ligne.|
| column | int | Index des colonnes.|
| freezed_rows | int | Nombre de lignes visibles dans le volet supérieur, pas plus que l'index de ligne.|
| freezed_columns | int | Nombre de colonnes visibles dans le volet de gauche, pas plus que l'index de colonne.|
###  Remarques

Les index de ligne et de colonne ne peuvent pas tous être nuls. Nombre de lignes et de colonnes
tout ne peut pas non plus être nul.


Les deux premiers paramètres spécifient la position figée et les deux derniers paramètres spécifient la zone figée dans le volet supérieur gauche.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
