---
title: méthode is_chart_data_changed
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Détecte si la source de données d'un graphique a changé.


###  Retour

Renvoie vrai si le graphique a changé, sinon renvoie faux


```python

def is_chart_data_changed(self):
    ...
```


###  Remarques

La méthode détecte les modifications dans la source de données du graphique avant de restituer le graphique au format image.
Lors du premier appel à Chart.toImage, les données source du graphique (par exemple XValuesParseData, ValuesParseData) seront enregistrées.
Avant d'appeler à nouveau la méthode Chart.toImage, appelez la méthode IsChartDataChanged pour vérifier si Chart doit être restitué.


###  Voir également
* module [`aspose.cells.charts`](../../)
* classe [`Chart`](/cells/python-net/fr/aspose.cells.charts/chart)
