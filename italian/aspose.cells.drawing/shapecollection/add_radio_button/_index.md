---
title: Metodo add_radio_button
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 250
url: /it/aspose.cells.drawing/shapecollection/add_radio_button/
is_root: false
---
##  add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge un RadioButton al foglio di lavoro.


###  ritorna

Un oggetto RadioButton.


```python

def add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di RadioButton dalla sua riga di sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo spostamento orizzontale di RadioButton dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di RadioButton, in pixel.|
| width | int | Rappresenta la larghezza di RadioButton, in pixel.|

###  Esempio

```python

# add a radio button
radioButton = shapes.add_radio_button(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
