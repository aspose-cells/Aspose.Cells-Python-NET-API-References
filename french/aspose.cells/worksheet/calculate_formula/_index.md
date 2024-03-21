---
title: méthode calculate_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
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


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Calcule directement une expression de formule.


###  Retour

Résultat calculé de la formule donnée.
L’objet renvoyé peut être des types possibles [`Cell.value`](/cells/python-net/fr/aspose.cells/cell#value) ou ReferredArea.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|
| opts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul de la formule|
###  Remarques

La formule sera calculée exactement comme elle a été définie dans la cellule A1.
Et la formule sera considérée comme une formule normale.
Si vous avez besoin que la formule soit calculée sous forme de formule matricielle et que vous obteniez un tableau pour le résultat calculé,
veuillez plutôt utiliser le [`Worksheet.calculate_array_formula`](/cells/python-net/fr/aspose.cells/worksheet/calculate_array_formula).

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Calcule toutes les formules de cette feuille de calcul.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul|
| recursive | bool | True signifie que si les cellules de la feuille de calcul dépendent des cellules d'autres feuilles de calcul,<br/>les cellules dépendantes des autres feuilles de calcul seront également calculées.<br/> False signifie que toutes les formules de la feuille de calcul ont été calculées et que les valeurs sont correctes.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Calcule directement une expression de formule.


###  Retour

Résultat calculé de la formule donnée.
L’objet renvoyé peut être des types possibles [`Cell.value`](/cells/python-net/fr/aspose.cells/cell#value) ou ReferredArea.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) | Options d'analyse de la formule.|
| c_opts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul de la formule.|
| base_cell_row | int | L'index de ligne de la cellule de base.|
| base_cell_column | int | L'index de colonne de la cellule de base.|
| calculation_data | [`CalculationData`](/cells/python-net/fr/aspose.cells/calculationdata) | Les données de calcul. Il est utilisé pour la situation<br/>cet utilisateur doit calculer certaines formules statiques lors de la mise en œuvre d'un moteur de calcul personnalisé.<br/>Pour ce type de situation, l'utilisateur doit le spécifier avec les données de calcul fournies<br/> pour [`AbstractCalculationEngine.calculate`](/cells/python-net/fr/aspose.cells/abstractcalculationengine/calculate).|
###  Remarques

La formule sera calculée comme si elle avait été définie sur la cellule de base spécifiée.
Et la formule sera considérée comme une formule normale. Si vous avez besoin que la formule soit calculée sous forme de formule matricielle
et pour obtenir un tableau pour le résultat calculé, veuillez utiliser
[`Worksheet.calculate_array_formula`](/cells/python-net/fr/aspose.cells/worksheet/calculate_array_formula) à la place.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
