---
title: to_image метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 140
url: /ru/aspose.cells.charts/chart/to_image/
is_root: false
---
##  to_image(self, image_file) {#str}
Создает изображение диаграммы и сохраняет его в файл.
Расширение имени файла определяет формат изображения.



```python

def to_image(self, image_file):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| image_file | str | Имя файла изображения с полным путем.|
###  Примечания

Формат изображения указывается с помощью расширения имени файла.
Например, если указать "myfile.png", то изображение будет сохранено
 в формате PNG. Распознаются следующие расширения файлов:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.

##  to_image(self, image_file, image_type) {#str-aspose.cells.drawing.ImageType}
Создает изображение диаграммы и сохраняет его в файле указанного типа изображения.



```python

def to_image(self, image_file, image_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| image_file | str | Имя файла изображения с полным путем.|
| image_type | aspose.cells.drawing.ImageType | Тип изображения, в котором будет сохранено изображение.|
###  Примечания

Тип изображения указывается с помощью `imageType`.
 Поддерживаются следующие типы:
Тип изображения.Bmp, Тип изображения.Gif, Тип изображения.Png, Тип изображения.Jpeg, Тип изображения.Tiff, Тип изображения.Emf.


Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.

##  to_image(self, image_file, jpeg_quality) {#str-int}
Создает изображение диаграммы и сохраняет его в файле в формате Jpeg.



```python

def to_image(self, image_file, jpeg_quality):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| image_file | str | Имя файла изображения с полным путем.|
| jpeg_quality | int | Качество JPEG.|
###  Примечания

Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.
 ПРИМЕЧАНИЕ: Этот метод уже устарел. Вместо этого
используйте метод ToImage(string,ImageOrPrintOptions) с указанным качеством.
 Этот метод будет удален через 12 месяцев, с марта 2025 года.
Aspose приносит извинения за любые причиненные вам неудобства.

##  to_image(self, stream, jpeg_quality) {#io.RawIOBase-int}
Создает изображение диаграммы и сохраняет его в потоке в формате Jpeg.



```python

def to_image(self, stream, jpeg_quality):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Выходной поток.|
| jpeg_quality | int | Качество JPEG.|
###  Примечания

Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.

##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}

Создает изображение диаграммы и сохраняет его в потоке в указанном формате.



```python

def to_image(self, stream, image_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Выходной поток.|
| image_type | aspose.cells.drawing.ImageType | Тип изображения, в котором будет сохранено изображение.|
###  Примечания

Тип изображения указывается с помощью `imageType`.
 Поддерживаются следующие типы:
Тип изображения.Bmp, Тип изображения.Gif, Тип изображения.Png, Тип изображения.Jpeg, Тип изображения.Tiff, Тип изображения.Emf.


Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.

##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
Создает изображение диаграммы и сохраняет его в файл.
Расширение имени файла определяет формат изображения.



```python

def to_image(self, image_file, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| image_file | str | Имя файла изображения с полным путем.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Дополнительные возможности создания изображений|
###  Примечания

Формат изображения указывается с помощью расширения имени файла.
Например, если указать "myfile.png", то изображение будет сохранено
 в формате PNG. Распознаются следующие расширения файлов:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.
 Пожалуйста, обратитесь к[Список поддерживаемых диаграмм](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) для более подробной информации.
###  Пример

Сохраняет в формате Tiff с разрешением 300 точек на дюйм и сжатием CCITT4.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, TiffCompression

options = ImageOrPrintOptions()
options.horizontal_resolution = 300
options.vertical_resolution = 300
options.tiff_compression = TiffCompression.COMPRESSION_CCITT4
book = Workbook(r"test.xls")
book.worksheets[0].charts[0].to_image(r"chart.Tiff", options)

```


Сохраняет в формате Jpeg с разрешением 300 точек на дюйм и качеством изображения 80.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions

options = ImageOrPrintOptions()
options.horizontal_resolution = 300
options.vertical_resolution = 300
options.quality = 80
book = Workbook(r"test.xls")
book.worksheets[0].charts[0].to_image(r"chart.Jpeg", options)

```


##  to_image(self, stream, options) {#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions}
Создает изображение диаграммы и сохраняет его в потоке в указанном формате.



```python

def to_image(self, stream, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Выходной поток.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Дополнительные возможности создания изображений|
###  Примечания

Тип изображения указывается с помощью `options.ImageType`.
 Поддерживаются следующие форматы:
Тип изображения.Bmp, Тип изображения.Gif, Тип изображения.Png, Тип изображения.Jpeg, Тип изображения.Tiff, Тип изображения.Emf.


Если ширина или высота равны нулю или диаграмма не поддерживается в соответствии со списком поддерживаемых диаграмм, этот метод ничего не сделает.
 Пожалуйста, обратитесь к[Список поддерживаемых диаграмм](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) для более подробной информации.


###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart)
