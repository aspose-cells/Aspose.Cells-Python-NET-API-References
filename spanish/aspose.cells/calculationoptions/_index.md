---
title: CalculationOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells/calculationoptions/
is_root: false
---
##  CalculationOptions clase
Representa opciones para el cálculo.



El tipo CalculationOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/calculationoptions/__init__/#) | Construye una nueva instancia de CalculationOptions|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [ignore_error](/cells/python-net/es/aspose.cells/calculationoptions/ignore_error) | Indica si se deben ignorar los errores encontrados al calcular fórmulas.<br/>El error puede deberse a una función no compatible, enlaces externos, etc.<br/> El valor predeterminado es verdadero.|
| [recursive](/cells/python-net/es/aspose.cells/calculationoptions/recursive) | Indica si se calculan las celdas dependientes de forma recursiva cuando se calcula una celda y depende de otras celdas.<br/> El valor predeterminado es verdadero.|
| [calc_stack_size](/cells/python-net/es/aspose.cells/calculationoptions/calc_stack_size) | Tamaño de la pila para calcular celdas recursivamente. El valor predeterminado es 200.|
| [precision_strategy](/cells/python-net/es/aspose.cells/calculationoptions/precision_strategy) | Especifica la estrategia para procesar la precisión del cálculo.|
| [linked_data_sources](/cells/python-net/es/aspose.cells/calculationoptions/linked_data_sources) | Especifica las fuentes de datos para los enlaces externos utilizados en las fórmulas.|
| [character_encoding](/cells/python-net/es/aspose.cells/calculationoptions/character_encoding) | Especifica la codificación utilizada para codificar/decodificar caracteres al calcular fórmulas.<br/>Para funciones como CHAR, CODE, el resultado calculado depende de la configuración de la región y del conjunto de caracteres predeterminado del entorno.<br/>Con esta propiedad, el usuario puede especificar la codificación adecuada utilizada para esas funciones para obtener el resultado esperado.|



###  Ver también
* módulo [`aspose.cells`](..)
