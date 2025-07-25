---
title: IconSet classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 850
url: /it/aspose.cells/iconset/
is_root: false
---
##  IconSet classe
 Descrivere la regola di formattazione condizionale IconSet.
Questa regola di formattazione condizionale applica le icone alle celle
in base ai loro valori.



Il tipo IconSet espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [cf_icons](/cells/python-net/it/aspose.cells/iconset/cf_icons) | Ottieni il [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon) dalla collezione|
| [cfvos](/cells/python-net/it/aspose.cells/iconset/cfvos) | Ottieni l'istanza di CFValueObjects.|
| [type](/cells/python-net/it/aspose.cells/iconset/type) | Ottieni o imposta il tipo di set di icone da visualizzare.<br/>L'impostazione del tipo verificherà automaticamente se il conteggio Cfvos corrente è<br/> in accordo con il nuovo tipo. In caso contrario, i vecchi Cfvos verranno puliti e<br/> Verranno aggiunti i Cfvos predefiniti.|
| [is_custom](/cells/python-net/it/aspose.cells/iconset/is_custom) | Indica se il set di icone è personalizzato.<br/> Il valore predefinito è falso.|
| [show_value](/cells/python-net/it/aspose.cells/iconset/show_value) | Ottieni o imposta il flag che indica se visualizzare i valori delle celle a cui è applicato questo set di icone.<br/> Il valore predefinito è vero.|
| [reverse](/cells/python-net/it/aspose.cells/iconset/reverse) |Ottieni o imposta il flag che indica se invertire l'ordine predefinito delle icone in questo set di icone.<br/> Il valore predefinito è falso.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon)
