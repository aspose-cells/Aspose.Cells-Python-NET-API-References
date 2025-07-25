---
title: méthode delete_rows
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 260
url: /fr/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Supprime plusieurs lignes.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row_index | int | Le premier index de ligne à supprimer.|
| total_rows | int | Nombre de lignes à supprimer.|
###  Remarques

Si la plage supprimée contient la partie supérieure (et non la totalité) du tableau (ListObject),
la portée n'a pas pu être supprimée et rien ne sera fait.
Cela fonctionne de la même manière avec MS Excel.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
Supprime plusieurs lignes dans la feuille de calcul.


###  Retour




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row_index | int | Index de la première ligne à supprimer.|
| total_rows | int | Nombre de lignes à supprimer.|
| update_reference | bool | Indique si les références de mise à jour sont dans d'autres feuilles de calcul.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Supprime plusieurs lignes dans la feuille de calcul.


###  Retour




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row_index | int | Index de la première ligne à supprimer.|
| total_rows | int | Nombre de lignes à supprimer.|
| options | [`DeleteOptions`](/cells/python-net/fr/aspose.cells/deleteoptions) | Options pour l'opération de suppression|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
