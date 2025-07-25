---
title: Metodo add_oval
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 220
url: /it/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un ovale al foglio di lavoro.


###  ritorna

Un oggetto ovale.


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale dell'Oval dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di Oval dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza dell'ovale, in pixel.|
| width | int | Rappresenta la larghezza dell'ovale, in pixel.|

###  Esempio

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
