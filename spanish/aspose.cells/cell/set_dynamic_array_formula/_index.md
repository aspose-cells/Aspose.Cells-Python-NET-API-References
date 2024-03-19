---
title: método set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 330
url: /es/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
Establece una fórmula de matriz dinámica y, si es posible, hace que la fórmula se extienda a las celdas vecinas.


###  Devoluciones

el rango en el que debe extenderse la fórmula.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str |la expresión de la fórmula|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | opciones para analizar la fórmula.<br/> La opción "Analizar" se ignorará y la fórmula siempre se analizará inmediatamente|
| calculate_value | bool | si calcula esta fórmula de matriz dinámica para aquellas celdas en el rango extendido.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Establece una fórmula de matriz dinámica y, si es posible, hace que la fórmula se extienda a las celdas vecinas.


###  Devoluciones

el rango en el que debe extenderse la fórmula.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str |la expresión de la fórmula|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | opciones para analizar la fórmula.<br/> La opción "Analizar" se ignorará y la fórmula siempre se analizará inmediatamente|
| values | list | valores (resultados calculados) para aquellas celdas con una fórmula de matriz dinámica dada|
| calculate_range | bool | Si se calcula el rango derramado para esta fórmula de matriz dinámica.<br/>Si el parámetro "valores" no es nulo y este indicador es falso,<br/> entonces la altura del rango derramado será valores. La longitud y el ancho serán valores [0].|
| calculate_value | bool | si se calcula esta fórmula de matriz dinámica para aquellas celdas en el rango extendido cuando los "valores" son nulos<br/> o el elemento correspondiente en "valores" para una celda es nulo.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Establece una fórmula de matriz dinámica y, si es posible, hace que la fórmula se extienda a las celdas vecinas.


###  Devoluciones

el rango en el que debe extenderse la fórmula.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| array_formula | str |la expresión de la fórmula|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | opciones para analizar la fórmula.<br/> La opción "Analizar" se ignorará y la fórmula siempre se analizará inmediatamente|
| values | list | valores (resultados calculados) para aquellas celdas con una fórmula de matriz dinámica dada|
| calculate_range | bool | Si se calcula el rango derramado para esta fórmula de matriz dinámica.<br/>Si el parámetro "valores" no es nulo y este indicador es falso,<br/> entonces la altura del rango derramado será valores. La longitud y el ancho serán valores [0].|
| calculate_value | bool | si se calcula esta fórmula de matriz dinámica para aquellas celdas en el rango extendido cuando los "valores" son nulos<br/> o el elemento correspondiente en "valores" para una celda es nulo.|
| copts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Las opciones para calcular la fórmula.<br/> Normalmente, para considerar el rendimiento, la propiedad [`CalculationOptions.recursive`](/cells/python-net/es/aspose.cells/calculationoptions#recursive) debe ser falsa.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
