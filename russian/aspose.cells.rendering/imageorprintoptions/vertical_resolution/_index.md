---
title: vertical_resolution недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 400
url: /ru/aspose.cells.rendering/imageorprintoptions/vertical_resolution/
is_root: false
---
##  vertical_resolution недвижимость

Получает или задает вертикальное разрешение для создаваемых изображений в точках на дюйм.

###  Примечания

Значение по умолчанию — 96.


Настройка [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) и [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
влияет на ширину и высоту выходного изображения в пикселях.

###  Пример

 Следующий код устанавливает разрешение 192, ширина и высота сгенерированного изображения в два раза больше
тот, у которого разрешение оставлено по умолчанию равным 96.

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

wb = Workbook("Book1.xlsx")
opts = ImageOrPrintOptions()
# Set output image type: png.
opts.image_type = ImageType.PNG
# Set resolution to 192.
opts.horizontal_resolution = 192
opts.vertical_resolution = 192
# Render Chart to image.
wb.worksheets[0].charts[0].to_image("Chart.png", opts)

```
###  Определение:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`ImageOrPrintOptions`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions)
