---
title: PivotItem clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem clase
Representa un elemento en un informe de campo dinámico.



El tipo PivotItem expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_hidden](/cells/python-net/es/aspose.cells.pivot/pivotitem/is_hidden) | Obtiene y establece si el elemento pivote está oculto.|
| [position](/cells/python-net/es/aspose.cells.pivot/pivotitem/position) | Especificar el índice de posición en todos los elementos dinámicos, no en los elementos dinámicos bajo el mismo nodo principal.|
| [position_in_same_parent_node](/cells/python-net/es/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Especificar el índice de posición en los elementos dinámicos bajo el mismo nodo principal.|
| [is_hide_detail](/cells/python-net/es/aspose.cells.pivot/pivotitem/is_hide_detail) | Obtiene y establece si el elemento pivote oculta los detalles.|
| [is_detail_hidden](/cells/python-net/es/aspose.cells.pivot/pivotitem/is_detail_hidden) |Obtiene y establece si el detalle de este elemento pivote está oculto.|
| [is_calculated_item](/cells/python-net/es/aspose.cells.pivot/pivotitem/is_calculated_item) | Indica si este elemento pivote es un elemento de fórmula calculado.|
| [is_formula](/cells/python-net/es/aspose.cells.pivot/pivotitem/is_formula) | Indica si este elemento pivote es un elemento de fórmula calculado.|
| [is_missing](/cells/python-net/es/aspose.cells.pivot/pivotitem/is_missing) | Indica si el elemento se elimina de la fuente de datos.|
| [value](/cells/python-net/es/aspose.cells.pivot/pivotitem/value) | Obtiene el valor del elemento pivote|
| [name](/cells/python-net/es/aspose.cells.pivot/pivotitem/name) | Obtiene el nombre del elemento pivote.|
| [index](/cells/python-net/es/aspose.cells.pivot/pivotitem/index) | Obtiene el índice del elemento pivote en el campo de caché.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/es/aspose.cells.pivot/pivotitem/move/#int-bool) | Mueve el elemento hacia arriba o hacia abajo|
| [`get_formula(self)`](/cells/python-net/es/aspose.cells.pivot/pivotitem/get_formula/#) | Obtiene la fórmula de este elemento calculado.<br/> Sólo funciona cuando este elemento es un elemento calculado.|
| [`get_string_value(self)`](/cells/python-net/es/aspose.cells.pivot/pivotitem/get_string_value/#) | Obtiene el valor de la cadena del elemento pivote<br/> Si el valor es nulo, devolverá ""|
| [`get_double_value(self)`](/cells/python-net/es/aspose.cells.pivot/pivotitem/get_double_value/#) | Obtiene el valor doble del elemento pivote<br/> Si el valor es nulo o no es un número, devolverá 0|
| [`get_date_time_value(self)`](/cells/python-net/es/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Obtiene el valor de fecha y hora del elemento pivote<br/> Si el valor es nulo, devolverá DateTime.MinValue|



###  Ver también
* módulo [`aspose.cells.pivot`](..)
