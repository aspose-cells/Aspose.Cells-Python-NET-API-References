---
title: AbstractCalculationEngine clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine clase
Representa el motor de cálculo personalizado del usuario para ampliar el motor de cálculo predeterminado de Aspose.Cells.



El tipo AbstractCalculationEngine expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_param_literal_required](/cells/python-net/es/aspose.cells/abstractcalculationengine/is_param_literal_required) |Indica si este motor necesita el texto literal del parámetro mientras realiza el cálculo. El valor predeterminado es falso.|
| [is_param_array_mode_required](/cells/python-net/es/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Indica si este motor necesita que el parámetro se calcule en modo matriz. El valor predeterminado es falso.<br/>Si se requiere [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/es/aspose.cells/calculationdata/get_param_value_in_array_mode) al calcular el valor personalizado<br/>funciones y el usuario no ha actualizado la definición para ellas<br/>(por [`Workbook.update_custom_function_definition`](/cells/python-net/es/aspose.cells/workbook/update_custom_function_definition)),<br/> esta propiedad debe establecerse como verdadera.|
| [process_built_in_functions](/cells/python-net/es/aspose.cells/abstractcalculationengine/process_built_in_functions) | Si las funciones integradas que han sido compatibles con el motor integrado<br/>debe ser verificado y procesado por esta implementación.<br/> El valor predeterminado es falso.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [calculate](/cells/python-net/es/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Calcula una función con datos dados.|



###  Observaciones

El usuario no debe modificar ninguna parte del Libro de trabajo directamente en esta implementación (excepto
el resultado calculado de la función personalizada, que se puede establecer mediante la propiedad CalculationData.CalculatedValue).
De lo contrario, se pueden producir resultados inesperados o excepciones.
Si el usuario necesita cambiar otros datos además del resultado calculado en la implementación de algunas funciones personalizadas,
por ejemplo, cambiar la fórmula, el estilo, etc. de la celda, el usuario debe recopilar esos datos en esta implementación
y cámbielos fuera del alcance del cálculo de la fórmula.

###  Ver también
* módulo [`aspose.cells`](..)
