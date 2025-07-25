---
title: ReConnectionMethodType enumeración
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
##  ReConnectionMethodType enumeración
Especifica qué debe hacer la aplicación de hoja de cálculo cuando falla una conexión.



El tipo ReConnectionMethodType expone los siguientes miembros:

###  Campos
| Campo| Descripción|
| :- | :- |
| REQUIRED | Al actualizar, utilice la información de conexión existente y, si resulta ser inválida,<br/> luego obtenga información de conexión actualizada, si está disponible en el archivo de conexión externa.|
| ALWAYS | En cada actualización, obtenga información de conexión actualizada del archivo de conexión externa.<br/> si está disponible, y utilícelo en lugar de la información de conexión existente.<br/>En este caso, la actualización de datos fallará si el archivo de conexión externa no está disponible.|
| NEVER | Nunca obtenga información de conexión actualizada del archivo de conexión externa<br/> incluso si está disponible e incluso si la información de conexión existente no es válida|



###  Ver también
* módulo [`aspose.cells.externalconnections`](..)
