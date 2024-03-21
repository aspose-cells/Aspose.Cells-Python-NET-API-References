---
title: método convert_formula_reference_style
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style {#str-bool-int-int}
Convierte el estilo de referencia de la fórmula.


###  Devoluciones

La fórmula convertida.


```python
def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | La fórmula a convertir.|
| to_r1c1 | bool | A qué estilo de referencia convertir la fórmula.<br/>Si la fórmula original es de estilo de referencia A1,<br/>entonces este valor debe ser verdadero para que la fórmula se convierta del estilo de referencia A1 al estilo de referencia R1C1;<br/>Si la fórmula original es del estilo de referencia R1C1,<br/> entonces este valor debe ser falso para que la fórmula se convierta del estilo de referencia R1C1 al estilo de referencia A1;|
| base_cell_row | int | El índice de fila de la celda base.|
| base_cell_column | int | El índice de columna de la celda base.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
