---
title: height_ratio_to_chart propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 200
url: /fr/aspose.cells.charts/plotarea/height_ratio_to_chart/
is_root: false
---
##  height_ratio_to_chart propriété

Obtient ou définit la hauteur du cadre de délimitation de la zone de tracé en unités de rapport de la zone du graphique.

###  Remarques

Le cadre de délimitation de la zone de tracé comprend la zone de tracé, les coches (étiquettes de coche) et une petite bordure autour des coches.
 Si la valeur n'est pas créée par MS Excel, veuillez appeler la méthode Chart.Calculate() avant d'appeler cette méthode.


 Le**XRatioToChart** , **YRatioToChart** , **Rapport de largeur par rapport au graphique** et**Rapport hauteur/graphique** de**Superficie de la parcelle** représente la superficie de la parcelle
 cadre de délimitation qui comprend la zone de tracé, les graduations (étiquettes de graduation) et une petite bordure autour des graduations.
 Si vous souhaitez obtenir la taille réelle de la superficie du terrain, vous devez appeler**InnerXRatioToChart** , **InnerYRatioToChart** , **Rapport de largeur intérieure par rapport au graphique** et
**Rapport hauteur intérieure/graphique** propriétés.


Pour Excel 2007 ou version ultérieure, la valeur par défaut est zéro. Vous devez appeler pour obtenir la valeur après avoir appelé Chart.Calculate().

 
HeightPixel = HeightRatioToChart * chart.ChartObject.Width.
###  Définition:
```python
@property
def height_ratio_to_chart(self):
    ...
@height_ratio_to_chart.setter
def height_ratio_to_chart(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.charts`](../../)
* classe [`PlotArea`](/cells/python-net/fr/aspose.cells.charts/plotarea)
