---
title: método set_shared_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 350
url: /es/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula {#str-int-int}
Establece fórmulas compartidas para un rango de celdas.



```python
def set_shared_formula(self, shared_formula, row_number, column_number):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| shared_formula | str | Fórmula compartida.|
| row_number | int | Número de filas para completar la fórmula.|
| column_number | int | Número de columnas para completar la fórmula.|
###  Observaciones



##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions}

Establece fórmulas compartidas para un rango de celdas.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| shared_formula | str | Fórmula compartida.|
| row_number | int | Número de filas para completar la fórmula.|
| column_number | int | Número de columnas para completar la fórmula.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|


##  set_shared_formula {#str-int-int-bool-bool}
Establece una fórmula para un rango de celdas.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| shared_formula | str | Fórmula compartida.|
| row_number | int | Número de filas para completar la fórmula.|
| column_number | int | Número de columnas para completar la fórmula.|
| is_r1c1 | bool | si la fórmula es la fórmula R1C1|
| is_local | bool | si la fórmula tiene formato local|
###  Observaciones

NOTA: Esta clase ahora está obsoleta. En cambio,
utilice Cell.SetSharedFormula(string,int,int,FormulaParseOptions).
Esta propiedad será eliminada 12 meses después desde diciembre de 2019.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.

##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Establece fórmulas compartidas para un rango de celdas.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options, values):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| shared_formula | str | Fórmula compartida.|
| row_number | int | Número de filas para completar la fórmula.|
| column_number | int | Número de columnas para completar la fórmula.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|
| values | list | valores para aquellas celdas con una fórmula compartida dada|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
