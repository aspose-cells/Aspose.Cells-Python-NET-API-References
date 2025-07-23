---
title: Metodo add_label
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 150
url: /it/aspose.cells.drawing/shapecollection/add_label/
is_root: false
---
##  add_label(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un'etichetta al foglio di lavoro.


###  ritorna

Un oggetto Etichetta.


```python

def add_label(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int |Rappresenta lo scostamento verticale dell'etichetta dalla sua riga di sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale dell'etichetta dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza dell'etichetta, in pixel.|
| width | int | Rappresenta la larghezza dell'etichetta, in pixel.|

###  Esempio

```python

# add a label
label = shapes.add_label(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
