---
title: to_image metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 230
url: /sv/aspose.cells.drawing/combobox/to_image/
is_root: false
---
##  to_image {#io.RawIOBase-aspose.cells.drawing.ImageType}
Skapar formbilden och sparar den i en ström i det angivna formatet.



```python
def to_image(self, stream, image_type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | Utgångsströmmen.|
| image_type | [`ImageType`](/cells/python-net/sv/aspose.cells.drawing/imagetype) | Typen där bilden ska sparas.|
###  Anmärkningar

Följande format stöds:
.bmp, .gif, .jpg, .jpeg, .tiff, .emf.
###  Exempel

```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


##  to_image {#str-aspose.cells.rendering.ImageOrPrintOptions}
Sparar formen till en fil.



```python
def to_image(self, image_file, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Exempel

```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


##  to_image {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Sparar formen till en ström.



```python
def to_image(self, stream, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Exempel

```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ComboBox`](/cells/python-net/sv/aspose.cells.drawing/combobox)
