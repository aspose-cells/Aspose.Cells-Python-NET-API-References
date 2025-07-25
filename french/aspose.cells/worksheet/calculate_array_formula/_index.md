---
title: méthode calculate_array_formula
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Calcule une formule sous forme de formule matricielle.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|
| opts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul de la formule|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Calcule une formule sous forme de formule matricielle.


###  Retour

Résultat de la formule calculée.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|
| opts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul de la formule|
| max_row_count | int | le nombre maximal de lignes de données résultantes.<br/> Si le nombre de lignes n'est pas positif ou est supérieur au nombre réel de lignes, le nombre réel de lignes sera utilisé.|
| max_column_count | int | le nombre maximal de colonnes de données résultantes.<br/> Si le nombre n'est pas positif ou supérieur au nombre réel de lignes, le nombre réel de colonnes sera utilisé.|
###  Remarques

La formule sera considérée comme une formule de tableau dynamique pour calculer la dimension et le résultat.
La dimension maximale spécifiée par l'utilisateur est utilisée dans les cas où le résultat calculé est un grand ensemble de données
(par exemple, le résultat calculé peut correspondre à une ligne ou à une colonne entière de données)
mais l'utilisateur n'a pas besoin d'un tableau aussi grand en fonction des besoins de l'entreprise ou pour des raisons de performances.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Calcule une formule sous forme de formule matricielle.


###  Retour

Résultat de la formule calculée.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | Formule à calculer.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions) |Options d'analyse de formule|
| c_opts | [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions) | Options de calcul de la formule|
| base_cell_row | int | L'index de ligne de la cellule de base.|
| base_cell_column | int | L'index de colonne de la cellule de base.|
| max_row_count | int | Le nombre maximal de lignes de données résultantes.<br/> Si le nombre de lignes n'est pas positif ou est supérieur au nombre réel de lignes, le nombre réel de lignes sera utilisé.|
| max_column_count | int | Le nombre maximal de colonnes de données résultantes.<br/> Si le nombre n'est pas positif ou supérieur au nombre réel de lignes, le nombre réel de colonnes sera utilisé.|
| calculation_data | [`CalculationData`](/cells/python-net/fr/aspose.cells/calculationdata) | Les données de calcul. Elles sont utilisées pour la situation.<br/>cet utilisateur doit calculer certaines formules statiques lors de la mise en œuvre d'un moteur de calcul personnalisé.<br/>Pour ce type de situation, l'utilisateur doit le spécifier avec les données de calcul fournies<br/> pour Aspose.Cells.AbstractCalculationEngine.Calculer.|
###  Remarques

La formule sera considérée comme une formule de tableau dynamique pour calculer la dimension et le résultat.
La dimension maximale spécifiée par l'utilisateur est utilisée dans les cas où le résultat calculé est un grand ensemble de données
(par exemple, le résultat calculé peut correspondre à une ligne ou à une colonne entière de données)
mais l'utilisateur n'a pas besoin d'un tableau aussi grand en fonction des besoins de l'entreprise ou pour des raisons de performances.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
