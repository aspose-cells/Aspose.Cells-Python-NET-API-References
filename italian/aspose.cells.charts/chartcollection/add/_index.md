---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
Aggiunge un grafico alla raccolta.


###  ritorna

[`Chart`](/cells/python-net/it/aspose.cells.charts/chart) indice oggetto.


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/it/aspose.cells.charts/charttype) | Tipo di grafico|
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| lower_right_row | int | Indice della riga inferiore destra|
| lower_right_column | int | Indice della colonna in basso a destra|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
Aggiunge un grafico alla raccolta.


###  ritorna

[`Chart`](/cells/python-net/it/aspose.cells.charts/chart) indice oggetto.


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/it/aspose.cells.charts/charttype) | Tipo di grafico|
| data_range | str | Specifica l'intervallo di dati del grafico|
| top_row | int | Indice della riga in alto a sinistra.|
| left_column | int | Indice della colonna in alto a sinistra.|
| right_row | int | Indice della riga inferiore destra|
| bottom_column | int | Indice della colonna in basso a destra|
###  Osservazioni

NOTA: questo membro è ora obsoleto. Invece,
si prega di utilizzare la proprietà [`ChartCollection.add`](/cells/python-net/it/aspose.cells.charts/chartcollection/add).
 Questa proprietà verrà rimossa 12 mesi dopo, a partire da maggio 2022.
Aspose si scusa per ogni eventuale disagio arrecato.

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
Aggiunge un grafico con modello preimpostato.


###  ritorna

[`Chart`](/cells/python-net/it/aspose.cells.charts/chart) indice oggetto.


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| data | bytes | I dati del file modello del grafico (.crtx).|
| data_range | str | Specifica l'intervallo di dati del grafico|
| is_vertical | bool | Specifica se tracciare la serie da un intervallo di valori di cella per riga o per colonna.|
| top_row | int | Indice della riga in alto a sinistra.|
| left_column | int | Indice della colonna in alto a sinistra.|
| right_row | int | Indice della riga inferiore destra|
| bottom_column | int | Indice della colonna in basso a destra|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
Aggiunge un grafico alla raccolta.


###  ritorna

[`Chart`](/cells/python-net/it/aspose.cells.charts/chart) indice oggetto.


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/it/aspose.cells.charts/charttype) | Tipo di grafico|
| data_range | str | Specifica l'intervallo di dati del grafico|
| is_vertical | bool | Specifica se tracciare la serie da un intervallo di valori di cella per riga o per colonna.|
| top_row | int | Indice della riga in alto a sinistra.|
| left_column | int | Indice della colonna in alto a sinistra.|
| right_row | int | Indice della riga inferiore destra|
| bottom_column | int | Indice della colonna in basso a destra|



###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`Chart`](/cells/python-net/it/aspose.cells.charts/chart)
* classe [`ChartCollection`](/cells/python-net/it/aspose.cells.charts/chartcollection)
