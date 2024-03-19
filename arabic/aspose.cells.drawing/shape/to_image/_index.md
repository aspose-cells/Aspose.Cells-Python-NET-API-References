---
title: طريقة to_image
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 230
url: /ar/aspose.cells.drawing/shape/to_image/
is_root: false
---
##  to_image {#io.RawIOBase-aspose.cells.drawing.ImageType}
يقوم بإنشاء صورة الشكل وحفظها في دفق بالتنسيق المحدد.



```python
def to_image(self, stream, image_type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | تيار الإخراج.|
| image_type | [`ImageType`](/cells/python-net/ar/aspose.cells.drawing/imagetype) | النوع الذي سيتم حفظ الصورة به.|
###  ملاحظات

يتم دعم التنسيقات التالية:
.bmp، .gif، .jpg، .jpeg، .tiff، .emf.
###  مثال

```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


##  to_image {#str-aspose.cells.rendering.ImageOrPrintOptions}
يحفظ الشكل في ملف.



```python
def to_image(self, image_file, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  مثال

```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


##  to_image {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
يحفظ الشكل في دفق.



```python
def to_image(self, stream, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  مثال

```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Shape`](/cells/python-net/ar/aspose.cells.drawing/shape)
