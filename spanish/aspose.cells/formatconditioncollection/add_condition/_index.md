---
title: método add_condition
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Añadir una condición de formato.


###  Devoluciones

Índice de objeto de condición de formato;


```python

def add_condition(self, type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/es/aspose.cells/formatconditiontype) | Tipo de condición de formato.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Agrega una condición de formato.


###  Devoluciones

Índice de objeto de condición de formato;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/es/aspose.cells/formatconditiontype) | El tipo de condición de formato.|
| operator_type | [`OperatorType`](/cells/python-net/es/aspose.cells/operatortype) | El tipo de operador|
| formula1 | str | El valor o la expresión asociada con el formato condicional.<br/>Si el valor de entrada comienza con '=', entonces se tomará como fórmula.<br/>De lo contrario, se tomará como valor simple (texto, número, bool).<br/> Para un valor de texto que comienza con '=', el usuario puede ingresarlo como fórmula en el formato: "=\"=...\"".|
| formula2 | str | El valor o la expresión asociada con el formato condicional.<br/> El formato de entrada es el mismo que el de la fórmula 1.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FormatConditionCollection`](/cells/python-net/es/aspose.cells/formatconditioncollection)
