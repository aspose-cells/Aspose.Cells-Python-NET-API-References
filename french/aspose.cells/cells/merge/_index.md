---
title: méthode merge
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 800
url: /fr/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Fusionne une plage de cellules spécifiée en une seule cellule.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| first_row | int | Première ligne de cette plage (base zéro)|
| first_column | int | Première colonne de cette plage (base zéro)|
| total_rows | int |Nombre de lignes (basé sur un)|
| total_columns | int | Nombre de colonnes (une base)|
###  Remarques

Référencez la cellule fusionnée via l’adresse de la cellule supérieure gauche de la plage.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Fusionne une plage de cellules spécifiée en une seule cellule.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| first_row | int | Première ligne de cette plage (base zéro)|
| first_column | int | Première colonne de cette plage (base zéro)|
| total_rows | int |Nombre de lignes (basé sur un)|
| total_columns | int | Nombre de colonnes (une base)|
| merge_conflict | bool | Fusionner les plages fusionnées en conflit.|
###  Remarques

Référencez la cellule fusionnée via l’adresse de la cellule supérieure gauche de la plage.
Si mergeConflict est vrai et que la plage fusionnée est en conflit avec d'autres cellules fusionnées,
les autres cellules fusionnées seront automatiquement supprimées.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Fusionne une plage de cellules spécifiée en une seule cellule.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| first_row | int | Première ligne de cette plage (base zéro)|
| first_column | int | Première colonne de cette plage (base zéro)|
| total_rows | int |Nombre de lignes (basé sur un)|
| total_columns | int | Nombre de colonnes (une base)|
| check_conflict | bool | Indique si les cellules fusionnées croisent d'autres cellules fusionnées|
| merge_conflict | bool | Fusionner les plages fusionnées en conflit.|
###  Remarques

Référencez la cellule fusionnée via l’adresse de la cellule supérieure gauche de la plage.
Si mergeConflict est vrai et que la plage fusionnée est en conflit avec d'autres cellules fusionnées,
les autres cellules fusionnées seront automatiquement supprimées.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
