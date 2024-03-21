---
title: Metodo freeze_panes
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 140
url: /it/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes {#str-int-int}
Blocca i riquadri nella cella specificata nel foglio di lavoro.



```python
def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_name | str | Cell nome.|
| freezed_rows | int | Numero di righe visibili nel riquadro superiore, non superiore all'indice delle righe.|
| freezed_columns | int | Numero di colonne visibili nel riquadro sinistro, non superiore all'indice della colonna.|
###  Osservazioni

L'indice di riga e l'indice di colonna non possono essere tutti zero. Numero di righe e numero di colonne
inoltre non possono essere tutti zero.

##  freeze_panes {#int-int-int-int}
Blocca i riquadri nella cella specificata nel foglio di lavoro.



```python
def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Indice delle righe.|
| column | int | Indice delle colonne.|
| freezed_rows | int | Numero di righe visibili nel riquadro superiore, non superiore all'indice delle righe.|
| freezed_columns | int | Numero di colonne visibili nel riquadro sinistro, non superiore all'indice della colonna.|
###  Osservazioni

L'indice di riga e l'indice di colonna non possono essere tutti zero. Numero di righe e numero di colonne
inoltre non possono essere tutti zero.


I primi due parametri specificano la posizione bloccata e gli ultimi due parametri specificano l'area bloccata nel riquadro superiore sinistro.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
