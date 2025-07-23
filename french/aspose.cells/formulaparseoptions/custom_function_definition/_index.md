---
title: custom_function_definition propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/formulaparseoptions/custom_function_definition/
is_root: false
---
##  custom_function_definition propriété

Définition pour l'analyse des fonctions personnalisées.

###  Remarques

Pour certaines exigences particulières, comme lors du calcul d'une fonction personnalisée dans le moteur personnalisé de l'utilisateur,
certains paramètres doivent être calculés en mode tableau, l'utilisation de cette propriété peut marquer ces paramètres
en mode tableau lors de l'analyse de la formule. Sinon, l'utilisateur devra mettre à jour ces fonctions personnalisées ultérieurement en
[`Workbook.update_custom_function_definition`](/cells/python-net/fr/aspose.cells/workbook/update_custom_function_definition) pour obtenir le même résultat.
###  Définition:
```python
@property
def custom_function_definition(self):
    ...
@custom_function_definition.setter
def custom_function_definition(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`CustomFunctionDefinition`](/cells/python-net/fr/aspose.cells/customfunctiondefinition)
* classe [`FormulaParseOptions`](/cells/python-net/fr/aspose.cells/formulaparseoptions)
