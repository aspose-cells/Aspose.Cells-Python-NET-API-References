---
title: calculate_on_open propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/formulasettings/calculate_on_open/
is_root: false
---
##  calculate_on_open propriété

Indique si l'application doit effectuer un calcul complet lorsque le classeur est ouvert.

###  Remarques

Cette propriété sert uniquement à enregistrer les paramètres dans le fichier de feuille de calcul résultant
afin que d'autres applications (telles que MS Excel) puissent agir en conséquence lors du chargement du fichier résultant.
Pour des raisons de performances pour la plupart des applications des utilisateurs, nous ne calculons automatiquement aucune formule dans le classeur,
quelle que soit la valeur définie pour cette propriété.
###  Définition:
```python
@property
def calculate_on_open(self):
    ...
@calculate_on_open.setter
def calculate_on_open(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`FormulaSettings`](/cells/python-net/fr/aspose.cells/formulasettings)
