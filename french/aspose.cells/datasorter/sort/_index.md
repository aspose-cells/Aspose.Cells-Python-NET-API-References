---
title: méthode sort
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cells/datasorter/sort/
is_root: false
---
##  sort(self) {#}
Trier les données dans la plage.


###  Retour

les indices d'origine (position absolue, par exemple, la colonne A est 0, B est 1, ...) des lignes/colonnes triées.
Si aucune ligne/colonne ne doit être déplacée par cette opération de tri, null sera renvoyé.


```python

def sort(self):
    ...
```




##  sort(self, cells, area) {#aspose.cells.Cells-aspose.cells.CellArea}
Trier les données de la zone.


###  Retour

les indices d'origine (position absolue, par exemple, la colonne A est 0, B est 1, ...) des lignes/colonnes triées.
Si aucune ligne/colonne ne doit être déplacée par cette opération de tri, null sera renvoyé.


```python

def sort(self, cells, area):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/fr/aspose.cells/cells) | Les cellules contiennent la zone de données.|
| area | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La zone nécessaire pour trier|


##  sort(self, cells, start_row, start_column, end_row, end_column) {#aspose.cells.Cells-int-int-int-int}
Trie les données de la zone.


###  Retour

les indices d'origine (position absolue, par exemple, la colonne A est 0, B est 1, ...) des lignes/colonnes triées.
Si aucune ligne/colonne ne doit être déplacée par cette opération de tri, null sera renvoyé.


```python

def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/fr/aspose.cells/cells) | Les cellules contiennent la zone de données.|
| start_row | int | La ligne de départ de la zone.|
| start_column | int | La colonne de départ de la zone.|
| end_row | int | La dernière rangée de la zone.|
| end_column | int | La colonne de fin de la zone.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`DataSorter`](/cells/python-net/fr/aspose.cells/datasorter)
