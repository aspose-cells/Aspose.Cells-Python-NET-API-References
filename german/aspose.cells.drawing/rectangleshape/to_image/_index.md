---
title: to_image Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 240
url: /de/aspose.cells.drawing/rectangleshape/to_image/
is_root: false
---
##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}
Erstellt das Formbild und speichert es im angegebenen Format in einem Stream.



```python

def to_image(self, stream, image_type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase | Der Ausgabestream.|
| image_type | [`ImageType`](/cells/python-net/de/aspose.cells.drawing/imagetype) | Der Typ, in dem das Bild gespeichert werden soll.|
###  Bemerkungen

Die folgenden Formate werden unterstützt:
.bmp, .gif, .jpg, .jpeg, .tiff, .emf.
###  Beispiel

```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
Speichert die Form in einer Datei.



```python

def to_image(self, image_file, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Beispiel

```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


##  to_image(self, stream, options) {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Speichert die Form in einem Stream.



```python

def to_image(self, stream, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Beispiel

```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`RectangleShape`](/cells/python-net/de/aspose.cells.drawing/rectangleshape)
