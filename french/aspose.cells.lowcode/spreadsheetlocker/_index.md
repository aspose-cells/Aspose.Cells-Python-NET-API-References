---
title: SpreadsheetLocker classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 170
url: /fr/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker classe
API low code pour verrouiller le fichier de feuille de calcul.



Le type SpreadsheetLocker expose les membres suivants :

###  Méthodes
| Méthode| Description|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/fr/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/fr/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/fr/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/fr/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.|



###  Exemple

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Voir également
* module [`aspose.cells.lowcode`](..)
