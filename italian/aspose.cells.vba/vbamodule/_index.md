---
title: VbaModule classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.vba/vbamodule/
is_root: false
---
##  VbaModule classe
Rappresenta il modulo nel progetto VBA.



Il tipo VbaModule espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [name](/cells/python-net/it/aspose.cells.vba/vbamodule/name) | Ottiene e imposta il nome del modulo.|
| [type](/cells/python-net/it/aspose.cells.vba/vbamodule/type) | Ottiene il tipo di modulo.|
| [binary_codes](/cells/python-net/it/aspose.cells.vba/vbamodule/binary_codes) | Ottiene e imposta i codici binari del modulo.|
| [codes](/cells/python-net/it/aspose.cells.vba/vbamodule/codes) | Ottiene e imposta i codici del modulo.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.vba`](..)
