---
title: método insert_image
second_title: Aspose.Cells.GridJs for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

Inserta una imagen en la hoja de trabajo desde la secuencia de archivos o la URL (se debe proporcionar la secuencia de archivos o la URL)
 o
Inserta forma, cuando el tipo p es uno de AutoShapeType


###  Devoluciones


La cadena de formato JSON de la imagen insertada.


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| uid | str | La identificación única para el caché de archivos.|
| p | str |La cadena de formato JSON para la operación que especifica la ubicación de la celda, el nombre de la hoja de trabajo, la fila superior izquierda, la columna superior izquierda de la imagen, etc. {nombre:'hoja1',ri:1,ci:1} |
| s | io.RawIOBase | La secuencia de archivos del archivo de imagen.|
| image_url | str | La URL del archivo de imagen.|



###  Ver también
* módulo [`aspose.cellsgridjs`](../../)
* clase [`GridJsWorkbook`](/cells/python-net/es/aspose.cellsgridjs/gridjsworkbook)
