---
title: force_full_calculation propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/formulasettings/force_full_calculation/
is_root: false
---
##  force_full_calculation propriété

Indique si toutes les formules sont calculées à chaque fois qu'un calcul est déclenché.

###  Remarques

Cette propriété sert uniquement à enregistrer les paramètres dans le fichier de feuille de calcul résultant
afin que d'autres applications (telles que MS Excel) puissent agir en conséquence lors du chargement et de la manipulation du fichier résultant.
Pour des raisons de performances pour la plupart des applications des utilisateurs, nous ne calculons automatiquement aucune formule dans le classeur,
quelle que soit la valeur définie pour cette propriété.
###  Définition:
```python
@property
def force_full_calculation(self):
    ...
@force_full_calculation.setter
def force_full_calculation(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`FormulaSettings`](/cells/python-net/fr/aspose.cells/formulasettings)
