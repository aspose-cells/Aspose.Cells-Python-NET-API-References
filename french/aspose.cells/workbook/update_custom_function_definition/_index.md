---
title: méthode update_custom_function_definition
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 430
url: /fr/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition(self, definition) {#aspose.cells.CustomFunctionDefinition}
Met à jour la définition des fonctions personnalisées.



```python

def update_custom_function_definition(self, definition):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/fr/aspose.cells/customfunctiondefinition) | Définition spéciale de fonctions personnalisées pour les besoins particuliers de l'utilisateur.|
###  Remarques

Cette méthode peut être utilisée dans des cas particuliers. Par exemple, si l'utilisateur a besoin de certains paramètres.
de certaines fonctions personnalisées peuvent être calculées en mode tableau, l'utilisateur peut alors fournir sa propre définition avec implémenté
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/fr/aspose.cells/customfunctiondefinition/get_array_mode_parameters) pour ces fonctions.
Une fois les données des formules mises à jour, les paramètres spécifiés seront calculés automatiquement en mode tableau.
lors du calcul des fonctions personnalisées correspondantes.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
