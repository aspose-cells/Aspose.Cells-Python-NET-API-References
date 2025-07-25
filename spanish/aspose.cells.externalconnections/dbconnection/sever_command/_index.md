---
title: sever_command propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 300
url: /es/aspose.cells.externalconnections/dbconnection/sever_command/
is_root: false
---
##  sever_command propiedad

 Especifica una segunda cadena de texto de comando que se conserva cuando se ejecuta una tabla dinámica basada en servidor.
 Los campos de página están en uso.
 Para las conexiones ODBC, serverCommand suele ser una consulta más amplia que command (no
La cláusula WHERE está presente en el primero. Basándose en estos dos comandos (Command y ServerCommand),
Se pueden rellenar los parámetros de la interfaz de usuario y construir consultas parametrizadas

###  Observaciones

 NOTA: Esta propiedad ya no está disponible. En su lugar,
Utilice la propiedad ExternalConnection.SecondCommand.
 Este método se eliminará 12 meses después, a partir de octubre de 2024.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.
###  Definición:
```python
@property
def sever_command(self):
    ...
@sever_command.setter
def sever_command(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.externalconnections`](../../)
* clase [`DBConnection`](/cells/python-net/es/aspose.cells.externalconnections/dbconnection)
