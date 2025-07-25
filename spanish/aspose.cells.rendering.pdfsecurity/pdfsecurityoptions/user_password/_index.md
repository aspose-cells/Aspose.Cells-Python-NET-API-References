---
title: user_password propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password propiedad

Obtiene o establece la contraseña de usuario necesaria para abrir el documento cifrado PDF.

###  Observaciones

Se requerirá la contraseña del propietario o la contraseña del usuario para abrir un documento encriptado PDF para su visualización.


La contraseña del usuario puede ser nula o una cadena vacía, en este caso no se le solicitará contraseña al usuario al abrir el documento PDF.


Abrir el documento con la contraseña de propietario correcta permite acceso completo al documento.


 Abrir el documento con la contraseña de usuario correcta (o abrir un documento que no tiene una contraseña de usuario)
permite acceso limitado según los permisos especificados.
###  Definición:
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.rendering.pdfsecurity`](../../)
* clase [`PdfSecurityOptions`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
