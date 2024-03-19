---
title: méthode on_circular
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
Mettez en œuvre cette méthode pour faire des affaires lors du calcul de formules avec des références circulaires.


###  Retour

Indique si le moteur de formule doit calculer ces cellules de manière circulaire après cet appel.
True pour laisser le moteur de formule continuer à effectuer des calculs à leur place.
False pour permettre au moteur de formule de simplement marquer ces cellules comme calculées.


```python
def on_circular(self, circular_cells_data):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator avec [`CalculationCell`](/cells/python-net/fr/aspose.cells/calculationcell) éléments représentant les cellules qui<br/> dépendent de références circulaires.|
###  Remarques

Dans l'implémentation, l'utilisateur peut également définir la valeur attendue comme résultat calculé
pour une partie/la totalité de ces cellules afin que le moteur de formule ne les calcule pas de manière récursive.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`AbstractCalculationMonitor`](/cells/python-net/fr/aspose.cells/abstractcalculationmonitor)
* classe [`CalculationCell`](/cells/python-net/fr/aspose.cells/calculationcell)
