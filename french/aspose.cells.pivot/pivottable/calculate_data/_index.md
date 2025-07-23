---
title: méthode calculate_data
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
Calcule les données du tableau croisé dynamique en cellules.



```python

def calculate_data(self):
    ...
```


###  Remarques

Cell.La valeur dans la plage pivot ne peut pas renvoyer le résultat correct si la méthode n'a pas été appelée.
Cette méthode calcule les données avec un cache pivot interne, et non avec la source de données d'origine.
Donc, si la source de données est modifiée, veuillez d'abord appeler la méthode RefreshData().

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
Calcul des tableaux croisés dynamiques avec options



```python

def calculate_data(self, option):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/fr/aspose.cells.pivot/pivottablecalculateoption) |  |



###  Voir également
* module [`aspose.cells.pivot`](../../)
* classe [`PivotTable`](/cells/python-net/fr/aspose.cells.pivot/pivottable)
