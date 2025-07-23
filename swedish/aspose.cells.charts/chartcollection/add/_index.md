---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
Lägger till ett diagram i samlingen.


###  Returnerar

[`Chart`](/cells/python-net/sv/aspose.cells.charts/chart) objektindex.


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/sv/aspose.cells.charts/charttype) | Diagramtyp|
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| lower_right_row | int | Index nedre högra raden|
| lower_right_column | int | Index i nedre högra kolumnen|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
Lägger till ett diagram i samlingen.


###  Returnerar

[`Chart`](/cells/python-net/sv/aspose.cells.charts/chart) objektindex.


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/sv/aspose.cells.charts/charttype) | Diagramtyp|
| data_range | str | Anger diagrammets dataområde|
| top_row | int | Index för övre vänstra raden.|
| left_column | int | Index i övre vänstra kolumnen.|
| right_row | int | Index nedre högra raden|
| bottom_column | int | Index i nedre högra kolumnen|
###  Anmärkningar

OBS! Denna medlem är nu föråldrad. Istället,
Vänligen använd fastigheten [`ChartCollection.add`](/cells/python-net/sv/aspose.cells.charts/chartcollection/add).
 Den här egenskapen kommer att tas bort 12 månader senare från och med maj 2022.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
Lägger till ett diagram med förinställd mall.


###  Returnerar

[`Chart`](/cells/python-net/sv/aspose.cells.charts/chart) objektindex.


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| data | bytes | Data för diagrammallfilen (.crtx).|
| data_range | str | Anger diagrammets dataområde|
| is_vertical | bool | Anger om serien från ett cellvärdeintervall ska plottas rad för rad eller kolumn.|
| top_row | int | Index för övre vänstra raden.|
| left_column | int | Index i övre vänstra kolumnen.|
| right_row | int | Index nedre högra raden|
| bottom_column | int | Index i nedre högra kolumnen|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
Lägger till ett diagram i samlingen.


###  Returnerar

[`Chart`](/cells/python-net/sv/aspose.cells.charts/chart) objektindex.


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/sv/aspose.cells.charts/charttype) | Diagramtyp|
| data_range | str | Anger diagrammets dataområde|
| is_vertical | bool | Anger om serien från ett cellvärdeintervall ska plottas rad för rad eller kolumn.|
| top_row | int | Index för övre vänstra raden.|
| left_column | int | Index i övre vänstra kolumnen.|
| right_row | int | Index nedre högra raden|
| bottom_column | int | Index i nedre högra kolumnen|



###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`Chart`](/cells/python-net/sv/aspose.cells.charts/chart)
* klass [`ChartCollection`](/cells/python-net/sv/aspose.cells.charts/chartcollection)
