---
title: inner_x propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 250
url: /fr/aspose.cells.charts/plotarea/inner_x/
is_root: false
---
##  inner_x propriété

Obtient ou obtient la coordonnée x du coin supérieur de la zone de tracé en unités de 1/4000 de la zone du graphique.

###  Remarques

Le cadre de délimitation de la zone de tracé comprend la zone de tracé, les coches (étiquettes de coche) et une petite bordure autour des coches.
 Si la valeur n'est pas créée par MS Excel, veuillez appeler la méthode Chart.Calculate() avant d'appeler cette méthode.


 Le**X** , **Y** , **Largeur** et**Hauteur** de**Superficie de la parcelle** représente la superficie de la parcelle
 cadre de délimitation qui comprend la zone de tracé, les graduations (étiquettes de graduation) et une petite bordure autour des graduations.
 Si vous souhaitez obtenir la taille réelle de la superficie du terrain, vous devez appeler**InnerXRatioToChart** , **InnerYRatioToChart** , **Rapport de largeur intérieure par rapport au graphique** et
**Rapport hauteur intérieure/graphique** propriétés.


Pour Excel 2007 ou version ultérieure, la valeur par défaut est zéro. Vous devez appeler pour obtenir la valeur après avoir appelé Chart.Calculate().
###  Définition:
```python
@property
def inner_x(self):
    ...
@inner_x.setter
def inner_x(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.charts`](../../)
* classe [`PlotArea`](/cells/python-net/fr/aspose.cells.charts/plotarea)
