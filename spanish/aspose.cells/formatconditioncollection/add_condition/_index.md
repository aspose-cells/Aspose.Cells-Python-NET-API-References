---
title: add_condition método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(type) {#FormatConditionType}
Agregue una condición de formato.


###  Devoluciones

Índice de objeto de condición de formato;


```python
def add_condition(self, type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [FormatConditionType](/cells/python-net/es/aspose.cells/formatconditiontype) | Tipo de condición de formato.|


##  add_condition(type, operator_type, formula1, formula2) {#FormatConditionType-OperatorType-str-str}
Agrega una condición de formato.


###  Devoluciones

Índice de objeto de condición de formato;


```python
def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [FormatConditionType](/cells/python-net/es/aspose.cells/formatconditiontype) | [FormatConditionType](/cells/python-net/es/aspose.cells/formatconditiontype) de formato condicional.<br/> Podría ser uno de los miembros de FormatConditionType.|
| operator_type | [OperatorType](/cells/python-net/es/aspose.cells/operatortype) | La comparación [OperatorType](/cells/python-net/es/aspose.cells/operatortype).<br/> Podría ser uno de los miembros de OperatorType.|
| formula1 | str | El valor o la expresión asociada con el formato condicional.<br/>Si el valor de entrada comienza con '=', se tomará como fórmula.<br/>De lo contrario, se tomará como valor simple (texto, número, bool).<br/> Para el valor de texto que comienza con '=', el usuario puede ingresarlo como fórmula en formato: "=\"=...\"".|
| formula2 | str | El valor o la expresión asociada con el formato condicional.<br/>El formato de entrada es el mismo con formula1|



###  Ver también
* módulo [aspose.cells](../../)
* clase [FormatConditionCollection](/cells/python-net/es/aspose.cells/formatconditioncollection)
* clase [FormatConditionType](/cells/python-net/es/aspose.cells/formatconditiontype)
* clase [OperatorType](/cells/python-net/es/aspose.cells/operatortype)
