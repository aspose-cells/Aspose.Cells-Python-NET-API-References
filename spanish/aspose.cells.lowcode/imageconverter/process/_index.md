---
title: método process
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, archivo_de_plantilla, archivo_de_resultados){#str-str}
Convierte archivos de plantilla en imágenes.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| template_file | str | El archivo de plantilla que se convertirá en imágenes.|
| result_file | str | El archivo resultante (patrón de nombre) para las imágenes generadas.|
###  Observaciones

Los archivos de salida se crearán a partir del archivo de resultados especificado.
añadiendo el número de secuencia de la hoja y la parte dividida.
Por ejemplo, si el archivo de salida especificado es Image.png, entonces la imagen generada
Los archivos serán Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, opciones_de_carga, opciones_de_guardado){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Convierte archivos de plantilla en imágenes



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodeloadoptions) | Opciones de entrada y carga|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions) | Opciones de salida y guardado|
###  Observaciones

Al convertir a una imagen de formato que admita varias páginas (como tiff),
el especificado [`LowCodeSaveOptions.output_file`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions#output_file)
o se utilizará directamente [`LowCodeSaveOptions.output_stream`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions#output_stream) para la imagen resultante.


Para otros tipos de imágenes, si las opciones de guardado han especificado Stream como salida,
Luego, todas las imágenes resultantes se guardarán en el mismo flujo.
De lo contrario, los archivos de salida se crearán a partir del archivo de salida especificado.
de las opciones de guardado añadiendo el número de secuencia de la hoja y la parte dividida.
Por ejemplo, si el archivo de salida especificado es Image.png, entonces la imagen generada
Los archivos serán Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, opciones_de_carga, opciones_de_guardado, proveedor){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Ver también
* módulo [`aspose.cells.lowcode`](../../)
* clase [`ImageConverter`](/cells/python-net/es/aspose.cells.lowcode/imageconverter)
