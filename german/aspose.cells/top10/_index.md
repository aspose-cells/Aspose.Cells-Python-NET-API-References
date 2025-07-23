---
title: Top10 Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1460
url: /de/aspose.cells/top10/
is_root: false
---
##  Top10 Klasse
 Beschreiben Sie die Regel zur bedingten Formatierung Top10.
Diese Regel der bedingten Formatierung hebt Zellen hervor, deren
Die Werte fallen je nach Angabe in die obere oder untere N-Klammer.



Der Typ Top10 macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/top10/__init__/#) | Erstellt eine neue Instanz von Top10|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_percent](/cells/python-net/de/aspose.cells/top10/is_percent) | Ermitteln oder Festlegen, ob es sich bei einer „Oberste/Unterste n“-Regel um eine „Oberste/Unterste n Prozent“-Regel handelt.<br/> Der Standardwert ist „false“.|
| [is_bottom](/cells/python-net/de/aspose.cells/top10/is_bottom) | Ermitteln oder Festlegen, ob eine „Top/Bottom n“-Regel eine „Bottom n“-Regel ist.<br/> Der Standardwert ist „false“.|
| [rank](/cells/python-net/de/aspose.cells/top10/rank) | Rufen Sie den Wert von „n“ in einer bedingten Formatierungsregel „oben/unten n“ ab oder legen Sie ihn fest.<br/>Wenn IsPercent wahr ist, muss der Wert zwischen 0 und 100 liegen.<br/>Andernfalls muss es zwischen 0 und 1000 liegen.<br/> Der Standardwert ist 10.|



###  Beispiel

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea.create_cell_area(0, 0, 10, 10)
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.TOP10, OperatorType.NONE, None, None)
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
top10 = fc.top10
# Set the Top N
top10.rank = 5
# Saving the Excel file
workbook.save("output.xls")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
