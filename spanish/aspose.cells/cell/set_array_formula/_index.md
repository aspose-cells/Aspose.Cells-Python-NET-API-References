---
title: método set_array_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 310
url: /es/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Establece una fórmula matricial (fórmula matricial heredada ingresada mediante CTRL+MAYÚS+ENTRAR en ms excel) en un rango de celdas.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para completar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para completar el resultado de la fórmula matricial.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Establece una fórmula matricial para un rango de celdas.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para completar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para completar el resultado de la fórmula matricial.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|


##  set_array_formula {#str-int-int-bool-bool}
Establece una fórmula matricial para un rango de celdas.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para completar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para completar el resultado de la fórmula matricial.|
| is_r1c1 | bool | si la fórmula es la fórmula R1C1|
| is_local | bool | si la fórmula tiene formato local|
###  Observaciones

NOTA: Esta clase ahora está obsoleta. En cambio,
utilice Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Esta propiedad será eliminada 12 meses después desde diciembre de 2019.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Establece una fórmula matricial para un rango de celdas.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para completar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para completar el resultado de la fórmula matricial.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|
| values | list | valores para aquellas celdas con una fórmula matricial dada|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
