---
title: Metodo add_list_box
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 190
url: /it/aspose.cells.drawing/shapecollection/add_list_box/
is_root: false
---
##  add_list_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un controllo ListBox al foglio di lavoro.


###  ritorna

Un oggetto ListBox.


```python

def add_list_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di ListBox dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di ListBox dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di ListBox, in pixel.|
| width | int | Rappresenta la larghezza di ListBox, in pixel.|

###  Esempio

```python

# add a list box
listBox = shapes.add_list_box(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
