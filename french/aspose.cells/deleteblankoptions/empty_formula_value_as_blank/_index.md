---
title: empty_formula_value_as_blank propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank propriété

Si une cellule sera considérée comme vide lorsqu'il s'agit d'une formule et que le résultat calculé est nul ou une chaîne vide.
La valeur par défaut est faux.

###  Remarques

En règle générale, l'utilisateur doit s'assurer que les formules ont été calculées avant de supprimer l'opération avec cette propriété comme vraie.
Sinon, toutes les formules nouvellement créées par des API normales telles que [`Cell.formula`](/cells/python-net/fr/aspose.cells/cell#formula) seront considérées comme vides et pourront être supprimées.
car avant le calcul, leurs résultats calculés sont tous nuls.
###  Définition:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`DeleteBlankOptions`](/cells/python-net/fr/aspose.cells/deleteblankoptions)
