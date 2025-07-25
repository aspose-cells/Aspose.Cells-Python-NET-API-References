---
title: método process
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, opciones_de_carga, opciones_de_guardado, proveedor){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Bloquea el archivo de hoja de cálculo con la configuración especificada.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodeloadoptions) | Opciones de entrada y carga|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions) | Opciones de salida y guardado|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/es/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Implementación para proporcionar configuraciones de protección|


##  process(, archivo_de_plantilla, archivo_de_resultado, contraseña_de_apertura, contraseña_de_escritura){#str-str-str-str}
Bloquea el archivo de hoja de cálculo con la configuración especificada.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| template_file | str | El archivo de plantilla que se va a bloquear|
| result_file | str | El archivo resultante|
| open_password | str | Contraseña para el cifrado de archivos|
| write_password | str |Contraseña para proteger la modificación de la hoja de cálculo|


##  process(, opciones_de_carga, opciones_de_guardado, contraseña_de_apertura, contraseña_de_escritura){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Bloquea el archivo de hoja de cálculo con la configuración especificada.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodeloadoptions) | Opciones de entrada y carga|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions) | Opciones de salida y guardado|
| open_password | str | Contraseña para el cifrado de archivos|
| write_password | str |Contraseña para proteger la modificación de la hoja de cálculo|


##  process(, opciones_de_carga, opciones_de_guardado, contraseña_de_apertura, contraseña_de_escritura, contraseña_de_libro, tipo_de_libro){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Bloquea el archivo de hoja de cálculo con la configuración especificada.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodeloadoptions) | Opciones de entrada y carga|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions) | Opciones de salida y guardado|
| open_password | str | Contraseña para el cifrado de archivos|
| write_password | str |Contraseña para proteger la modificación de la hoja de cálculo|
| workbook_password | str | Contraseña para proteger el libro de trabajo|
| workbook_type | [`ProtectionType`](/cells/python-net/es/aspose.cells/protectiontype) | Tipo de protección para proteger el libro de trabajo|



###  Ver también
* módulo [`aspose.cells.lowcode`](../../)
* clase [`SpreadsheetLocker`](/cells/python-net/es/aspose.cells.lowcode/spreadsheetlocker)
