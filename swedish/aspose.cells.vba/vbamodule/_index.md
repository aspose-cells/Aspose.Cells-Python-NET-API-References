---
title: VbaModule klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.vba/vbamodule/
is_root: false
---
##  VbaModule klass
Representerar modulen i VBA-projektet.



Typen VbaModule avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [name](/cells/python-net/sv/aspose.cells.vba/vbamodule/name) | Hämtar och anger namnet på modulen.|
| [type](/cells/python-net/sv/aspose.cells.vba/vbamodule/type) | Hämtar modultypen.|
| [binary_codes](/cells/python-net/sv/aspose.cells.vba/vbamodule/binary_codes) | Hämtar och ställer in modulens binära koder.|
| [codes](/cells/python-net/sv/aspose.cells.vba/vbamodule/codes) | Hämtar och ställer in modulens koder.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.vba`](..)
