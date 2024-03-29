---
title: to_image метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 240
url: /ru/aspose.cells.drawing/radiobutton/to_image/
is_root: false
---
##  to_image {#io.RawIOBase-aspose.cells.drawing.ImageType}
Создает изображение фигуры и сохраняет его в поток в указанном формате.



```python
def to_image(self, stream, image_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Выходной поток.|
| image_type | [`ImageType`](/cells/python-net/ru/aspose.cells.drawing/imagetype) | Тип сохранения изображения.|
###  Примечания

Поддерживаются следующие форматы:
.bmp, .gif, .jpg, .jpeg, .tiff, .emf.
###  Пример

```python
from aspose.cells.drawing import ImageType
from io import BytesIO

imageStream = BytesIO()
shape.to_image(imageStream, ImageType.PNG)

```


##  to_image {#str-aspose.cells.rendering.ImageOrPrintOptions}
Сохраняет форму в файл.



```python
def to_image(self, image_file, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| image_file | str |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Пример

```python
from aspose.cells.rendering import ImageOrPrintOptions

op = ImageOrPrintOptions()
shape.to_image("exmaple.png", op)

```


##  to_image {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Сохраняет форму в поток.



```python
def to_image(self, stream, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| options | aspose.cells.rendering.ImageOrPrintOptions |  |

###  Пример

```python
from aspose.cells.rendering import ImageOrPrintOptions
from io import BytesIO

imageStream = BytesIO()
op = ImageOrPrintOptions()
shape.to_image(imageStream, op)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`RadioButton`](/cells/python-net/ru/aspose.cells.drawing/radiobutton)
