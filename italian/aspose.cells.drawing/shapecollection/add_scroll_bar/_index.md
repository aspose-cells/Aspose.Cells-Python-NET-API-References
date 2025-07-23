---
title: Metodo add_scroll_bar
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 270
url: /it/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge una barra di scorrimento al foglio di lavoro.


###  ritorna

Un oggetto ScrollBar.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int |Rappresenta lo scostamento verticale di ScrollBar dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di ScrollBar dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di ScrollBar, in pixel.|
| width | int | Rappresenta la larghezza della barra di scorrimento, in pixel.|

###  Esempio

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
