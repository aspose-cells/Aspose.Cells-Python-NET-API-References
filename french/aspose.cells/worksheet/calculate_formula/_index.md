---
title: calculate_formula méthode
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(formula) {#str}
Calcule une formule.


###  Retour

Résultat de la formule calculée.


```python
def calculate_formula(self, formula):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|


##  calculate_formula(formula, opts) {#str-CalculationOptions}
Calcule une formule.


###  Retour

Résultat de la formule calculée.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|
| opts | [CalculationOptions](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de formule de calcul|


##  calculate_formula(options, recursive) {#CalculationOptions-bool}
Calcule toutes les formules de cette feuille de calcul.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul|
| recursive | bool | True signifie que si les cellules de la feuille de calcul dépendent des cellules d'autres feuilles de calcul,<br/>les cellules dépendantes dans d'autres feuilles de calcul seront également calculées.<br/> False signifie que toutes les formules de la feuille de calcul ont été calculées et que les valeurs sont correctes.|


##  calculate_formula(recursive, ignore_error, custom_function) {#bool-bool-ICustomFunction}
Calcule toutes les formules de cette feuille de calcul.



```python
def calculate_formula(self, recursive, ignore_error, custom_function):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| recursive | bool | True signifie que si les cellules de la feuille de calcul dépendent des cellules d'autres feuilles de calcul,<br/>les cellules dépendantes dans d'autres feuilles de calcul seront également calculées.<br/> False signifie que toutes les formules de la feuille de calcul ont été calculées et que les valeurs sont correctes.|
| ignore_error | bool | Indique si masquer l'erreur dans le calcul des formules.<br/> L'erreur peut être une fonction non prise en charge, des liens externes, etc.|
| custom_function | [ICustomFunction](/cells/python-net/fr/aspose.cells/icustomfunction) | Les fonctions de calcul de formule personnalisée pour étendre le moteur de calcul.|
###  Remarques

REMARQUE : ce membre est désormais obsolète. Plutôt,
veuillez utiliser la méthode CalculateFormula(CalculationOptions, bool).
 Cette méthode sera supprimée 12 mois plus tard depuis août 2020.
Aspose s'excuse pour tout inconvénient que vous pourriez avoir rencontré.


###  Voir également
* module [aspose.cells](../../)
* classe [Worksheet](/cells/python-net/fr/aspose.cells/worksheet)
