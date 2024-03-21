---
title: Metodo to_image
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 230
url: /it/aspose.cells.drawing/commentshape/to_image/
is_root: false
---
##  to_image {#io.RawIOBase-aspose.cells.drawing.ImageType}
Crea l'immagine della forma e la salva in un flusso nel formato specificato.



```python
def to_image(self, stream, image_type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il flusso di output.|
| image_type | [`ImageType`](/cells/python-net/it/aspose.cells.drawing/imagetype) | Il tipo in cui salvare l'immagine.|
###  Osservazioni

Sono supportati i seguenti formati:
.bmp, .gif, .jpg, .jpeg, .tiff, .emf.
###  Esempio

```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


##  to_image {#str-aspose.cells.rendering.ImageOrPrintOptions}
Salva la forma in un file.



```python
def to_image(self, image_file, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Esempio

```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


##  to_image {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Salva la forma in un flusso.



```python
def to_image(self, stream, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Esempio

```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`CommentShape`](/cells/python-net/it/aspose.cells.drawing/commentshape)
