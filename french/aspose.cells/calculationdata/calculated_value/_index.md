---
title: calculated_value propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value propriété

Obtient ou définit la valeur calculée pour cette fonction.

###  Remarques

L'utilisateur doit définir cette propriété dans son moteur de calcul personnalisé pour les fonctions prises en charge par le moteur,
et la valeur définie sera renvoyée lors de l'obtention ultérieure de cette propriété.
La valeur définie peut être des types possibles de [`Cell.value`](/cells/python-net/fr/aspose.cells/cell#value),
ou un tableau de ce type de valeurs, ou une plage, un nom, une zone référencée.
Obtenir cette propriété avant de lui attribuer une valeur fera calculer la fonction
par le moteur de calcul par défaut de Aspose.Cells, puis la valeur calculée sera
être renvoyé (généralement, il devrait s'agir de #NAME? pour les fonctions définies par l'utilisateur).
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
* module [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/fr/aspose.cells/calculationdata)
