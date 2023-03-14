---
title: Validation clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1540
url: /es/aspose.cells/validation/
is_root: false
---
##  Validation clase
Representa la validación.configuración de datos.



El tipo Validation expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [operator](/cells/python-net/es/aspose.cells/validation/operator) | Representa el operador para la validación de datos.|
| [alert_style](/cells/python-net/es/aspose.cells/validation/alert_style) | Representa el estilo de alerta de validación.|
| [type](/cells/python-net/es/aspose.cells/validation/type) | Representa el tipo de validación de datos.|
| [input_message](/cells/python-net/es/aspose.cells/validation/input_message) | Representa el mensaje de entrada de validación de datos.|
| [input_title](/cells/python-net/es/aspose.cells/validation/input_title) | Representa el título del cuadro de diálogo de entrada de validación de datos.|
| [error_message](/cells/python-net/es/aspose.cells/validation/error_message) | Representa el mensaje de error de validación de datos.|
| [error_title](/cells/python-net/es/aspose.cells/validation/error_title) | Representa el título del cuadro de diálogo de error de validación de datos.|
| [show_input](/cells/python-net/es/aspose.cells/validation/show_input) |Indica si el mensaje de entrada de validación de datos se mostrará cada vez que el usuario seleccione una celda en el rango de validación de datos.|
| [show_error](/cells/python-net/es/aspose.cells/validation/show_error) | Indica si se mostrará el mensaje de error de validación de datos cada vez que el usuario ingrese datos no válidos.|
| [ignore_blank](/cells/python-net/es/aspose.cells/validation/ignore_blank) | Indica si la validación de datos de rango permite valores en blanco.|
| [formula1](/cells/python-net/es/aspose.cells/validation/formula1) | Representa el valor o la expresión asociada con la validación de datos.|
| [formula2](/cells/python-net/es/aspose.cells/validation/formula2) | Representa el valor o la expresión asociada con la validación de datos.|
| [value1](/cells/python-net/es/aspose.cells/validation/value1) | Representa el primer valor asociado a la validación de datos.|
| [value2](/cells/python-net/es/aspose.cells/validation/value2) | Representa el segundo valor asociado a la validación de datos.|
| [in_cell_drop_down](/cells/python-net/es/aspose.cells/validation/in_cell_drop_down) | Indica si la validación de datos muestra una lista desplegable que contiene valores aceptables.|
| [areas](/cells/python-net/es/aspose.cells/validation/areas) | Obtiene todos los [CellArea](/cells/python-net/es/aspose.cells/cellarea) que contienen la configuración de validación de datos.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [get_formula1(is_r1c1, is_local)](/cells/python-net/es/aspose.cells/validation/get_formula1/#bool-bool) | Obtiene el valor o la expresión asociada a esta validación.|
| [get_formula1(is_r1c1, is_local, row, column)](/cells/python-net/es/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Obtiene el valor o la expresión asociada a esta validación para una celda específica.|
| [get_formula2(is_r1c1, is_local)](/cells/python-net/es/aspose.cells/validation/get_formula2/#bool-bool) | Obtiene el valor o la expresión asociada a esta validación.|
| [get_formula2(is_r1c1, is_local, row, column)](/cells/python-net/es/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Obtiene el valor o la expresión asociada a esta validación para una celda específica.|
| [add_area(cell_area)](/cells/python-net/es/aspose.cells/validation/add_area/#CellArea) | Aplica la validación al área.|
| [add_area(cell_area, check_intersection, check_edge)](/cells/python-net/es/aspose.cells/validation/add_area/#CellArea-bool-bool) | Aplica la validación al área.|
| [set_formula1(formula, is_r1c1, is_local)](/cells/python-net/es/aspose.cells/validation/set_formula1/#str-bool-bool) | Establece el valor o la expresión asociada a esta validación.|
| [set_formula2(formula, is_r1c1, is_local)](/cells/python-net/es/aspose.cells/validation/set_formula2/#str-bool-bool) | Establece el valor o la expresión asociada a esta validación.|
| [get_list_value(row, column)](/cells/python-net/es/aspose.cells/validation/get_list_value/#int-int) |Obtenga el valor para la lista de la validación de la celda especificada.|
| [add_areas(areas, check_intersection, check_edge)](/cells/python-net/es/aspose.cells/validation/add_areas/#list-bool-bool) | Aplica la validación a áreas dadas.|
| [remove_area(cell_area)](/cells/python-net/es/aspose.cells/validation/remove_area/#CellArea) | Quite la configuración de validación en el rango.|
| [remove_areas(areas)](/cells/python-net/es/aspose.cells/validation/remove_areas/#list) | Elimina esta validación de áreas determinadas.|
| [remove_a_cell(row, column)](/cells/python-net/es/aspose.cells/validation/remove_a_cell/#int-int) | Quite la configuración de validación en la celda.|
| [copy(source, copy_option)](/cells/python-net/es/aspose.cells/validation/copy/#Validation-CopyOptions) | Copia de validación.|



###  Ejemplo

```python
from aspose.cells import CellArea, OperatorType, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.WHOLE_NUMBER
validation.operator = OperatorType.BETWEEN
validation.formula1 = "3"
validation.formula2 = "1234"

```

###  Ver también
* módulo [aspose.cells](..)
* clase [CellArea](/cells/python-net/es/aspose.cells/cellarea)
