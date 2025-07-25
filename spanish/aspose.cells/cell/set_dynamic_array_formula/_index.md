---
title: método set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 340
url: /es/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Establece una fórmula de matriz dinámica y hace que la fórmula se extienda a las celdas vecinas si es posible.


###  Devoluciones

el rango en el que debe extenderse la fórmula.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | la expresión de la fórmula|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.<br/> La opción "Analizar" se ignorará y la fórmula siempre se analizará inmediatamente.|
| calculate_value | bool | si calcula esta fórmula de matriz dinámica para aquellas celdas en el rango derramado.|
###  Observaciones

El rango devuelto puede no ser el mismo que el rango real en el que se vierte esta fórmula de matriz dinámica.
Si hay celdas no vacías en el rango, la fórmula se establecerá solo para la celda actual y se marcará como "#DERRAMA!".
Pero para este tipo de situaciones, todavía devolvemos todo el rango en el que debería aplicarse esta fórmula.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Establece una fórmula de matriz dinámica y hace que la fórmula se extienda a las celdas vecinas si es posible.


###  Devoluciones

el rango en el que debe extenderse la fórmula.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | la expresión de la fórmula|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.<br/> La opción "Analizar" se ignorará y la fórmula siempre se analizará inmediatamente.|
| values | list |valores (resultados calculados) para aquellas celdas con la fórmula de matriz dinámica dada|
| calculate_range | bool | Si desea calcular el rango derramado para esta fórmula de matriz dinámica.<br/>Si el parámetro "valores" no es nulo y este indicador es falso,<br/> entonces la altura del rango derramado será values.Length y el ancho serán values[0].Length.|
| calculate_value | bool | Si se calcula esta fórmula de matriz dinámica para aquellas celdas en el rango derramado cuando "valores" es nulo<br/> o el elemento correspondiente en "valores" para una celda es nulo.|
###  Observaciones

El rango devuelto puede no ser el mismo que el rango real en el que se vierte esta fórmula de matriz dinámica.
Si hay celdas no vacías en el rango, la fórmula se establecerá solo para la celda actual y se marcará como "#DERRAMA!".
Pero para este tipo de situaciones, todavía devolvemos todo el rango en el que debería aplicarse esta fórmula.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Establece una fórmula de matriz dinámica y hace que la fórmula se extienda a las celdas vecinas si es posible.


###  Devoluciones

el rango en el que debe extenderse la fórmula.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str | la expresión de la fórmula|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.<br/> La opción "Analizar" se ignorará y la fórmula siempre se analizará inmediatamente.|
| values | list |valores (resultados calculados) para aquellas celdas con la fórmula de matriz dinámica dada|
| calculate_range | bool | Si desea calcular el rango derramado para esta fórmula de matriz dinámica.<br/>Si el parámetro "valores" no es nulo y este indicador es falso,<br/> entonces la altura del rango derramado será values.Length y el ancho serán values[0].Length.|
| calculate_value | bool | Si se calcula esta fórmula de matriz dinámica para aquellas celdas en el rango derramado cuando "valores" es nulo<br/> o el elemento correspondiente en "valores" para una celda es nulo.|
| copts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Las opciones para calcular la fórmula.<br/> Comúnmente, por razones de rendimiento, la propiedad [`CalculationOptions.recursive`](/cells/python-net/es/aspose.cells/calculationoptions#recursive) debe ser falsa.|
###  Observaciones

El rango devuelto puede no ser el mismo que el rango real en el que se vierte esta fórmula de matriz dinámica.
Si hay celdas no vacías en el rango, la fórmula se establecerá solo para la celda actual y se marcará como "#DERRAMA!".
Pero para este tipo de situaciones, todavía devolvemos todo el rango en el que debería aplicarse esta fórmula.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
