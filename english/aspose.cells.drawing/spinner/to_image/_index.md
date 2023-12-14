﻿---
title: to_image method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 230
url: /aspose.cells.drawing/spinner/to_image/
is_root: false
---

## to_image {#io.RawIOBase-aspose.cells.drawing.ImageType}

Creates the shape image and saves it to a stream in the specified format.



```python
def to_image(self, stream, image_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The output stream. |
| image_type | [`ImageType`](/cells/python-net/aspose.cells.drawing/imagetype) | The type in which to save the image. |
### Remarks

The following formats are supported: 
.bmp, .gif, .jpg, .jpeg, .tiff, .emf.
### Example 


```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


## to_image {#str-aspose.cells.rendering.ImageOrPrintOptions}

Saves the shape to a file.



```python
def to_image(self, image_file, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

### Example 


```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


## to_image {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}

Saves the shape to a stream.



```python
def to_image(self, stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

### Example 


```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`Spinner`](/cells/python-net/aspose.cells.drawing/spinner)
