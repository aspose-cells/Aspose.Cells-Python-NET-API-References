---
title: ExternalConnection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells.externalconnections/externalconnection/
is_root: false
---
##  ExternalConnection clase
Especifica una conexión de datos externa



El tipo ExternalConnection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [id](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/id) | Obtiene el id de la conexión.|
| [power_query_formula](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/power_query_formula) | Obtiene la definición de la fórmula de consulta de potencia.|
| [type](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/type) | Obtiene o establece el tipo de origen de datos de la conexión externa.|
| [source_file](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/source_file) | Se utiliza cuando la fuente de datos externa está basada en archivos. Cuando una conexión a tales datos<br/> fuente falla, la aplicación de hoja de cálculo intenta conectarse directamente a este archivo. Tal vez<br/> expresado en URI o notación de ruta de archivo específica del sistema.|
| [sso_id](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/sso_id) | Identificador de inicio de sesión único (SSO) utilizado para la autenticación entre un intermediario<br/> servidor spreadsheetML y la fuente de datos externa.|
| [save_password](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/save_password) | True si la contraseña se guardará como parte de la cadena de conexión; de lo contrario, Falso.|
| [save_data](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/save_data) | True si se van a guardar los datos externos obtenidos a través de la conexión para completar una tabla<br/> con el libro de trabajo; en caso contrario, falso.|
| [refresh_on_load](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/refresh_on_load) | True si esta conexión debe actualizarse al abrir el archivo; en caso contrario, falso.|
| [reconnection_method_type](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/reconnection_method_type) | Especifica lo que debe hacer la aplicación de hoja de cálculo cuando falla una conexión.<br/>El valor predeterminado es ReConnectionMethodType.Required.|
| [reconnection_method](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/reconnection_method) | Especifica lo que debe hacer la aplicación de hoja de cálculo cuando falla una conexión.<br/>El valor predeterminado es ReConnectionMethodType.Required.|
| [only_use_connection_file](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/only_use_connection_file) | Indica si la aplicación de hoja de cálculo debe usar siempre y solo el<br/> información de conexión en el archivo de conexión externo indicado por el atributo odcFile<br/> cuando se actualiza la conexión. Si es falso, entonces la aplicación de hoja de cálculo<br/> debe seguir el procedimiento indicado por el atributo reconnectionMethod|
| [odc_file](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/odc_file) | Especifica la ruta completa al archivo de conexión externa desde el que se realizó esta conexión.<br/> creado. Si una conexión falla durante un intento de actualizar los datos y reconnectionMethod=1,<br/> luego, la aplicación de hoja de cálculo volverá a intentarlo utilizando la información del archivo de conexión externa<br/> en lugar del objeto de conexión incrustado en el libro de trabajo.|
| [is_new](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/is_new) | True si la conexión no se ha actualizado por primera vez; en caso contrario, falso.<br/> Este estado puede ocurrir cuando el usuario guarda el archivo antes de que termine de regresar una consulta.|
| [name](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/name) | Especifica el nombre de la conexión. Cada conexión debe tener un nombre único.|
| [keep_alive](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/keep_alive) | Verdadero cuando la aplicación de hoja de cálculo debe esforzarse por mantener la conexión<br/>abierto. Cuando es falso, la aplicación debe cerrar la conexión después de recuperar el<br/> información.|
| [refresh_internal](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/refresh_internal) | Especifica la cantidad de minutos entre actualizaciones automáticas de la conexión.|
| [connection_id](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/connection_id) | Especifica el identificador único de esta conexión.|
| [connection_description](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/connection_description) | Especifica la descripción del usuario para esta conexión.|
| [is_deleted](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/is_deleted) |Indica si se ha eliminado la conexión del libro de trabajo asociado. cierto si el<br/> la conexión ha sido eliminada; en caso contrario, falso.|
| [credentials_method_type](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/credentials_method_type) | Especifica el método de autenticación que se utilizará al establecer (o restablecer) la conexión.|
| [credentials](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/credentials) | Especifica el método de autenticación que se utilizará al establecer (o restablecer) la conexión.|
| [background_refresh](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/background_refresh) | Indica si la conexión se puede actualizar en segundo plano (asincrónicamente).<br/>true si el uso preferido de la conexión es actualizar de forma asíncrona en segundo plano;<br/> falso si el uso preferido de la conexión es actualizar sincrónicamente en primer plano.|
| [parameters](/cells/python-net/es/aspose.cells.externalconnections/externalconnection/parameters) | Obtiene [ConnectionParameterCollection](/cells/python-net/es/aspose.cells.externalconnections/connectionparametercollection) para una consulta web o ODBC.|



###  Ver también
* módulo [aspose.cells.externalconnections](..)
* clase [ConnectionParameterCollection](/cells/python-net/es/aspose.cells.externalconnections/connectionparametercollection)
