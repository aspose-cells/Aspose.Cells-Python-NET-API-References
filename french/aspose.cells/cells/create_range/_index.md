---
title: méthode create_range
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 190
url: /fr/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une adresse de la plage.


###  Retour

Un objet [`Range`](/cells/python-net/fr/aspose.cells/range)


```python

def create_range(self, address):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| address | str | L'adresse de la plage.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une plage de cellules.


###  Retour

Un objet [`Range`](/cells/python-net/fr/aspose.cells/range)


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_cell | str | Nom de la cellule en haut à gauche.|
| lower_right_cell | str | Nom de la cellule en bas à droite.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir de lignes de cellules ou de colonnes de cellules.


###  Retour

Un objet [`Range`](/cells/python-net/fr/aspose.cells/range).


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| first_index | int | Index de première ligne ou index de première colonne, basé sur zéro.|
| number | int | Nombre total de lignes ou de colonnes, basé sur un.|
| is_vertical | bool | Vrai - Plage créée à partir de colonnes de cellules. Faux - Plage créée à partir de lignes de cellules.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une plage de cellules.


###  Retour

Un objet [`Range`](/cells/python-net/fr/aspose.cells/range)


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| first_row | int |Première rangée de cette gamme|
| first_column | int | Première colonne de cette gamme|
| total_rows | int | Nombre de lignes|
| total_columns | int | Nombre de colonnes|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
