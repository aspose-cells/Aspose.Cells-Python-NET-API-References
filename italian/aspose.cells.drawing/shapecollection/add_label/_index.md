---
title: metodo add_label
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 130
url: /it/aspose.cells.drawing/shapecollection/add_label/
is_root: false
---
##  add_label(upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
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
| top | int | Rappresenta l'offset verticale di Label dalla relativa riga sinistra, in unità di pixel.|
| upper_left_column | int | Indice colonna in alto a sinistra.|
| left | int | Rappresenta l'offset orizzontale di Label dalla colonna di sinistra, in unità di pixel.|
| height | int | Rappresenta l'altezza di Label, in unità di pixel.|
| width | int | Rappresenta la larghezza dell'etichetta, in unità di pixel.|

###  Esempio

```python

# add a label
label = shapes.add_label(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [aspose.cells.drawing](../../)
* classe [ShapeCollection](/cells/python-net/it/aspose.cells.drawing/shapecollection)
