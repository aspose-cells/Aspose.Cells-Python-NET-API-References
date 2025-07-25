---
title: méthode set_array_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 320
url: /fr/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
Définit une formule de tableau (formule de tableau héritée saisie via CTRL+MAJ+ENTRÉE dans MS Excel) sur une plage de cellules.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes à renseigner avec le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes à renseigner pour le résultat de la formule matricielle.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
Définit une formule matricielle sur une plage de cellules.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes à renseigner avec le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes à renseigner pour le résultat de la formule matricielle.|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | Options d'analyse de la formule.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Définit une formule matricielle sur une plage de cellules.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes à renseigner avec le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes à renseigner pour le résultat de la formule matricielle.|
| is_r1c1 | bool | si la formule est la formule R1C1|
| is_local | bool | si la formule est formatée en fonction des paramètres régionaux|
###  Remarques

REMARQUE : Cette classe est désormais obsolète. À la place,
veuillez utiliser Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Cette propriété sera supprimée 12 mois plus tard soit en décembre 2019.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Définit une formule matricielle sur une plage de cellules.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| array_formula | str | Formule matricielle.|
| row_number | int | Nombre de lignes à renseigner avec le résultat de la formule matricielle.|
| column_number | int | Nombre de colonnes à renseigner pour le résultat de la formule matricielle.|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | Options d'analyse de la formule.|
| values | list | valeurs pour les cellules avec la formule matricielle donnée|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
