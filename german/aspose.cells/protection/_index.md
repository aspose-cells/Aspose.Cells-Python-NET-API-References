---
title: Protection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1150
url: /de/aspose.cells/protection/
is_root: false
---
##  Protection Klasse
Stellt die verschiedenen Arten von Schutzoptionen dar, die für ein Arbeitsblatt verfügbar sind.



Der Typ Protection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [allow_deleting_column](/cells/python-net/de/aspose.cells/protection/allow_deleting_column) | Gibt an, ob das Löschen von Spalten in einem geschützten Arbeitsblatt zulässig ist.|
| [allow_deleting_row](/cells/python-net/de/aspose.cells/protection/allow_deleting_row) | Gibt an, ob das Löschen von Zeilen in einem geschützten Arbeitsblatt zulässig ist.|
| [allow_filtering](/cells/python-net/de/aspose.cells/protection/allow_filtering) | Gibt an, ob der Benutzer einen AutoFilter verwenden darf, der vor dem Schützen des Blatts erstellt wurde.|
| [allow_formatting_cell](/cells/python-net/de/aspose.cells/protection/allow_formatting_cell) | Gibt an, ob die Formatierung von Zellen in einem geschützten Arbeitsblatt zulässig ist.|
| [allow_formatting_column](/cells/python-net/de/aspose.cells/protection/allow_formatting_column) | Gibt an, ob die Formatierung von Spalten in einem geschützten Arbeitsblatt zulässig ist.|
| [allow_formatting_row](/cells/python-net/de/aspose.cells/protection/allow_formatting_row) |Gibt an, ob die Formatierung von Zeilen in einem geschützten Arbeitsblatt zulässig ist.|
| [allow_inserting_column](/cells/python-net/de/aspose.cells/protection/allow_inserting_column) | Gibt an, ob das Einfügen von Spalten in einem geschützten Arbeitsblatt zulässig ist.|
| [allow_inserting_hyperlink](/cells/python-net/de/aspose.cells/protection/allow_inserting_hyperlink) | Gibt an, ob das Einfügen von Hyperlinks in ein geschütztes Arbeitsblatt zulässig ist.|
| [allow_inserting_row](/cells/python-net/de/aspose.cells/protection/allow_inserting_row) | Gibt an, ob das Einfügen von Zeilen in ein geschütztes Arbeitsblatt zulässig ist.|
| [allow_sorting](/cells/python-net/de/aspose.cells/protection/allow_sorting) | Gibt an, ob die Sortieroption auf einem geschützten Arbeitsblatt zulässig ist.|
| [allow_using_pivot_table](/cells/python-net/de/aspose.cells/protection/allow_using_pivot_table) | Gibt an, ob der Benutzer Pivot-Tabellen in einem geschützten Arbeitsblatt bearbeiten darf.|
| [allow_editing_content](/cells/python-net/de/aspose.cells/protection/allow_editing_content) | Gibt an, ob der Benutzer den Inhalt gesperrter Zellen in einem geschützten Arbeitsblatt bearbeiten darf.|
| [allow_editing_object](/cells/python-net/de/aspose.cells/protection/allow_editing_object) | Gibt an, ob der Benutzer Zeichenobjekte auf einem geschützten Arbeitsblatt bearbeiten darf.|
| [allow_editing_scenario](/cells/python-net/de/aspose.cells/protection/allow_editing_scenario) | Gibt an, ob der Benutzer Szenarien auf einem geschützten Arbeitsblatt bearbeiten darf.|
| [allow_selecting_locked_cell](/cells/python-net/de/aspose.cells/protection/allow_selecting_locked_cell) | Gibt an, ob der Benutzer gesperrte Zellen in einem geschützten Arbeitsblatt auswählen darf.|
| [allow_selecting_unlocked_cell](/cells/python-net/de/aspose.cells/protection/allow_selecting_unlocked_cell) | Gibt an, ob der Benutzer nicht gesperrte Zellen in einem geschützten Arbeitsblatt auswählen darf.|
| [password](/cells/python-net/de/aspose.cells/protection/password) | Stellt das Kennwort zum Schutz des Arbeitsblatts dar.|
| [is_protected_with_password](/cells/python-net/de/aspose.cells/protection/is_protected_with_password) | Gibt an, ob die Arbeitsblätter mit einem Kennwort geschützt sind.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/de/aspose.cells/protection/copy/#aspose.cells.protection) |Informationen zum Kopierschutz.|
| [`verify_password(self, password)`](/cells/python-net/de/aspose.cells/protection/verify_password/#str) | Überprüft das Passwort.|
| [`get_password_hash(self)`](/cells/python-net/de/aspose.cells/protection/get_password_hash/#) | Ruft den Hash des aktuellen Passworts ab.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
