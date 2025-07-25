---
title: SpreadsheetLocker classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 170
url: /it/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker classe
API low-code per bloccare i file del foglio di calcolo.



Il tipo SpreadsheetLocker espone i seguenti membri:

###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/it/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Blocca il file del foglio di calcolo con le impostazioni specificate.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/it/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Blocca il file del foglio di calcolo con le impostazioni specificate.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/it/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Blocca il file del foglio di calcolo con le impostazioni specificate.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/it/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Blocca il file del foglio di calcolo con le impostazioni specificate.|



###  Esempio

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Guarda anche
* modulo [`aspose.cells.lowcode`](..)
