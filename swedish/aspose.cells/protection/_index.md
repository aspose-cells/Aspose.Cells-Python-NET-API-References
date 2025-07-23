---
title: Protection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1150
url: /sv/aspose.cells/protection/
is_root: false
---
##  Protection klass
Representerar de olika typerna av skyddsalternativ som är tillgängliga för ett kalkylblad.



Typen Protection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [allow_deleting_column](/cells/python-net/sv/aspose.cells/protection/allow_deleting_column) | Representerar om borttagning av kolumner är tillåten i ett skyddat kalkylblad.|
| [allow_deleting_row](/cells/python-net/sv/aspose.cells/protection/allow_deleting_row) | Representerar om borttagning av rader är tillåten i ett skyddat kalkylblad.|
| [allow_filtering](/cells/python-net/sv/aspose.cells/protection/allow_filtering) | Representerar om användaren har tillstånd att använda ett autofilter som skapades innan arket skyddades.|
| [allow_formatting_cell](/cells/python-net/sv/aspose.cells/protection/allow_formatting_cell) | Representerar om formatering av celler är tillåten i ett skyddat kalkylblad.|
| [allow_formatting_column](/cells/python-net/sv/aspose.cells/protection/allow_formatting_column) | Representerar om formatering av kolumner är tillåten i ett skyddat kalkylblad|
| [allow_formatting_row](/cells/python-net/sv/aspose.cells/protection/allow_formatting_row) |Representerar om formatering av rader är tillåten i ett skyddat kalkylblad|
| [allow_inserting_column](/cells/python-net/sv/aspose.cells/protection/allow_inserting_column) | Representerar om infogning av kolumner är tillåten i ett skyddat kalkylblad|
| [allow_inserting_hyperlink](/cells/python-net/sv/aspose.cells/protection/allow_inserting_hyperlink) | Representerar om infogning av hyperlänkar är tillåten i ett skyddat kalkylblad|
| [allow_inserting_row](/cells/python-net/sv/aspose.cells/protection/allow_inserting_row) | Representerar om insättning av rader är tillåten i ett skyddat kalkylblad|
| [allow_sorting](/cells/python-net/sv/aspose.cells/protection/allow_sorting) | Representerar om sorteringsalternativet är tillåtet på ett skyddat kalkylblad.|
| [allow_using_pivot_table](/cells/python-net/sv/aspose.cells/protection/allow_using_pivot_table) | Representerar om användaren har tillstånd att manipulera pivottabeller i ett skyddat kalkylblad.|
| [allow_editing_content](/cells/python-net/sv/aspose.cells/protection/allow_editing_content) | Representerar om användaren har behörighet att redigera innehållet i låsta celler i ett skyddat kalkylblad.|
| [allow_editing_object](/cells/python-net/sv/aspose.cells/protection/allow_editing_object) | Representerar om användaren har tillstånd att manipulera ritobjekt på ett skyddat kalkylblad.|
| [allow_editing_scenario](/cells/python-net/sv/aspose.cells/protection/allow_editing_scenario) | Representerar om användaren har behörighet att redigera scenarier i ett skyddat kalkylblad.|
| [allow_selecting_locked_cell](/cells/python-net/sv/aspose.cells/protection/allow_selecting_locked_cell) | Representerar om användaren har behörighet att markera låsta celler i ett skyddat kalkylblad.|
| [allow_selecting_unlocked_cell](/cells/python-net/sv/aspose.cells/protection/allow_selecting_unlocked_cell) | Representerar om användaren har behörighet att markera olåsta celler i ett skyddat kalkylblad.|
| [password](/cells/python-net/sv/aspose.cells/protection/password) | Representerar lösenordet för att skydda kalkylbladet.|
| [is_protected_with_password](/cells/python-net/sv/aspose.cells/protection/is_protected_with_password) | Anger om arbetsbladen är lösenordsskyddade.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/sv/aspose.cells/protection/copy/#aspose.cells.protection) |Information om kopieringsskydd.|
| [`verify_password(self, password)`](/cells/python-net/sv/aspose.cells/protection/verify_password/#str) | Verifierar lösenordet.|
| [`get_password_hash(self)`](/cells/python-net/sv/aspose.cells/protection/get_password_hash/#) | Hämtar hashen för det aktuella lösenordet.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  Se även
* modul [`aspose.cells`](..)
