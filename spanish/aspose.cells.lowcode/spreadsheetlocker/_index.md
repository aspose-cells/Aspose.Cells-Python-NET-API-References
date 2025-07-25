---
title: SpreadsheetLocker clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 170
url: /es/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker clase
API de código bajo para bloquear archivos de hojas de cálculo.



El tipo SpreadsheetLocker expone los siguientes miembros:

###  Métodos
| Método| Descripción|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/es/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Bloquea el archivo de hoja de cálculo con la configuración especificada.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/es/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Bloquea el archivo de hoja de cálculo con la configuración especificada.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/es/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Bloquea el archivo de hoja de cálculo con la configuración especificada.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/es/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Bloquea el archivo de hoja de cálculo con la configuración especificada.|



###  Ejemplo

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Ver también
* módulo [`aspose.cells.lowcode`](..)
