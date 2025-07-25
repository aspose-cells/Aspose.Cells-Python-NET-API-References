---
title: méthode add
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
Ajoute un graphique à la collection.


###  Retour

[`Chart`](/cells/python-net/fr/aspose.cells.charts/chart) index d'objet.


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/fr/aspose.cells.charts/charttype) | Type de graphique|
| upper_left_row | int | Index de la rangée supérieure gauche.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| lower_right_row | int | Index de la ligne inférieure droite|
| lower_right_column | int | Index de la colonne inférieure droite|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
Ajoute un graphique à la collection.


###  Retour

[`Chart`](/cells/python-net/fr/aspose.cells.charts/chart) index d'objet.


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/fr/aspose.cells.charts/charttype) | Type de graphique|
| data_range | str | Spécifie la plage de données du graphique|
| top_row | int | Index de la rangée supérieure gauche.|
| left_column | int | Index de la colonne supérieure gauche.|
| right_row | int | Index de la ligne inférieure droite|
| bottom_column | int | Index de la colonne inférieure droite|
###  Remarques

REMARQUE : Ce membre est désormais obsolète. À la place,
veuillez utiliser la propriété [`ChartCollection.add`](/cells/python-net/fr/aspose.cells.charts/chartcollection/add).
 Cette propriété sera supprimée 12 mois plus tard soit en mai 2022.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
Ajoute un graphique avec un modèle prédéfini.


###  Retour

[`Chart`](/cells/python-net/fr/aspose.cells.charts/chart) index d'objet.


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| data | bytes | Les données du fichier de modèle de graphique (.crtx).|
| data_range | str | Spécifie la plage de données du graphique|
| is_vertical | bool | Spécifie s'il faut tracer la série à partir d'une plage de valeurs de cellules par ligne ou par colonne.|
| top_row | int | Index de la rangée supérieure gauche.|
| left_column | int | Index de la colonne supérieure gauche.|
| right_row | int | Index de la ligne inférieure droite|
| bottom_column | int | Index de la colonne inférieure droite|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
Ajoute un graphique à la collection.


###  Retour

[`Chart`](/cells/python-net/fr/aspose.cells.charts/chart) index d'objet.


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/fr/aspose.cells.charts/charttype) | Type de graphique|
| data_range | str | Spécifie la plage de données du graphique|
| is_vertical | bool | Spécifie s'il faut tracer la série à partir d'une plage de valeurs de cellules par ligne ou par colonne.|
| top_row | int | Index de la rangée supérieure gauche.|
| left_column | int | Index de la colonne supérieure gauche.|
| right_row | int | Index de la ligne inférieure droite|
| bottom_column | int | Index de la colonne inférieure droite|



###  Voir également
* module [`aspose.cells.charts`](../../)
* classe [`Chart`](/cells/python-net/fr/aspose.cells.charts/chart)
* classe [`ChartCollection`](/cells/python-net/fr/aspose.cells.charts/chartcollection)
