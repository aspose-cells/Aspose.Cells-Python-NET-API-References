---
title: SpreadsheetLocker klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 170
url: /sv/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker klass
Lågkods-API för att låsa kalkylbladsfil.



Typen SpreadsheetLocker avslöjar följande medlemmar:

###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/sv/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Låser kalkylbladsfilen med angivna inställningar.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/sv/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Låser kalkylbladsfilen med angivna inställningar.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/sv/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Låser kalkylbladsfilen med angivna inställningar.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/sv/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Låser kalkylbladsfilen med angivna inställningar.|



###  Exempel

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Se även
* modul [`aspose.cells.lowcode`](..)
