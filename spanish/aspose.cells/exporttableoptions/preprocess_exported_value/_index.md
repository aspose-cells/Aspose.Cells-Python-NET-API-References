---
title: método preprocess_exported_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
Preprocese el valor de la celda actual que se va a exportar.


###  Devoluciones

Si la celda actual ha sido reemplazada por un tipo y/o valor diferente.


```python
def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_row | int | el índice de fila de la celda actual|
| cell_column | int | el índice de columna de la celda|
| value | [`CellValue`](/cells/python-net/es/aspose.cells/cellvalue) | valor y tipo de celda actual|
###  Observaciones

El índice de filas y columnas es el índice absoluto de la celda en la hoja de trabajo, no el índice en la tabla exportada.
El usuario puede verificar el valor de la celda actual en la implementación de anulación de este método,
si la celda actual necesita ser reemplazada por otro tipo y valor,
aquí la implementación debe establecer el tipo y valor esperado para el objeto CellValue y devolver verdadero.
Por defecto, este método no hace nada y devuelve falso.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ExportTableOptions`](/cells/python-net/es/aspose.cells/exporttableoptions)
