---
title: Metodo add_line
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 170
url: /it/aspose.cells.drawing/shapecollection/add_line/
is_root: false
---
##  add_line(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Aggiunge una LineShape al foglio di lavoro.


###  ritorna

Un oggetto LineShape.


```python

def add_line(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di LineShape dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di LineShape dalla sua colonna di sinistra, in pixel.|
| height | int | Rappresenta l'altezza di LineShape, in pixel.|
| width | int |Rappresenta la larghezza di LineShape, in unità di pixel.|

###  Esempio

```python

#  add a line object
lineShape = shapes.add_line(1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
