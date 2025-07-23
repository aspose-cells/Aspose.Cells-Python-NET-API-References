---
title: Metodo add_spinner
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 320
url: /it/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge uno Spinner al foglio di lavoro.


###  ritorna

Un oggetto Spinner.


```python

def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int |Rappresenta lo spostamento verticale di Spinner dalla sua riga sinistra, in unità di pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo spostamento orizzontale di Spinner dalla sua colonna di sinistra, in unità di pixel.|
| height | int | Rappresenta l'altezza dello Spinner, in unità di pixel.|
| width | int | Rappresenta la larghezza dello Spinner, in unità di pixel.|

###  Esempio

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
