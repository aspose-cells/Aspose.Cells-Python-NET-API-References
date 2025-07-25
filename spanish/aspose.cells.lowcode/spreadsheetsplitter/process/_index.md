---
title: método process
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, opciones){#aspose.cells.lowcode.LowCodeSplitOptions}
Divide el archivo de hoja de cálculo en varias partes.



```python

@staticmethod
def process(options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/es/aspose.cells.lowcode/lowcodesplitoptions) | Opciones para dividir la hoja de cálculo|


##  process(, archivo_de_plantilla, archivo_de_resultados){#str-str}
Divide el archivo de plantilla dado en varias partes.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| template_file | str | El archivo de plantilla que se va a dividir|
| result_file | str | El archivo resultante (nombre patrón)|
###  Observaciones

Los archivos de salida se crearán a partir del archivo resultante especificado por
añadiendo número de secuencia de la hoja y parte dividida.
Por ejemplo, si el archivo de salida especificado es Split.xlsx, entonces el archivo generado
Los archivos serán Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


###  Ver también
* módulo [`aspose.cells.lowcode`](../../)
* clase [`SpreadsheetSplitter`](/cells/python-net/es/aspose.cells.lowcode/spreadsheetsplitter)
