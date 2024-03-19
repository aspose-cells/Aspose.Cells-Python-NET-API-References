---
title: méthode preprocess_exported_value
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
Prétraitez la valeur de la cellule actuelle à exporter.


###  Retour

Si la cellule actuelle a été remplacée par un type et/ou une valeur différente.


```python
def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_row | int | l'index de ligne de la cellule actuelle|
| cell_column | int | l'index de colonne de la cellule|
| value | [`CellValue`](/cells/python-net/fr/aspose.cells/cellvalue) | valeur et type de cellule actuelle|
###  Remarques

L'index de ligne et de colonne est l'index absolu de la cellule dans la feuille de calcul, et non l'index dans la table exportée.
L'utilisateur peut vérifier la valeur de la cellule actuelle dans l'implémentation de remplacement de cette méthode,
si la cellule actuelle doit être remplacée par un autre type et une autre valeur,
ici, l'implémentation doit définir le type et la valeur attendus sur l'objet CellValue et renvoyer true.
Par défaut, cette méthode ne fait rien et renvoie false.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`ExportTableOptions`](/cells/python-net/fr/aspose.cells/exporttableoptions)
