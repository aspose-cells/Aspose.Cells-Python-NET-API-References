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

Spécifie la taille de la pile pour le calcul récursif des cellules.

###  Remarques

Lorsqu'il y a une grande quantité de cellules à calculer de manière récursive dans l'arbre de dépendance,
StackOverflowException peut être provoqué dans le processus de calcul.
Si c'est le cas, l'utilisateur doit spécifier une valeur plus petite pour cette propriété.
Dans une telle situation, l'utilisateur doit déterminer la valeur appropriée pour cette propriété en fonction des formules et des données réelles.
Une valeur trop petite peut entraîner une dégradation des performances pour le calcul de la formule.
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
* module [aspose.cells](../../)
* classe [CalculationOptions](/cells/python-net/fr/aspose.cells/calculationoptions)
