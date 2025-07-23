---
title: FormatConditionType enumeración
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 2110
url: /es/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType enumeración
Tipo de regla de formato condicional.



El tipo FormatConditionType expone los siguientes miembros:

###  Campos
| Campo| Descripción|
| :- | :- |
| CELL_VALUE | Esta regla de formato condicional compara un valor de celda<br/> a un resultado calculado mediante una fórmula, utilizando un operador.|
| EXPRESSION | Esta regla de formato condicional contiene una fórmula para<br/>evaluar. Cuando el resultado de la fórmula es verdadero, la celda es<br/> resaltado.|
| TOP10 | Esta regla de formato condicional resalta las celdas cuyas<br/>los valores caen en el corchete N superior o N inferior, como<br/> especificado.|
| UNIQUE_VALUES | Esta regla de formato condicional resalta lo único<br/> valores en el rango.|
| DUPLICATE_VALUES | Esta regla de formato condicional resalta los duplicados<br/> valores.|
| CONTAINS_TEXT | Esta regla de formato condicional resalta las celdas<br/>Contiene el texto dado. Equivalente a usar SEARCH()<br/>Función de hoja para determinar si la celda contiene<br/> el texto.|
| NOT_CONTAINS_TEXT | Esta regla de formato condicional resalta las celdas que<br/>No contiene el texto dado. Equivalente a usar SEARCH()<br/>Función de hoja para determinar si la celda contiene<br/> el texto o no.|
| BEGINS_WITH | Esta regla de formato condicional resalta las celdas en el<br/>rango que comienza con el texto dado. Equivalente a<br/> utilizando la función de hoja LEFT() y comparando valores.|
| ENDS_WITH | Esta regla de formato condicional resalta las celdas que terminan<br/>Con el texto dado. Equivalente a usar la hoja RIGHT()<br/> Función y comparación de valores.|
| CONTAINS_BLANKS | Esta regla de formato condicional resalta las celdas que<br/>están completamente en blanco. Equivalente a usar LEN(TRIM()).<br/>Esto significa que si la celda contiene sólo caracteres<br/>que TRIM() eliminaría, entonces se considera en blanco.<br/> Una celda vacía también se considera en blanco.|
| NOT_CONTAINS_BLANKS | Esta regla de formato condicional resalta las celdas que<br/>no están en blanco. Equivalente a usar LEN(TRIM()). Esto<br/>significa que si la celda contiene solo caracteres que<br/>TRIM() lo eliminaría, entonces se consideraría en blanco. Un<br/> La celda vacía también se considera en blanco.|
| CONTAINS_ERRORS | Esta regla de formato condicional resalta las celdas con<br/>Errores de fórmula. Equivalente a usar la hoja ISERROR().<br/> Función para determinar si hay un error de fórmula.|
| NOT_CONTAINS_ERRORS | Esta regla de formato condicional resalta las celdas<br/>Sin errores de fórmula. Equivalente a usar ISERROR()<br/> Función de hoja para determinar si hay un error de fórmula.|
| TIME_PERIOD | Esta regla de formato condicional resalta las celdas<br/>que contiene fechas en el período de tiempo especificado. El<br/>Se evalúa el valor subyacente de la celda, por lo tanto<br/>No es necesario formatear la celda como una fecha para que sea válida.<br/>evaluado. Por ejemplo, con una celda que contiene el<br/>valor 38913 se aplicará el formato condicional si<br/> La regla requiere un valor de 14/07/2006.|
| ABOVE_AVERAGE | Esta regla de formato condicional resalta las celdas que<br/>están por encima o por debajo del promedio para todos los valores en el<br/> rango.|
| COLOR_SCALE | Esta regla de formato condicional crea un degradado<br/> escala de colores en las celdas.|
| DATA_BAR | Esta regla de formato condicional muestra una gradación<br/> barra de datos en el rango de celdas.|
| ICON_SET |Esta regla de formato condicional aplica íconos a las celdas<br/> según sus valores.|



###  Ver también
* módulo [`aspose.cells`](..)
