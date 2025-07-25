---
title: SpreadsheetLocker Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 170
url: /de/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker Klasse
Low-Code-API zum Sperren von Tabellenkalkulationsdateien.



Der Typ SpreadsheetLocker macht die folgenden Member verfügbar:

###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/de/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/de/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/de/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/de/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.|



###  Beispiel

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Siehe auch
* Modul [`aspose.cells.lowcode`](..)
