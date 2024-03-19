---
title: méthode get_array_mode_parameters
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
Obtient les indices des paramètres d'une fonction personnalisée donnée qui doivent être calculés en mode tableau.


###  Retour

Indices des paramètres qui doivent être calculés en mode tableau pour une fonction personnalisée donnée.
La valeur par défaut est null, aucun paramètre ne doit être calculé en mode tableau pour la fonction personnalisée.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| function_name | str | Nom de la fonction personnalisée.|
###  Remarques

Pour une expression qui doit être calculée, en prenant A:A+B:B comme exemple :
Généralement, en mode valeur, il sera calculé sur une valeur unique en fonction de la base de cellules actuelle.
Mais en mode tableau, toutes les valeurs de A1+B1,A2+B2,A3+B3,... seront calculées et utilisées pour le calcul.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`CustomFunctionDefinition`](/cells/python-net/fr/aspose.cells/customfunctiondefinition)
