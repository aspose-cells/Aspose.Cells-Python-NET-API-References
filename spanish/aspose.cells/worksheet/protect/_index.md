---
title: método protect
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 220
url: /es/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(self, type) {#aspose.cells.ProtectionType}
Protege la hoja de trabajo.



```python

def protect(self, type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/es/aspose.cells/protectiontype) | Tipo de protección.|
###  Observaciones

Este método protege la hoja de cálculo sin contraseña. Es compatible con la hoja de cálculo protect en todas las versiones de Excel.

##  protect(self, type, password, old_password) {#aspose.cells.ProtectionType-str-str}

Protege la hoja de trabajo.



```python

def protect(self, type, password, old_password):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/es/aspose.cells/protectiontype) | Tipo de protección.|
| password | str | Contraseña.|
| old_password | str | Si la hoja de trabajo ya está protegida con una contraseña, proporcione la contraseña anterior.<br/> De lo contrario, puede establecer un valor nulo o una cadena en blanco para este parámetro.|
###  Observaciones

Este método puede trabajar la hoja de cálculo protect en todas las versiones del archivo Excel.
###  Ejemplo


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
