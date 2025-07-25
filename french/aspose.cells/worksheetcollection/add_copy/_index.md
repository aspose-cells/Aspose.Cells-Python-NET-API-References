---
title: méthode add_copy
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy(self, sheet_name) {#str}
Ajoute une feuille de calcul à la collection et copie les données d'une feuille de calcul existante.


###  Retour

[`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet) index d'objet.


```python

def add_copy(self, sheet_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| sheet_name | str | Nom de la feuille de calcul source.|
###  Exceptions
| Exception| Description|
| :- | :- |
| [`CellsException`](/cells/python-net/fr/aspose.cells/cellsexception) | Spécifie un nom de feuille de calcul non valide.|




##  add_copy(self, sheet_index) {#int}
Ajoute une feuille de calcul à la collection et copie les données d'une feuille de calcul existante.


###  Retour

[`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet) index d'objet.


```python

def add_copy(self, sheet_index):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| sheet_index | int | Index de la feuille de travail source.|


##  add_copy(self, source, dest_sheet_names) {#list-list}
Copiez un groupe de feuilles de travail.



```python

def add_copy(self, source, dest_sheet_names):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source | list | Les feuilles de travail sources.|
| dest_sheet_names | list | Les noms des feuilles copiées.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`CellsException`](/cells/python-net/fr/aspose.cells/cellsexception)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
* classe [`WorksheetCollection`](/cells/python-net/fr/aspose.cells/worksheetcollection)
