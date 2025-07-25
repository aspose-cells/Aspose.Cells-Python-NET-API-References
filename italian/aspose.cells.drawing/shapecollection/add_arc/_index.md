---
title: Metodo add_arc
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells.drawing/shapecollection/add_arc/
is_root: false
---
##  add_arc(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un ArcShape al foglio di lavoro.


###  ritorna

Un oggetto ArcShape.


```python

def add_arc(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int |Rappresenta lo scostamento verticale di ArcShape dalla sua riga di sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di ArcShape dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di ArcShape, in pixel.|
| width | int | Rappresenta la larghezza di ArcShape, in pixel.|

###  Esempio

```python

# add a arc
arcShape = shapes.add_arc(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
