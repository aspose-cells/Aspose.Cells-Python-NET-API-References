---
title: méthode add_add_in_function
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/cellshelper/add_add_in_function/
is_root: false
---
##  add_add_in_function(, fonction, nombre_min_de_paramètres, nombre_max_de_paramètres, type_paramètres, type_valeur_fonction){#str-int-int-list-aspose.cells.ParameterType}
Ajouter une fonction addin.



```python

@staticmethod
def add_add_in_function(function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| function | str | Le nom de la fonction.|
| min_count_of_parameters | int | Nombre minimum de paramètres requis par cette fonction|
| max_count_of_parameters | int | Nombre maximal de paramètres autorisés par cette fonction.|
| paramers_type | list | Le type de paramètres exceptés de la fonction|
| function_value_type | [`ParameterType`](/cells/python-net/fr/aspose.cells/parametertype) | Le type de valeur de fonction.|
###  Remarques

REMARQUE : Ce membre est désormais obsolète. À la place,
veuillez utiliser les méthodes WorksheetCollection.RegisterAddInFunction().
 Cette méthode sera supprimée 12 mois plus tard, soit en janvier 2022.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`CellsHelper`](/cells/python-net/fr/aspose.cells/cellshelper)
