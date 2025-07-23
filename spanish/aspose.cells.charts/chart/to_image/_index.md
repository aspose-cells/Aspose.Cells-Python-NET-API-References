---
title: método to_image
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells.charts/chart/to_image/
is_root: false
---
##  to_image(self, image_file) {#str}
Crea la imagen del gráfico y la guarda en un archivo.
La extensión del nombre del archivo determina el formato de la imagen.



```python

def to_image(self, image_file):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| image_file | str | El nombre del archivo de imagen con la ruta completa.|
###  Observaciones

El formato de la imagen se especifica utilizando la extensión del nombre del archivo.
Por ejemplo, si especifica "myfile.png", la imagen se guardará
 En el formato PNG. Se reconocen las siguientes extensiones de archivo:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.

##  to_image(self, image_file, image_type) {#str-aspose.cells.drawing.ImageType}
Crea la imagen del gráfico y la guarda en un archivo en el tipo de imagen especificado.



```python

def to_image(self, image_file, image_type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| image_file | str | El nombre del archivo de imagen con la ruta completa.|
| image_type | aspose.cells.drawing.ImageType | El tipo de imagen en el que se guardará la imagen.|
###  Observaciones

El tipo de imagen se especifica utilizando `imageType`.
 Se admiten los siguientes tipos:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.

##  to_image(self, image_file, jpeg_quality) {#str-int}
Crea la imagen del gráfico y la guarda en un archivo en formato Jpeg.



```python

def to_image(self, image_file, jpeg_quality):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| image_file | str | El nombre del archivo de imagen con la ruta completa.|
| jpeg_quality | int | Calidad jpeg.|
###  Observaciones

Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.
 NOTA: Este método ya no está disponible. En su lugar,
Utilice el método ToImage(string,ImageOrPrintOptions) con la calidad especificada.
 Este método se eliminará 12 meses después, a partir de marzo de 2025.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.

##  to_image(self, stream, jpeg_quality) {#io.RawIOBase-int}
Crea la imagen del gráfico y la guarda en una secuencia en formato Jpeg.



```python

def to_image(self, stream, jpeg_quality):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | El flujo de salida.|
| jpeg_quality | int | Calidad jpeg.|
###  Observaciones

Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.

##  to_image(self, stream, image_type) {#io.RawIOBase-aspose.cells.drawing.ImageType}

Crea la imagen del gráfico y la guarda en una secuencia en el formato especificado.



```python

def to_image(self, stream, image_type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | El flujo de salida.|
| image_type | aspose.cells.drawing.ImageType | El tipo de imagen en el que se guardará la imagen.|
###  Observaciones

El tipo de imagen se especifica utilizando `imageType`.
 Se admiten los siguientes tipos:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.

##  to_image(self, image_file, options) {#str-aspose.cells.rendering.ImageOrPrintOptions}
Crea la imagen del gráfico y la guarda en un archivo.
La extensión del nombre del archivo determina el formato de la imagen.



```python

def to_image(self, image_file, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| image_file | str | El nombre del archivo de imagen con la ruta completa.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Opciones adicionales de creación de imágenes|
###  Observaciones

El formato de la imagen se especifica utilizando la extensión del nombre del archivo.
Por ejemplo, si especifica "myfile.png", la imagen se guardará
 En el formato PNG. Se reconocen las siguientes extensiones de archivo:
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.


Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.
 Por favor refiérase a[Lista de gráficos compatibles](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) Para más detalles.
###  Ejemplo

Se guarda en Tiff con 300 dpi y compresión CCITT4.

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


Se guarda en formato Jpeg con 300 dpi y calidad de imagen 80.

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
Crea la imagen del gráfico y la guarda en una secuencia en el formato especificado.



```python

def to_image(self, stream, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | El flujo de salida.|
| options | aspose.cells.rendering.ImageOrPrintOptions | Opciones adicionales de creación de imágenes|
###  Observaciones

El tipo de imagen se especifica utilizando `options.ImageType`.
 Se admiten los siguientes formatos:
ImageType.Bmp, ImageType.Gif, ImageType.Png, ImageType.Jpeg, ImageType.Tiff, ImageType.Emf.


Si el ancho o la altura son cero o el gráfico no es compatible según la Lista de gráficos compatibles, este método no hará nada.
 Por favor refiérase a[Lista de gráficos compatibles](http://www.aspose.com/documentation/.net-components/aspose.cells-for-.net/converting-chart-to-image.html) Para más detalles.


###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`Chart`](/cells/python-net/es/aspose.cells.charts/chart)
