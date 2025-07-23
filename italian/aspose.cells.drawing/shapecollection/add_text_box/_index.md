---
title: Metodo add_text_box
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 340
url: /it/aspose.cells.drawing/shapecollection/add_text_box/
is_root: false
---
##  add_text_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge una casella di testo al foglio di lavoro.


###  ritorna

Un oggetto [`TextBox`](/cells/python-net/it/aspose.cells.drawing/textbox).


```python

def add_text_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale della casella di testo dalla sua riga superiore, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale della casella di testo dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza della casella di testo, in pixel.|
| width | int | Rappresenta la larghezza della casella di testo, in pixel.|

###  Esempio

```python

# add a TextBox
textBox = shapes.add_text_box(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
* classe [`TextBox`](/cells/python-net/it/aspose.cells.drawing/textbox)
