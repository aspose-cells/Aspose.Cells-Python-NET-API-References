---
title: is_param_array_mode_required propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required propriété

Indique si ce moteur a besoin que le paramètre soit calculé en mode tableau. La valeur par défaut est fausse.
Si [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/fr/aspose.cells/calculationdata/get_param_value_in_array_mode) est requis lors du calcul des douanes
fonctions et l'utilisateur n'a pas mis à jour la définition pour elles
(par [`Workbook.update_custom_function_definition`](/cells/python-net/fr/aspose.cells/workbook/update_custom_function_definition)),
cette propriété doit être définie comme vraie.

###  Remarques

Si ce moteur de calcul personnalisé nécessite que le paramètre soit calculé en mode tableau,
plus de piles seront nécessaires pour mettre en cache l'arborescence des paramètres
et la méthode Calculate() peut être appelée de manière récursive pour calculer la valeur du paramètre.
Pour des raisons de performances, veuillez conserver cette propriété comme valeur par défaut (faux)
s'il n'y a pas d'exigence particulière.
###  Définition:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`AbstractCalculationEngine`](/cells/python-net/fr/aspose.cells/abstractcalculationengine)
