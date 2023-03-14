---
title: x propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells.charts/plotarea/x/
is_root: false
---
##  x propriété

Obtient ou obtient la coordonnée x du coin supérieur gauche de la zone de délimitation de la zone de tracé en unités de 1/4000 de la zone du graphique.

###  Remarques

La boîte englobante de la zone de tracé comprend la zone de tracé, les graduations (étiquettes de graduation) et une petite bordure autour des graduations.
 Si la valeur n'est pas créée par MS Excel, veuillez appeler la méthode Chart.Calculate() avant d'appeler cette méthode.


 Le**X** , **Y** , **Largeur** et**Hauteur** de**Zone de tracé** représente la surface de la parcelle
 boîte englobante qui comprend la zone de tracé, les graduations (étiquettes de graduation) et une petite bordure autour des graduations.
 Si vous voulez obtenir la taille réelle de la zone de tracé, vous devez appeler**IntérieurX** , **IntérieurY** , **Largeurintérieure** et
**Hauteurintérieure** propriétés.


Pour Excel 2007 ou ultérieur, la valeur par défaut est zéro. vous devez appeler obtenir la valeur après avoir appelé Chart.Calculate().
###  Définition:
```python
@property
def x(self):
    ...
@x.setter
def x(self, value):
    ...
```

###  Voir également
* module [aspose.cells.charts](../../)
* classe [PlotArea](/cells/python-net/fr/aspose.cells.charts/plotarea)
