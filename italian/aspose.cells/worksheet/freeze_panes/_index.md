---
title: Metodo freeze_panes
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 140
url: /it/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Blocca i riquadri nella cella specificata nel foglio di lavoro.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_name | str | Cell nome.|
| freezed_rows | int | Numero di righe visibili nel riquadro superiore, non più dell'indice di riga.|
| freezed_columns | int | Numero di colonne visibili nel riquadro di sinistra, non più dell'indice di colonna.|
###  Osservazioni

L'indice di riga e l'indice di colonna non possono essere tutti zero. Numero di righe e numero di colonne
inoltre non possono essere tutti zero.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Blocca i riquadri nella cella specificata nel foglio di lavoro.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Indice di riga.|
| column | int | Indice delle colonne.|
| freezed_rows | int | Numero di righe visibili nel riquadro superiore, non più dell'indice di riga.|
| freezed_columns | int | Numero di colonne visibili nel riquadro di sinistra, non più dell'indice di colonna.|
###  Osservazioni

L'indice di riga e l'indice di colonna non possono essere tutti zero. Numero di righe e numero di colonne
inoltre non possono essere tutti zero.


I primi due parametri specificano la posizione congelata, mentre gli ultimi due parametri specificano l'area congelata nel riquadro in alto a sinistra.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
