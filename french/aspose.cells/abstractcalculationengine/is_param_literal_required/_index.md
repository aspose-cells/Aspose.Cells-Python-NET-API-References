---
title: is_param_literal_required propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required propriété

Indique si ce moteur a besoin du texte littéral du paramètre lors du calcul. La valeur par défaut est fausse.

###  Remarques

Si ce moteur de calcul personnalisé a besoin du texte littéral du paramètre,
plus de piles seront nécessaires pour mettre en cache le texte littéral des paramètres
et la méthode Calculate() peut être appelée de manière récursive pour calculer la valeur du paramètre.
Généralement, le texte littéral n'est pas nécessaire pour calculer les formules
et cette propriété doit rester fausse pour la plupart des implémentations afin d'obtenir de meilleures performances.
###  Définition:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`AbstractCalculationEngine`](/cells/python-net/fr/aspose.cells/abstractcalculationengine)
