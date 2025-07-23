---
title: Metodo add_button
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un pulsante al foglio di lavoro.


###  ritorna

Un oggetto Button.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo spostamento verticale del pulsante dalla sua riga di sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int |Rappresenta lo spostamento orizzontale del pulsante dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza del pulsante, in pixel.|
| width | int | Rappresenta la larghezza del pulsante, in pixel.|

###  Esempio

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
