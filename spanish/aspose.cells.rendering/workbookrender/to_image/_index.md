---
title: método to_image
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image {#io.RawIOBase}
Renderice todo el libro como imagen Tiff para transmitirlo.



```python
def to_image(self, stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | el flujo de la imagen de salida|


##  to_image {#str}
Renderice todo el libro como imagen Tiff en un archivo.



```python
def to_image(self, filename):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| filename | str | el nombre de archivo de la imagen de salida|


##  to_image {#int-str}
Renderiza cierta página en un archivo.



```python
def to_image(self, page_index, file_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| page_index | int | indicar qué página se va a convertir|
| file_name | str | nombre de archivo de la imagen de salida|


##  to_image {#int-io.RawIOBase}
Renderiza cierta página en una secuencia.



```python
def to_image(self, page_index, stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| page_index | int | indicar qué página se va a convertir|
| stream | io.RawIOBase | el flujo de la imagen de salida|



###  Ver también
* módulo [`aspose.cells.rendering`](../../)
* clase [`WorkbookRender`](/cells/python-net/es/aspose.cells.rendering/workbookrender)
