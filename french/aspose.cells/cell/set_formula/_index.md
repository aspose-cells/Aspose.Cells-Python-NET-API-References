---
title: méthode set_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 340
url: /fr/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Définissez la formule et la valeur (résultat calculé) de la formule.



```python
def set_formula(self, formula, value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | La formule.|
| value | any |La valeur (résultat calculé) de la formule.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Définissez la formule et la valeur (résultat calculé) de la formule.



```python
def set_formula(self, formula, options, value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | La formule.|
| options | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | Options d'analyse de la formule.|
| value | any |La valeur (résultat calculé) de la formule.|


##  set_formula {#str-bool-bool-any}
Définissez la formule et la valeur de la formule.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | La formule.|
| is_r1c1 | bool | Si la formule est la formule R1C1.|
| is_local | bool | Indique si la formule est au format local.|
| value | any | La valeur de la formule.|
###  Remarques

REMARQUE : Cette classe est désormais obsolète. Plutôt,
veuillez utiliser Cell.SetFormula(string,FormulaParseOptions,object).
Ce bien sera supprimé 12 mois plus tard depuis décembre 2019.
Le Aspose s'excuse pour tout inconvénient que vous pourriez avoir rencontré.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
