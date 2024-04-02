---
title: calculated_value propriété
second_title: Aspose.Cells.GridJs for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cellsgridjs/gridcalculationdata/calculated_value/
is_root: false
---
##  calculated_value propriété


Obtient/définit la valeur calculée pour cette fonction.

###  Remarques


L'utilisateur doit définir cette propriété dans son moteur de calcul personnalisé pour les fonctions prises en charge par le moteur,
et la valeur définie sera renvoyée lors de l'obtention de cette propriété.
L'obtention de cette propriété avant le réglage fera que la fonction sera calculée par le moteur de calcul par défaut de Aspose.Cells et la valeur calculée sera renvoyée.
###  Définition:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Voir également
* module [`aspose.cellsgridjs`](../../)
* classe [`GridCalculationData`](/cells/python-net/fr/aspose.cellsgridjs/gridcalculationdata)
