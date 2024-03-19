---
title: méthode set_array_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 310
url: /fr/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Définit une formule matricielle (ancienne formule matricielle saisie via CTRL+SHIFT+ENTER dans ms Excel) sur une plage de cellules.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes pour remplir le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes pour renseigner le résultat de la formule matricielle.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Définit une formule matricielle sur une plage de cellules.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes pour remplir le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes pour renseigner le résultat de la formule matricielle.|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | Options d'analyse de la formule.|


##  set_array_formula {#str-int-int-bool-bool}
Définit une formule matricielle sur une plage de cellules.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes pour remplir le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes pour renseigner le résultat de la formule matricielle.|
| is_r1c1 | bool | si la formule est la formule R1C1|
| is_local | bool | si la formule est formatée en paramètres régionaux|
###  Remarques

REMARQUE : Cette classe est désormais obsolète. Plutôt,
veuillez utiliser Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Ce bien sera supprimé 12 mois plus tard depuis décembre 2019.
Le Aspose s'excuse pour tout inconvénient que vous pourriez avoir rencontré.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Définit une formule matricielle sur une plage de cellules.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes pour remplir le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes pour renseigner le résultat de la formule matricielle.|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | Options d'analyse de la formule.|
| values | list | valeurs pour les cellules avec une formule matricielle donnée|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
