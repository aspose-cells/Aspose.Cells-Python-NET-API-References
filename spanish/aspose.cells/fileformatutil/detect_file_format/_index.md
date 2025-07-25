---
title: método detect_file_format
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, transmisión){#io.RawIOBase}
Detecta y devuelve la información sobre un formato de un Excel almacenado en una secuencia.


###  Devoluciones

Un objeto [`FileFormatInfo`](/cells/python-net/es/aspose.cells/fileformatinfo) que contiene la información detectada.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, ruta_del_archivo){#str}
Detecta y devuelve la información sobre un formato de un Excel almacenado en un archivo.


###  Devoluciones

Un objeto [`FileFormatInfo`](/cells/python-net/es/aspose.cells/fileformatinfo) que contiene la información detectada.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file_path | str | La ruta del archivo.|


##  detect_file_format(, transmisión, contraseña){#io.RawIOBase-str}
Detecta y devuelve la información sobre un formato de un Excel almacenado en una secuencia.


###  Devoluciones

Un objeto [`FileFormatInfo`](/cells/python-net/es/aspose.cells/fileformatinfo) que contiene la información detectada.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | La contraseña para archivos ooxml cifrados.|


##  detect_file_format(, ruta_del_archivo, contraseña){#str-str}
Detecta y devuelve la información sobre un formato de un Excel almacenado en un archivo.


###  Devoluciones

Un objeto [`FileFormatInfo`](/cells/python-net/es/aspose.cells/fileformatinfo) que contiene la información detectada.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file_path | str | La ruta del archivo.|
| password | str | La contraseña para archivos ooxml cifrados.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FileFormatInfo`](/cells/python-net/es/aspose.cells/fileformatinfo)
* clase [`FileFormatUtil`](/cells/python-net/es/aspose.cells/fileformatutil)
