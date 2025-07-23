---
title: método set_array_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 320
url: /es/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
Establece una fórmula de matriz (fórmula de matriz heredada ingresada mediante CTRL+MAYÚS+ENTRAR en MS Excel) en un rango de celdas.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para rellenar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para rellenar el resultado de la fórmula matricial.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
Establece una fórmula de matriz en un rango de celdas.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para rellenar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para rellenar el resultado de la fórmula matricial.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Establece una fórmula de matriz en un rango de celdas.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para rellenar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para rellenar el resultado de la fórmula matricial.|
| is_r1c1 | bool | si la fórmula es la fórmula R1C1|
| is_local | bool | si la fórmula está formateada según la configuración regional|
###  Observaciones

NOTA: Esta clase ya no está disponible. En su lugar,
utilice Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Esta propiedad será eliminada 12 meses después desde diciembre de 2019.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Establece una fórmula de matriz en un rango de celdas.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | Fórmula matricial.|
| row_number | int | Número de filas para rellenar el resultado de la fórmula matricial.|
| column_number | int | Número de columnas para rellenar el resultado de la fórmula matricial.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|
| values | list | Valores para aquellas celdas con la fórmula de matriz dada|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
