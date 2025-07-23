---
title: método preprocess_exported_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value(self, cell_row, cell_column, value) {#int-int-aspose.cells.CellValue}
Preprocesar el valor de la celda actual que se va a exportar.


###  Devoluciones

Si la celda actual ha sido reemplazada por un tipo y/o valor diferente.


```python

def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_row | int | el índice de fila de la celda actual|
| cell_column | int | el índice de la columna de la celda|
| value | [`CellValue`](/cells/python-net/es/aspose.cells/cellvalue) | valor y tipo de celda actual|
###  Observaciones

El índice de fila y columna es el índice absoluto de la celda en la hoja de cálculo, no el índice en la tabla exportada.
El usuario puede verificar el valor de la celda actual en la implementación de anulación de este método.
Si es necesario reemplazar la celda actual por otro tipo y valor,
Aquí la implementación debe establecer el tipo y valor esperados en el objeto CellValue y devolver verdadero.
De forma predeterminada, este método no hace nada y devuelve falso.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ExportTableOptions`](/cells/python-net/es/aspose.cells/exporttableoptions)
