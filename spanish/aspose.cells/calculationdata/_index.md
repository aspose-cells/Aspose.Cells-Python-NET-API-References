---
title: CalculationData clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells/calculationdata/
is_root: false
---
##  CalculationData clase
Representa los datos requeridos al calcular una función, como el nombre de la función, parámetros, etc.



El tipo CalculationData expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [calculated_value](/cells/python-net/es/aspose.cells/calculationdata/calculated_value) | Obtiene o establece el valor calculado para esta función.|
| [workbook](/cells/python-net/es/aspose.cells/calculationdata/workbook) | Obtiene el objeto Libro de trabajo donde se encuentra la función.|
| [worksheet](/cells/python-net/es/aspose.cells/calculationdata/worksheet) | Obtiene el objeto Hoja de trabajo donde se encuentra la función.|
| [cell_row](/cells/python-net/es/aspose.cells/calculationdata/cell_row) | Obtiene el índice de fila de la celda donde se encuentra la función.|
| [cell_column](/cells/python-net/es/aspose.cells/calculationdata/cell_column) | Obtiene el índice de columna de la celda donde se encuentra la función.|
| [cell](/cells/python-net/es/aspose.cells/calculationdata/cell) | Obtiene el objeto Cell donde se encuentra la función.|
| [function_name](/cells/python-net/es/aspose.cells/calculationdata/function_name) |Obtiene el nombre de la función que se va a calcular.|
| [param_count](/cells/python-net/es/aspose.cells/calculationdata/param_count) | Obtiene el recuento de parámetros.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [get_param_value](/cells/python-net/es/aspose.cells/calculationdata/get_param_value/#int) | Obtiene el objeto de valor representado del parámetro en el índice dado.|
| [get_param_value_in_array_mode](/cells/python-net/es/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | Obtiene los valores del parámetro en el índice dado.<br/>Si el parámetro es algún tipo de expresión que debe calcularse,<br/> luego se calculará en modo matriz.|
| [get_param_text](/cells/python-net/es/aspose.cells/calculationdata/get_param_text/#int) | Obtiene el texto literal del parámetro en el índice dado.|



###  Observaciones

Todos los objetos proporcionados por esta clase son sólo para fines de "lectura".
El usuario no debe cambiar ningún dato en el Libro de trabajo durante el proceso de cálculo de la fórmula.
De lo contrario, se pueden producir resultados inesperados o excepciones.

###  Ver también
* módulo [`aspose.cells`](..)
