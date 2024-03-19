---
title: calc_stack_size propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size propriété

La taille de la pile pour calculer les cellules de manière récursive. La valeur par défaut est 200.

###  Remarques

Lorsqu'un grand nombre de cellules doivent être calculées de manière récursive dans l'arborescence des dépendances,
StackOverflowException peut être provoqué dans le processus de calcul.
Si tel est le cas, l'utilisateur doit spécifier une valeur plus petite pour cette propriété.
Dans une telle situation, l'utilisateur doit déterminer la valeur appropriée pour cette propriété en fonction des formules et des données réelles.
Cependant, une valeur trop petite peut entraîner une dégradation des performances du calcul de la formule et une valeur inférieure à 2.
il sera impossible de calculer une formule qui dépend d'une autre. Donc si la valeur spécifiée est inférieure à 2,
il sera réinitialisé à 2.
###  Définition:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`CalculationOptions`](/cells/python-net/fr/aspose.cells/calculationoptions)
