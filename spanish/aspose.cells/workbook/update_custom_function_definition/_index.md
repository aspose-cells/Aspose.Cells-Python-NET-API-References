---
title: método update_custom_function_definition
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 410
url: /es/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition {#aspose.cells.CustomFunctionDefinition}
Actualiza la definición de funciones personalizadas.



```python
def update_custom_function_definition(self, definition):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/es/aspose.cells/customfunctiondefinition) |Definición especial de funciones personalizadas para requisitos especiales del usuario.|
###  Observaciones

Este método se puede utilizar para algunos escenarios especiales. Por ejemplo, si el usuario necesita algunos parámetros
de algunas funciones personalizadas se calculan en modo de matriz, luego el usuario puede proporcionar su propia definición con implementadas
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/es/aspose.cells/customfunctiondefinition/get_array_mode_parameters) para esas funciones.
Después de actualizar los datos de las fórmulas, los parámetros especificados se calcularán automáticamente en modo matriz.
al calcular las funciones personalizadas correspondientes.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
