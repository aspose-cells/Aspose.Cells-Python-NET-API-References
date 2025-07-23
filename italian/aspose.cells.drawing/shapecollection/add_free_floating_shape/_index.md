---
title: Metodo add_free_floating_shape
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells.drawing/shapecollection/add_free_floating_shape/
is_root: false
---
##  add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-bytes-bool}
Aggiunge una forma libera fluttuante al foglio di lavoro. Si applica solo alle forme linea/immagine.


###  ritorna




```python

def add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/it/aspose.cells.drawing/msodrawingtype) | Il tipo di forma.|
| top | int | Rappresenta lo scostamento verticale della forma dalla riga superiore del foglio di lavoro, in pixel.|
| left | int | Rappresenta lo scostamento orizzontale della forma dalla colonna di sinistra del foglio di lavoro, in pixel.|
| height | int | Rappresenta l'altezza di LineShape, in pixel.|
| width | int |Rappresenta la larghezza di LineShape, in unità di pixel.|
| image_data | bytes | I dati dell'immagine si applicano solo alla foto.|
| is_original_size | bool | Se la forma è un'immagine, deve utilizzare le dimensioni originali.|

###  Esempio

```python
from aspose import pycore
from aspose.cells.drawing import MsoDrawingType
import bytearray
import int

# add a line
floatingShape_Line = shapes.add_free_floating_shape(MsoDrawingType.LINE, 100, 100, 100, 50, None, False)
# add a picture
imageData = None
with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
floatingShape_Picture = shapes.add_free_floating_shape(MsoDrawingType.PICTURE, 200, 100, 100, 50, imageData, False)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
