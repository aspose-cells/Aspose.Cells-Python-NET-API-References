---
title: Metodo add_active_x_control
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
Crea un controllo ActiveX.


###  ritorna




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | Il tipo di controllo.|
| top_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di Shape dalla sua riga sinistra, in pixel.|
| left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di Shape dalla sua colonna di sinistra, in unità di pixel.|
| width | int | Rappresenta la larghezza della forma, in unità di pixel.|
| height | int | Rappresenta l'altezza della forma, in pixel.|

###  Esempio

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
