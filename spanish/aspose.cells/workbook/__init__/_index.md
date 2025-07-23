---
title: Workbook constructor
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(yo mismo){#}
Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  Observaciones

El formato de archivo predeterminado es XLSX. Si desea crear otros tipos de archivos, utilice Workbook(FileFormatType).
###  Ejemplo


El siguiente código muestra cómo utilizar el constructor Workbook para crear e inicializar una nueva instancia de la clase.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(self, tipo_de_formato_de_archivo){#aspose.cells.FileFormatType}
Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/es/aspose.cells/fileformattype) | El nuevo formato de archivo.|
###  Observaciones

El tipo de formato de archivo predeterminado es Excel97To2003.
###  Ejemplo


El siguiente código muestra cómo utilizar el constructor Workbook para crear e inicializar una nueva instancia de la clase con varios tipos de formato de archivo.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(self, archivo){#str}
Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un archivo.



```python

def __init__(self, file):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file | str | El nombre del archivo.|


##  \_\_init\_\_(self, flujo){#io.RawIOBase}
Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un flujo.



```python

def __init__(self, stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | El arroyo.|


##  \_\_init\_\_(self, archivo, opciones_de_carga){#str-aspose.cells.LoadOptions}
Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un archivo.



```python

def __init__(self, file, load_options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file | str | El nombre del archivo.|
| load_options | [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) | Las opciones de carga|


##  \_\_init\_\_(self, stream, opciones_de_carga){#io.RawIOBase-aspose.cells.LoadOptions}
Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre el flujo.



```python

def __init__(self, stream, load_options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | El arroyo.|
| load_options | [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) | Las opciones de carga|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
