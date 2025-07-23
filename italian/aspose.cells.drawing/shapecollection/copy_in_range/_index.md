---
title: Metodo copy_in_range
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 410
url: /it/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
Copia le forme nell'intervallo nell'intervallo di destinazione.



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection) | Forme sorgente.|
| ca | [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) | L'intervallo di origine.|
| dest_row | int | Indice della riga dest dell'intervallo dest.|
| dest_column | int | La colonna dest dell'intervallo dest.|
| is_contained | bool | Se copiare solo le forme contenute nell'intervallo.<br/> Se è vero, copia solo le forme nell'intervallo.<br/> Altrimenti funziona come MS Office.|

###  Esempio

```python
from aspose.cells import CellArea

# add a shape
shapes.add_rectangle(2, 0, 2, 0, 130, 130)
area2 = CellArea()
area2.start_column = 1
area2.start_row = 1
area2.end_column = 5
area2.end_row = 11
# copy
shapes.copy_in_range(shapes, area2, 12, 1, False)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
