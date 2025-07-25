---
title: trim_leading_blank_row_and_column propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 230
url: /es/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column propiedad

Indica si las filas y columnas en blanco iniciales deben recortarse como lo hace MS Excel.
El valor predeterminado es verdadero.

###  Observaciones

Lo mismo ocurre con la regla en MS Excel: una fila o columna no se considerará en blanco si tiene un estilo personalizado.
incluso si no contiene datos de celda.
Al guardar con el modo LightCells, esta opción no tiene efecto.
El usuario debe controlar el rango de salida mediante la implementación de [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/es/aspose.cells/txtsaveoptions)
o especificando [`TxtSaveOptions.export_area`](/cells/python-net/es/aspose.cells/txtsaveoptions#export_area)
###  Definición:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`TxtSaveOptions`](/cells/python-net/es/aspose.cells/txtsaveoptions)
