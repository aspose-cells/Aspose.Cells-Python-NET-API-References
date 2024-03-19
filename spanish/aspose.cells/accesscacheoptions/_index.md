---
title: AccessCacheOptions enumeración
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1810
url: /es/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions enumeración
Opciones de caché para acceso a datos. Se puede combinar con | operador para múltiples opciones juntas.



El tipo AccessCacheOptions expone los siguientes miembros:

###  Campos
| Campo| Descripción|
| :- | :- |
| NONE | Sin caché para ningún acceso a datos.|
| ALL | Aplique todas las optimizaciones posibles para todo tipo de acceso a datos en el libro de trabajo.<br/> Todas las configuraciones y datos no deben cambiarse durante el acceso optimizado.|
| POSITION_AND_SIZE |Aplique una posible optimización para obtener la posición y el tamaño del objeto (como la forma).<br/> La configuración de alto de fila y ancho de columna no debe cambiarse durante el acceso optimizado.|
| CELLS_DATA | Aplicar posible optimización para obtener los valores de las celdas.<br/>Los datos Cells (datos y configuraciones de Cell, fila) no deben cambiarse durante<br/>Para el acceso optimizado, tampoco se deben crear nuevos objetos Cell/Row (como<br/> por [indexador]).|
| CELL_DISPLAY | Aplicar posible optimización para obtener resultados relacionados con la visualización de<br/>celdas ([`Cell.display_string_value`](/cells/python-net/es/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/es/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style), etc.).<br/>Cells los datos y los objetos relacionados con el estilo (Cell/estilos de fila/columna, ancho de columna, etc.) no deben modificarse<br/> durante el acceso optimizado.|
| GET_FORMULA | Aplicar posibles optimizaciones para la obtención de fórmulas.<br/>Todos los datos y configuraciones que pueden afectar la expresión de la fórmula (nombre de la hoja de trabajo, texto del nombre,<br/> columna de la tabla, etc.) no deben modificarse durante el acceso optimizado.|
| SET_FORMULA |Aplicar posibles optimizaciones para establecer fórmulas.<br/>Todos los datos y configuraciones que pueden afectar la expresión de la fórmula (nombre de la hoja de trabajo, texto del nombre,<br/> columna de la tabla, etc.) no deben modificarse durante el acceso optimizado.|
| CALCULATE_FORMULA | Aplicar posibles optimizaciones para el cálculo de fórmulas.<br/>Cells los datos no deben cambiarse durante el acceso optimizado, ningún objeto nuevo (Cell, Fila, etc.)<br/> debe crearse (como por [indexador]).|
| CONDITIONAL_FORMATTING | Aplique la posible optimización para obtener el resultado del formato de los formatos condicionales.<br/>Todos los datos y configuraciones que puedan afectar el resultado de los formatos condicionales (configuraciones de<br/> formatos condicionales, valores de celda dependientes, etc.) no deben cambiarse durante el acceso optimizado.|
| VALIDATION | Aplique la posible optimización para obtener el resultado de la validación.<br/>Todos los datos y configuraciones que puedan afectar el resultado de la validación(configuraciones de la validación,<br/> valores de celda dependientes, etc.) no deben modificarse durante el acceso optimizado.|



###  Observaciones

Para algunas funciones, acceder a un gran conjunto de datos requiere muchas operaciones repetidas y complicadas.
como búsqueda, cálculo, etc. y esas operaciones tomarán mucho tiempo extra.
Para situaciones comunes, todos los datos dependientes permanecen sin cambios durante el acceso, por lo que algunos cachés se pueden crear y utilizar para
mejorar el rendimiento del acceso.
Para ello facilitamos este API para que el usuario pueda especificar qué tipo de datos necesita acceder
optimizarse mediante un posible mecanismo de almacenamiento en caché.


Tenga en cuenta que, para diferentes opciones, es posible que se requiera que un conjunto de datos diferente sea de "solo lectura".
Y el rendimiento del acceso a los datos depende de muchos aspectos, el uso del mecanismo de almacenamiento en caché
no garantiza que el rendimiento mejorará. Para algunas situaciones,
Por ejemplo, el conjunto de datos al que se accede es pequeño, el uso de la memoria caché puede requerir aún más tiempo porque
El almacenamiento en caché en sí también necesita cierto tiempo adicional.

###  Ver también
* módulo [`aspose.cells`](..)
