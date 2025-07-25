---
title: IconSet Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 850
url: /de/aspose.cells/iconset/
is_root: false
---
##  IconSet Klasse
 Beschreiben Sie die Regel zur bedingten Formatierung IconSet.
Diese Regel für die bedingte Formatierung wendet Symbole auf Zellen an
entsprechend ihren Werten.



Der Typ IconSet macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [cf_icons](/cells/python-net/de/aspose.cells/iconset/cf_icons) | Holen Sie sich die [`ConditionalFormattingIcon`](/cells/python-net/de/aspose.cells/conditionalformattingicon) aus der Sammlung|
| [cfvos](/cells/python-net/de/aspose.cells/iconset/cfvos) | Holen Sie sich die CFValueObjects-Instanz.|
| [type](/cells/python-net/de/aspose.cells/iconset/type) | Rufen Sie den anzuzeigenden Symbolsatztyp ab oder legen Sie ihn fest.<br/>Durch die Einstellung des Typs wird automatisch geprüft, ob die aktuelle Cfvos-Anzahl<br/> Übereinstimmung mit dem neuen Typ. Wenn nicht übereinstimmen, werden alte CFVOs gereinigt und<br/> Standard-Cfvos werden hinzugefügt.|
| [is_custom](/cells/python-net/de/aspose.cells/iconset/is_custom) | Gibt an, ob der Symbolsatz benutzerdefiniert ist.<br/> Der Standardwert ist „false“.|
| [show_value](/cells/python-net/de/aspose.cells/iconset/show_value) | Rufen Sie das Flag ab oder legen Sie es fest, das angibt, ob die Werte der Zellen angezeigt werden sollen, auf die dieser Symbolsatz angewendet wird.<br/> Der Standardwert ist „true“.|
| [reverse](/cells/python-net/de/aspose.cells/iconset/reverse) |Rufen Sie das Flag ab oder legen Sie es fest, das angibt, ob die Standardreihenfolge der Symbole in diesem Symbolsatz umgekehrt werden soll.<br/> Der Standardwert ist „false“.|



###  Beispiel

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 2
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
# Adds condition.
idx = fcs.add_condition(FormatConditionType.ICON_SET)
fcs.add_area(ca)
cond = fcs[idx]
# Get Icon Set
iconSet = cond.icon_set
# Set Icon Type
iconSet.type = IconSetType.ARROWS3
# Put Cell Values
cell1 = sheet.cells.get("A1")
cell1.put_value(10)
cell2 = sheet.cells.get("A2")
cell2.put_value(120)
cell3 = sheet.cells.get("A3")
cell3.put_value(260)
# Saving the Excel file
workbook.save("book1.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`ConditionalFormattingIcon`](/cells/python-net/de/aspose.cells/conditionalformattingicon)
