---
title: Metodo add_rectangle
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 260
url: /it/aspose.cells.drawing/shapecollection/add_rectangle/
is_root: false
---
##  add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un oggetto RectangleShape al foglio di lavoro.


###  ritorna

Un oggetto RectangleShape.


```python

def add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di RectangleShape dalla sua riga di sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di RectangleShape dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di RectangleShape, in pixel.|
| width | int | Rappresenta la larghezza di RectangleShape, in unità di pixel.|

###  Esempio

```python

#  add a rectangle
rectangleShape = shapes.add_rectangle(2, 0, 2, 0, 130, 130)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
