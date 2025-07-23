---
title: y_ratio_to_chart propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 660
url: /fr/aspose.cells.charts/datalabels/y_ratio_to_chart/
is_root: false
---
##  y_ratio_to_chart propriété

Obtient ou définit la coordonnée y du coin supérieur gauche en unités de rapport de la zone du graphique.

###  Remarques

Il s'agit d'une valeur fractionnaire, sa plage valide est comprise entre 0 et 1.
 Comment convertir des unités de rapport en pixels ?
YPixel = YRatioToChart * Chart.ChartObject.Height;
###  Définition:
```python
@property
def y_ratio_to_chart(self):
    ...
@y_ratio_to_chart.setter
def y_ratio_to_chart(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.charts`](../../)
* classe [`DataLabels`](/cells/python-net/fr/aspose.cells.charts/datalabels)
