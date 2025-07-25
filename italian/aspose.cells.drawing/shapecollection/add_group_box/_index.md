---
title: Metodo add_group_box
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 130
url: /it/aspose.cells.drawing/shapecollection/add_group_box/
is_root: false
---
##  add_group_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un GroupBox al foglio di lavoro.


###  ritorna

Un oggetto GroupBox.


```python

def add_group_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di GroupBox dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di GroupBox dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di GroupBox, in pixel.|
| width | int | Rappresenta la larghezza di GroupBox, in pixel.|

###  Esempio

```python

# add a group box
groupBox = shapes.add_group_box(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
