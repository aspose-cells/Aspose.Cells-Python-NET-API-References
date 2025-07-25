---
title: sheet_name propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells/referredarea/sheet_name/
is_root: false
---
##  sheet_name propriété

Indique dans quelle feuille se trouve cette référence.

###  Remarques

S'il fait référence à plusieurs feuilles de calcul,
la valeur renvoyée est exactement comme l'expression de plage dans la formule.
Par exemple « Feuille1 : Feuille3 » pour la référence dans la formule « =SOMME(Feuille1 : Feuille3 ! $A$1 : $B$2) ».
###  Définition:
```python
@property
def sheet_name(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`ReferredArea`](/cells/python-net/fr/aspose.cells/referredarea)
