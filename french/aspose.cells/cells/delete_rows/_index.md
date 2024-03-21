---
title: méthode delete_rows
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 260
url: /fr/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows {#int-int}
Supprime plusieurs lignes.



```python
def delete_rows(self, row_index, total_rows):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row_index | int | Index de la première ligne à supprimer.|
| total_rows | int | Nombre de lignes à supprimer.|
###  Remarques

Si la plage supprimée contient la partie supérieure(pas la totalité) du tableau(ListObject),
la distance n'a pas pu être supprimée et rien ne sera fait.
Cela fonctionne de la même manière avec MS Excel.

##  delete_rows {#int-int-bool}
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
| update_reference | bool | Indique si les références à jour dans d’autres feuilles de calcul sont mises à jour.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
