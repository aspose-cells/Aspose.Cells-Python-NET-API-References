---
title: VbaModule Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.vba/vbamodule/
is_root: false
---
##  VbaModule Klasse
Stellt das Modul im VBA-Projekt dar.



Der Typ VbaModule macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [name](/cells/python-net/de/aspose.cells.vba/vbamodule/name) | Ruft den Namen des Moduls ab und legt ihn fest.|
| [type](/cells/python-net/de/aspose.cells.vba/vbamodule/type) | Ruft den Modultyp ab.|
| [binary_codes](/cells/python-net/de/aspose.cells.vba/vbamodule/binary_codes) | Ruft die Binärcodes des Moduls ab und legt sie fest.|
| [codes](/cells/python-net/de/aspose.cells.vba/vbamodule/codes) | Ruft die Codes des Moduls ab und legt sie fest.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.vba`](..)
