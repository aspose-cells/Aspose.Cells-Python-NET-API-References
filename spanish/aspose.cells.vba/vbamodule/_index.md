---
title: VbaModule clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.vba/vbamodule/
is_root: false
---
##  VbaModule clase
Representa el módulo en el proyecto VBA.



El tipo VbaModule expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [name](/cells/python-net/es/aspose.cells.vba/vbamodule/name) | Obtiene y establece el nombre del módulo.|
| [type](/cells/python-net/es/aspose.cells.vba/vbamodule/type) | Obtiene el tipo de módulo.|
| [binary_codes](/cells/python-net/es/aspose.cells.vba/vbamodule/binary_codes) | Obtiene y establece los códigos binarios del módulo.|
| [codes](/cells/python-net/es/aspose.cells.vba/vbamodule/codes) | Obtiene y establece los códigos del módulo.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
index = vbaProject.modules.add(VbaModuleType.CLASS, "test")
#  Get vba module
vbaModule = vbaProject.modules[index]
#  Set codes
vbaModule.codes = "Sub ShowMessage()\r\nMsgBox \"Welcome to Aspose!\"\r\nEnd Sub"
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ver también
* módulo [`aspose.cells.vba`](..)
