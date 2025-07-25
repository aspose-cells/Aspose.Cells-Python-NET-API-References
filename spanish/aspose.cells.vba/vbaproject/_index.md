---
title: VbaProject clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject clase
Representa el proyecto VBA.



El tipo VbaProject expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_valid_signed](/cells/python-net/es/aspose.cells.vba/vbaproject/is_valid_signed) | Indica si la firma del proyecto VBA es válida o no.|
| [cert_raw_data](/cells/python-net/es/aspose.cells.vba/vbaproject/cert_raw_data) | Obtiene datos sin procesar del certificado si este proyecto VBA está firmado.|
| [encoding](/cells/python-net/es/aspose.cells.vba/vbaproject/encoding) |Obtiene y establece la codificación del proyecto VBA.|
| [name](/cells/python-net/es/aspose.cells.vba/vbaproject/name) | Obtiene y establece el nombre del proyecto VBA.|
| [is_signed](/cells/python-net/es/aspose.cells.vba/vbaproject/is_signed) | Indica si el código VBA está firmado o no.|
| [is_protected](/cells/python-net/es/aspose.cells.vba/vbaproject/is_protected) | Indica si este proyecto de VBA está protegido.|
| [islocked_for_viewing](/cells/python-net/es/aspose.cells.vba/vbaproject/islocked_for_viewing) | Indica si este proyecto VBA está bloqueado para su visualización.|
| [modules](/cells/python-net/es/aspose.cells.vba/vbaproject/modules) | Obtiene todos los [`VbaModule`](/cells/python-net/es/aspose.cells.vba/vbamodule) objetos.|
| [references](/cells/python-net/es/aspose.cells.vba/vbaproject/references) | Obtiene todas las referencias del proyecto VBA.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/es/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | Firme este proyecto VBA con una firma digital|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/es/aspose.cells.vba/vbaproject/protect/#bool-str) | Protege o desprotege este proyecto de VBA.|
| [`copy(self, source)`](/cells/python-net/es/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | Copiar proyecto VBA desde otro archivo.|
| [`validate_password(self, password)`](/cells/python-net/es/aspose.cells.vba/vbaproject/validate_password/#str) | Valida la contraseña de protección.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ver también
* módulo [`aspose.cells.vba`](..)
* clase [`VbaModule`](/cells/python-net/es/aspose.cells.vba/vbamodule)
