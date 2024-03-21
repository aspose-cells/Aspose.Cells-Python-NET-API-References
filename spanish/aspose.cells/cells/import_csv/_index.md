---
title: método import_csv
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 620
url: /es/aspose.cells/cells/import_csv/
is_root: false
---
##  import_csv {#str-aspose.cells.TxtLoadOptions-int-int}
Importe un archivo CSV a las celdas.



```python
def import_csv(self, file_name, options, first_row, first_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file_name | str | El nombre del archivo CSV.|
| options | [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions) | Las opciones de carga para leer archivos de texto.|
| first_row | int | El número de fila de la primera celda a importar.|
| first_column | int | El número de columna de la primera celda a importar.|


##  import_csv {#io.RawIOBase-aspose.cells.TxtLoadOptions-int-int}
Importe un archivo CSV a las celdas.



```python
def import_csv(self, stream, options, first_row, first_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | La secuencia de archivos CSV.|
| options | [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions) | Las opciones de carga para leer archivos de texto.|
| first_row | int | El número de fila de la primera celda a importar.|
| first_column | int | El número de columna de la primera celda a importar.|


##  import_csv {#str-str-bool-int-int}
Importe un archivo CSV a las celdas.



```python
def import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file_name | str | El nombre del archivo CSV.|
| splitter | str | el divisor|
| convert_numeric_data | bool | Si la cadena del archivo de texto se convierte en datos numéricos.|
| first_row | int | El número de fila de la primera celda a importar.|
| first_column | int | El número de columna de la primera celda a importar.|


##  import_csv {#io.RawIOBase-str-bool-int-int}
Importe un archivo CSV a las celdas.



```python
def import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase | La secuencia de archivos CSV.|
| splitter | str | el divisor|
| convert_numeric_data | bool | Si la cadena del archivo de texto se convierte en datos numéricos.|
| first_row | int | El número de fila de la primera celda a importar.|
| first_column | int | El número de columna de la primera celda a importar.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
