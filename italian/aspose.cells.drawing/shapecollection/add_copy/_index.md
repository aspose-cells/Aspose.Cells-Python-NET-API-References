---
title: Metodo add_copy
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Aggiunge e copia una forma nel foglio di lavoro.


###  ritorna

Il nuovo oggetto [`Shape`](/cells/python-net/it/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/it/aspose.cells.drawing/shape) | Forma della sorgente.|
| top_row | int |Indice della riga superiore.|
| top | int | Rappresenta lo scostamento verticale dalla riga superiore, in unità di pixel.|
| left_column | int | Indice della colonna di sinistra.|
| left | int | Rappresenta lo scostamento orizzontale dalla colonna di sinistra, in pixel.|

###  Esempio

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`Shape`](/cells/python-net/it/aspose.cells.drawing/shape)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
