---
title: méthode remove_date_filter
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Supprime un filtre de date.



```python

def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| field_index | int | Le décalage entier du champ sur lequel vous souhaitez baser le filtre<br/> (à partir de la gauche de la liste ; le champ le plus à gauche est le champ 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/fr/aspose.cells/datetimegroupingtype) | Le type de regroupement|
| year | int | L'année.|
| month | int | Le mois.|
| day | int | Le jour.|
| hour | int | L'heure.|
| minute | int | La minute.|
| second | int | Le deuxième.|
###  Remarques

Si DateTimeGroupingType est Year, seul le paramètre year est pris en compte.
Si DateTiemGroupingType est Month, seuls les paramètres year et month ont un effet.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`AutoFilter`](/cells/python-net/fr/aspose.cells/autofilter)
