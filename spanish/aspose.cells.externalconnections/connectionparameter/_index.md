---
title: ConnectionParameter clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter clase
Especifica propiedades sobre cualquier parámetro utilizado con conexiones de datos externas
Los parámetros son válidos para consultas ODBC y web.



El tipo ConnectionParameter expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [sql_type](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/sql_type) | Tipo de dato SQL del parámetro. Válido solo para orígenes ODBC.|
| [refresh_on_change](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Bandera que indica si la consulta debe actualizarse automáticamente cuando se actualiza el contenido de una<br/> La celda que proporciona el valor del parámetro cambia. Si es verdadero, se actualizan los datos externos.<br/> Usando el nuevo valor del parámetro cada vez que hay un cambio. Si es falso, entonces los datos externos...<br/> sólo se actualiza cuando lo solicita el usuario o algún otro evento activa la actualización (por ejemplo, cuando se abre un libro).|
| [prompt](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/prompt) | Cadena de solicitud para el parámetro. Se presenta al usuario de la hoja de cálculo junto con la interfaz de usuario de entrada.<br/> Para recopilar el valor del parámetro antes de actualizar los datos externos. Se utiliza solo cuando<br/>tipoDeParámetro = prompt.|
| [type](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/type) | Tipo de parámetro utilizado.<br/> Si el tipo de parámetro=valor, entonces el valor puede ser booleano, doble, entero,<br/> o se utilizará una cadena. En este caso, se espera que solo uno de<br/> Se especificará {booleano, doble, entero o cadena}.|
| [name](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/name) | El nombre del parámetro.|
| [cell_reference](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/cell_reference) | Referencia Cell que indica el valor de la celda que se usará para el parámetro de consulta. Solo se usa cuando el parámetroType es celda.|
| [value](/cells/python-net/es/aspose.cells.externalconnections/connectionparameter/value) | Valor numérico no entero, valor entero, valor de cadena o valor booleano<br/> Para usar como parámetro de consulta. Se usa solo cuando `parameterType` es `value`.|



###  Ver también
* módulo [`aspose.cells.externalconnections`](..)
