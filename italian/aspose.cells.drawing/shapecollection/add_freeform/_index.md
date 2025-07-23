---
title: Metodo add_freeform
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 120
url: /it/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
Aggiunge una forma libera al foglio di lavoro.


###  ritorna

Una forma libera.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale della forma libera dalla sua riga di sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Rappresenta lo scostamento orizzontale della forma libera dalla sua colonna di sinistra, in unità di pixel.|
| height | int | Rappresenta l'altezza della forma libera, in unità di pixel.|
| width | int | Rappresenta la larghezza della forma libera, in unità di pixel.|
| paths | list | Rappresenta un percorso definito dall'utente|
###  Osservazioni

Nota: la larghezza e l'altezza nei parametri possono essere qualsiasi valore intero positivo, non la larghezza e l'altezza totali dell'array ShapePath specificato da "paths". La relazione tra loro è di tipo scala-riempimento, ovvero ogni oggetto ShapePath verrà ridimensionato in base alla larghezza e all'altezza. Pertanto, quando sono presenti più oggetti nei "paths", ogni oggetto ShapePath deve essere progettato in modo ragionevole per soddisfare le aspettative. Quando è presente un solo oggetto ShapePath e non ci sono altri requisiti, passare la larghezza e l'altezza dell'oggetto come valori di parametro è una buona soluzione.
###  Esempio


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
