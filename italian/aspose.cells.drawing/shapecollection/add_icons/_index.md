---
title: Metodo add_icons
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 140
url: /it/aspose.cells.drawing/shapecollection/add_icons/
is_root: false
---
##  add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
Aggiunge l'immagine svg.


###  ritorna




```python

def add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| top | int | Rappresenta lo scostamento verticale della forma dalla sua riga sinistra, in pixel.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| left | int | Lo scostamento orizzontale della forma dalla sua colonna di sinistra, in unità di pixel.|
| height | int | L'altezza della forma, in unità di pixel.|
| width | int | Larghezza della forma, in unità di pixel.|
| image_byte_data | bytes | I dati in byte dell'immagine.|
| compatible_image_data | bytes | Dati immagine convertiti da svg per renderli compatibili con Excel 2016 o versioni precedenti.|

###  Esempio

```python
from aspose import pycore
import bytearray
import int

# add icon
with open("icon.svg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    picture = shapes.add_icons(4, 0, 5, 0, -1, -1, imageData, None)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
