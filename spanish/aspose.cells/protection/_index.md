---
title: Protection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1150
url: /es/aspose.cells/protection/
is_root: false
---
##  Protection clase
Representa los distintos tipos de opciones de protección disponibles para una hoja de trabajo.



El tipo Protection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [allow_deleting_column](/cells/python-net/es/aspose.cells/protection/allow_deleting_column) | Representa si se permite la eliminación de columnas en una hoja de cálculo protegida.|
| [allow_deleting_row](/cells/python-net/es/aspose.cells/protection/allow_deleting_row) | Representa si se permite la eliminación de filas en una hoja de cálculo protegida.|
| [allow_filtering](/cells/python-net/es/aspose.cells/protection/allow_filtering) | Representa si al usuario se le permite hacer uso de un Autofiltro que fue creado antes de que la hoja fuera protegida.|
| [allow_formatting_cell](/cells/python-net/es/aspose.cells/protection/allow_formatting_cell) | Representa si se permite el formato de celdas en una hoja de cálculo protegida.|
| [allow_formatting_column](/cells/python-net/es/aspose.cells/protection/allow_formatting_column) | Representa si se permite el formato de columnas en una hoja de cálculo protegida|
| [allow_formatting_row](/cells/python-net/es/aspose.cells/protection/allow_formatting_row) |Representa si se permite el formato de filas en una hoja de cálculo protegida|
| [allow_inserting_column](/cells/python-net/es/aspose.cells/protection/allow_inserting_column) | Representa si se permite la inserción de columnas en una hoja de cálculo protegida|
| [allow_inserting_hyperlink](/cells/python-net/es/aspose.cells/protection/allow_inserting_hyperlink) | Representa si se permite la inserción de hipervínculos en una hoja de cálculo protegida|
| [allow_inserting_row](/cells/python-net/es/aspose.cells/protection/allow_inserting_row) | Representa si se permite la inserción de filas en una hoja de cálculo protegida|
| [allow_sorting](/cells/python-net/es/aspose.cells/protection/allow_sorting) | Representa si la opción de clasificación está permitida en una hoja de trabajo protegida.|
| [allow_using_pivot_table](/cells/python-net/es/aspose.cells/protection/allow_using_pivot_table) | Representa si al usuario se le permite manipular tablas dinámicas en una hoja de trabajo protegida.|
| [allow_editing_content](/cells/python-net/es/aspose.cells/protection/allow_editing_content) | Representa si el usuario tiene permiso para editar el contenido de las celdas bloqueadas en una hoja de cálculo protegida.|
| [allow_editing_object](/cells/python-net/es/aspose.cells/protection/allow_editing_object) | Representa si al usuario se le permite manipular objetos de dibujo en una hoja de trabajo protegida.|
| [allow_editing_scenario](/cells/python-net/es/aspose.cells/protection/allow_editing_scenario) | Representa si el usuario tiene permiso para editar escenarios en una hoja de trabajo protegida.|
| [allow_selecting_locked_cell](/cells/python-net/es/aspose.cells/protection/allow_selecting_locked_cell) | Representa si al usuario se le permite seleccionar celdas bloqueadas en una hoja de cálculo protegida.|
| [allow_selecting_unlocked_cell](/cells/python-net/es/aspose.cells/protection/allow_selecting_unlocked_cell) | Representa si al usuario se le permite seleccionar celdas desbloqueadas en una hoja de cálculo protegida.|
| [password](/cells/python-net/es/aspose.cells/protection/password) | Representa la contraseña para proteger la hoja de trabajo.|
| [is_protected_with_password](/cells/python-net/es/aspose.cells/protection/is_protected_with_password) | Indica si las hojas de trabajo están protegidas con contraseña.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/es/aspose.cells/protection/copy/#aspose.cells.protection) |Información de protección de copia.|
| [`verify_password(self, password)`](/cells/python-net/es/aspose.cells/protection/verify_password/#str) | Verifica la contraseña.|
| [`get_password_hash(self)`](/cells/python-net/es/aspose.cells/protection/get_password_hash/#) | Obtiene el hash de la contraseña actual.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  Ver también
* módulo [`aspose.cells`](..)
