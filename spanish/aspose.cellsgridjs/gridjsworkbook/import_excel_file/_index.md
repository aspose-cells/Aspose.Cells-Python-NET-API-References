---
title: método import_excel_file
second_title: Aspose.Cells.GridJs for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cellsgridjs/gridjsworkbook/import_excel_file/
is_root: false
---
##  import_excel_file {#str}

Importa el archivo de Excel desde la ruta del archivo.



```python
def import_excel_file(self, file_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| file_name | str | La ruta completa del archivo.|


##  import_excel_file {#str-str}

Importa el archivo de Excel desde la ruta del archivo.



```python
def import_excel_file(self, uid, file_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| uid | str | La identificación única para el caché de archivos, si se establece en nulo, se generará automáticamente.|
| file_name | str | La ruta completa del archivo.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Importa el archivo de Excel desde la secuencia de archivos con formato de carga.



```python
def import_excel_file(self, filestream, format):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| filestream | io.RawIOBase | La secuencia del archivo de Excel.|
| format | [`GridLoadFormat`](/cells/python-net/es/aspose.cellsgridjs/gridloadformat) | El LoadFormat del archivo de Excel.|


##  import_excel_file {#str-str-str}

Importa el archivo de Excel desde la ruta del archivo y la contraseña de apertura.



```python
def import_excel_file(self, uid, file_name, password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| uid | str | La identificación única para el caché de archivos, si se establece en nulo, se generará automáticamente.|
| file_name | str | La ruta completa del archivo.|
| password | str | La contraseña de apertura del archivo de Excel. El valor puede ser nulo si no se establece ninguna contraseña.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Importa el archivo de Excel desde la secuencia de archivos.



```python
def import_excel_file(self, uid, filestream, format):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| uid | str | La identificación única para el caché de archivos, si se establece en nulo, se generará automáticamente.|
| filestream | io.RawIOBase | La secuencia del archivo de Excel.|
| format | [`GridLoadFormat`](/cells/python-net/es/aspose.cellsgridjs/gridloadformat) | El LoadFormat del archivo de Excel.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Importa el archivo de Excel desde el flujo de archivos con formato de carga y contraseña de apertura.



```python
def import_excel_file(self, filestream, format, password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| filestream | io.RawIOBase | La secuencia del archivo de Excel.|
| format | [`GridLoadFormat`](/cells/python-net/es/aspose.cellsgridjs/gridloadformat) | El LoadFormat del archivo de Excel.|
| password | str | La contraseña de apertura del archivo de Excel. El valor puede ser nulo si no se establece ninguna contraseña.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Importa el archivo de Excel desde el flujo de archivos con formato de carga y contraseña de apertura.



```python
def import_excel_file(self, uid, filestream, format, password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| uid | str | La identificación única para el caché de archivos, si se establece en nulo, se generará automáticamente.|
| filestream | io.RawIOBase | La secuencia del archivo de Excel.|
| format | [`GridLoadFormat`](/cells/python-net/es/aspose.cellsgridjs/gridloadformat) | El LoadFormat del archivo de Excel.|
| password | str | La contraseña de apertura del archivo de Excel. El valor puede ser nulo si no se establece ninguna contraseña.|



###  Ver también
* módulo [`aspose.cellsgridjs`](../../)
* clase [`GridJsWorkbook`](/cells/python-net/es/aspose.cellsgridjs/gridjsworkbook)
