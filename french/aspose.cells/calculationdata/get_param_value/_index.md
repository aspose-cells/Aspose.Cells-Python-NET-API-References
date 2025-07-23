---
title: méthode get_param_value
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
Obtient l'objet valeur représenté du paramètre à un index donné.


###  Retour

La valeur calculée du paramètre.


```python

def get_param_value(self, index):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| index | int | L'index du paramètre (basé sur 0)|
###  Remarques

Pour un paramètre :

S'il s'agit d'une valeur simple, renvoie la valeur simple elle-même ;


S'il s'agit d'une référence, renvoie l'objet ReferredArea ;


S'il fait référence à un ou plusieurs ensembles de données avec plusieurs valeurs, il renvoie un tableau d'objets ;



S'il s'agit d'une sorte d'expression qui doit être calculée, elle sera calculée en mode valeur
et généralement, une seule valeur sera renvoyée selon la base de cellules actuelle. Par exemple,
si l'un des paramètres de la formule de D2 est A:A+B:B, alors A2+B2 sera calculé et renvoyé.
Cependant, si ce paramètre a été spécifié en mode tableau
(par [`Workbook.update_custom_function_definition`](/cells/python-net/fr/aspose.cells/workbook/update_custom_function_definition)
ou [`FormulaParseOptions.custom_function_definition`](/cells/python-net/fr/aspose.cells/formulaparseoptions#custom_function_definition)),
alors un tableau(object[][]) sera renvoyé dont les éléments sont A1+B1,A2+B2,....


###  Voir également
* module [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/fr/aspose.cells/calculationdata)
