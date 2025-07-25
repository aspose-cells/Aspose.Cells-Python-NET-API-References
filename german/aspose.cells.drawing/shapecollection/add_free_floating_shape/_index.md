---
title: add_free_floating_shape Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells.drawing/shapecollection/add_free_floating_shape/
is_root: false
---
##  add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-bytes-bool}
Fügt dem Arbeitsblatt eine frei schwebende Form hinzu. Gilt nur für Linien-/Bildformen.


###  Kehrt zurück




```python

def add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/de/aspose.cells.drawing/msodrawingtype) | Der Formtyp.|
| top | int | Stellt den vertikalen Versatz der Form von der obersten Zeile des Arbeitsblatts in Pixeleinheiten dar.|
| left | int | Stellt den horizontalen Versatz der Form von der linken Spalte des Arbeitsblatts in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Linienform in Pixeln dar.|
| width | int |Stellt die Breite der Linienform in Pixeln dar.|
| image_data | bytes | Die Bilddaten gelten nur für das Foto.|
| is_original_size | bool | Ob die Form die Originalgröße verwendet, wenn es sich bei der Form um ein Bild handelt.|

###  Beispiel

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



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
