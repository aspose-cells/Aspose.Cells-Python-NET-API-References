---
title: Metodo add_shape
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 280
url: /it/aspose.cells.drawing/shapecollection/add_shape/
is_root: false
---
##  add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-int-int}
Aggiunge una forma al foglio di lavoro.


###  ritorna

Un oggetto Forma.


```python

def add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/it/aspose.cells.drawing/msodrawingtype) | Tipo di disegno Mso.|
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale di Shape dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale di Shape dalla sua colonna di sinistra, in unità di pixel.|
| height | int | Rappresenta l'altezza della forma, in pixel.|
| width | int | Rappresenta la larghezza della forma, in unità di pixel.|
###  Osservazioni

Il tipo non può essere Grafico/Commento/Immagine/OleObject/Poligono/Finestra di dialogo
###  Esempio


```python
from aspose.cells.drawing import MsoDrawingType

# Add a shape of the specified type
shapeByType = shapes.add_shape(MsoDrawingType.CELLS_DRAWING, 1, 0, 1, 0, 100, 50)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
