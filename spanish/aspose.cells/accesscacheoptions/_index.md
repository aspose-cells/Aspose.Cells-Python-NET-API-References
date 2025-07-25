---
title: AccessCacheOptions enumeración
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1710
url: /es/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions enumeración
Opciones de caché para acceder a los datos. Se puede combinar con el operador | para obtener varias opciones juntas.



El tipo AccessCacheOptions expone los siguientes miembros:

###  Campos
| Campo| Descripción|
| :- | :- |
| NONE | No hay caché para ningún acceso a datos.|
| ALL | Aplicar todas las optimizaciones posibles para todo tipo de acceso a datos en el libro de trabajo.<br/> No se deben modificar todas las configuraciones ni los datos durante el acceso optimizado.|
| POSITION_AND_SIZE | Aplicar la optimización posible para obtener la posición y el tamaño del objeto (por ejemplo, la forma).<br/> Los ajustes de altura de fila y ancho de columna no deben cambiarse durante el acceso optimizado.|
| CELLS_DATA | Aplicar la optimización posible para obtener los valores de las celdas.<br/>Los datos Cells (datos y configuraciones de Cell, fila) no deben cambiarse durante<br/>Para el acceso optimizado, tampoco se deben crear nuevos objetos Cell/Row (como<br/> por [indexador]).|
| CELL_DISPLAY | Aplicar la optimización posible para obtener resultados relacionados con la visualización de<br/>celdas([`Cell.display_string_value`](/cells/python-net/es/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/es/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style), etc.).<br/>Cells Los objetos relacionados con datos y estilos (Cell/Estilos de fila/columna, ancho de columna, etc.) no deben modificarse<br/> durante el acceso optimizado.|
| GET_FORMULA | Aplicar posible optimización para obtener fórmulas.<br/>Todos los datos y configuraciones que pueden afectar la expresión de la fórmula (nombre de la hoja de trabajo, texto del nombre,<br/> La columna de la tabla, etc.) no se debe cambiar durante el acceso optimizado.|
| SET_FORMULA | Aplicar posible optimización para configurar fórmulas.<br/>Todos los datos y configuraciones que pueden afectar la expresión de la fórmula (nombre de la hoja de trabajo, texto del nombre,<br/> La columna de la tabla, etc.) no se debe cambiar durante el acceso optimizado.|
| CALCULATE_FORMULA | Aplicar posible optimización para el cálculo de fórmulas.<br/>Cells no se deben cambiar los datos durante el acceso optimizado, no hay objetos nuevos (Cell, fila, etc.)<br/> debe crearse (por ejemplo, mediante [indexer]).|
| CONDITIONAL_FORMATTING | Aplicar la optimización posible para obtener el resultado de formato de formatos condicionales.<br/>Todos los datos y configuraciones que pueden afectar el resultado de los formatos condicionales (configuraciones de<br/> Los formatos condicionales, los valores de celda dependientes, etc.) no deben modificarse durante el acceso optimizado.|
| VALIDATION | Aplicar la optimización posible para obtener el resultado de la validación.<br/>Todos los datos y configuraciones que puedan afectar el resultado de la validación (configuraciones de la validación,<br/> Los valores de celdas dependientes, etc.) no deben modificarse durante el acceso optimizado.|



###  Observaciones

Para algunas funciones, acceder a grandes conjuntos de datos requiere muchas operaciones repetidas y complicadas
como búsqueda, cálculo, etc. y esas operaciones llevarán mucho tiempo extra.
En situaciones comunes, todos los datos dependientes permanecen sin cambios durante el acceso, por lo que se pueden crear y usar algunos cachés para
Mejorar el rendimiento del acceso.
Para ello ponemos a disposición del usuario este API para que pueda especificar qué tipo de acceso a datos necesita.
para ser optimizado mediante un posible mecanismo de almacenamiento en caché.


Tenga en cuenta que, para diferentes opciones, es posible que se requiera que diferentes conjuntos de datos sean de "solo lectura".
Y el rendimiento del acceso a los datos depende de muchos aspectos, como el uso del mecanismo de almacenamiento en caché.
no garantiza que el rendimiento mejore. En algunas situaciones,
Por ejemplo, si el conjunto de datos al que se va a acceder es pequeño, el uso de caché puede causar incluso más tiempo porque
El almacenamiento en caché en sí también necesita cierto tiempo adicional.

###  Ver también
* módulo [`aspose.cells`](..)
