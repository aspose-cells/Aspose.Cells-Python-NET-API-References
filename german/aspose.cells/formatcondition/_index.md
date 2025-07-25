---
title: FormatCondition Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 700
url: /de/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition Klasse
Stellt eine Bedingung für die bedingte Formatierung dar.



Der Typ FormatCondition macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [formula1](/cells/python-net/de/aspose.cells/formatcondition/formula1) | Ruft den mit der bedingten Formatierung verknüpften Wert oder Ausdruck ab und legt ihn fest.|
| [formula2](/cells/python-net/de/aspose.cells/formatcondition/formula2) | Ruft den mit der bedingten Formatierung verknüpften Wert oder Ausdruck ab und legt ihn fest.|
| [operator](/cells/python-net/de/aspose.cells/formatcondition/operator) | Ruft den Operatortyp für das bedingte Format ab und legt ihn fest.|
| [stop_if_true](/cells/python-net/de/aspose.cells/formatcondition/stop_if_true) |True: Wenn diese Regel als „true“ ausgewertet wird, dürfen keine Regeln mit niedrigerer Priorität auf diese Regel angewendet werden.<br/> Gilt nur für Excel 2007;|
| [priority](/cells/python-net/de/aspose.cells/formatcondition/priority) | Die Priorität dieser Regel zur bedingten Formatierung. Dieser Wert wird verwendet, um zu bestimmen, welche<br/>Format ausgewertet und gerendert werden soll. Niedrigere numerische Werte haben eine höhere Priorität als<br/> höhere numerische Werte, wobei „1“ die höchste Priorität hat.|
| [style](/cells/python-net/de/aspose.cells/formatcondition/style) | Ruft den Stil bedingt formatierter Zellbereiche ab oder legt ihn fest.|
| [type](/cells/python-net/de/aspose.cells/formatcondition/type) | Ruft ab und legt fest, ob der Typ des bedingten Formats verwendet wird.|
| [icon_set](/cells/python-net/de/aspose.cells/formatcondition/icon_set) | Holen Sie sich die „IconSet“-Instanz der bedingten Formatierung.<br/>Der IconSetType der Standardinstanz ist TrafficLights31.<br/> Nur gültig für Typ = IconSet.|
| [data_bar](/cells/python-net/de/aspose.cells/formatcondition/data_bar) | Holen Sie sich die „DataBar“-Instanz der bedingten Formatierung.<br/>Die Standardfarbe der Instanz ist Blau.<br/> Nur gültig für den Typ „DataBar“.|
| [color_scale](/cells/python-net/de/aspose.cells/formatcondition/color_scale) | Holen Sie sich die „ColorScale“-Instanz der bedingten Formatierung.<br/>Die Standardinstanz ist eine „grün-gelb-rote“ 3-Farbskala.<br/> Nur gültig für Typ = Farbskala.|
| [top10](/cells/python-net/de/aspose.cells/formatcondition/top10) | Holen Sie sich die „Top10“-Instanz der bedingten Formatierung.<br/>Die Regel der Standardinstanz hebt Zellen hervor, deren<br/>Die Werte liegen im oberen Zehntelbereich.<br/> Nur gültig für den Typ „Top10“.|
| [above_average](/cells/python-net/de/aspose.cells/formatcondition/above_average) |Holen Sie sich die Instanz „Überdurchschnittlich“ der bedingten Formatierung.<br/> Die Regel der Standardinstanz hebt Zellen hervor, die<br/>über dem Durchschnitt aller Werte im Bereich.<br/> Nur gültig für Typ = Überdurchschnittlich.|
| [text](/cells/python-net/de/aspose.cells/formatcondition/text) | Der Textwert in einer bedingten Formatierungsregel „Text enthält“.<br/>Nur gültig für Typ = containsText, notContainsText, beginsWith und endsWith.<br/> Der Standardwert ist null.|
| [time_period](/cells/python-net/de/aspose.cells/formatcondition/time_period) | Der anwendbare Zeitraum in einer Regel zur bedingten Formatierung vom Typ „Datum, an dem …“<br/>Nur gültig für Typ = Zeitraum.<br/> Der Standardwert ist TimePeriodType.Today.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/formatcondition/get_formula1/#bool-bool) | Ruft den Wert oder Ausdruck ab, der dieser Formatbedingung zugeordnet ist.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/de/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Ruft den Wert oder Ausdruck der bedingten Formatierung der Zelle ab.|
| [`get_formula1(self, row, column)`](/cells/python-net/de/aspose.cells/formatcondition/get_formula1/#int-int) | Ruft die Formel der bedingten Formatierung der Zelle ab.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/formatcondition/get_formula2/#bool-bool) | Ruft den Wert oder Ausdruck ab, der dieser Formatbedingung zugeordnet ist.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/de/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Ruft den Wert oder Ausdruck der bedingten Formatierung der Zelle ab.|
| [`get_formula2(self, row, column)`](/cells/python-net/de/aspose.cells/formatcondition/get_formula2/#int-int) | Ruft die Formel der bedingten Formatierung der Zelle ab.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Legt den Wert oder Ausdruck fest, der mit dieser Formatbedingung verknüpft ist.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Legt den Wert oder Ausdruck fest, der mit dieser Formatbedingung verknüpft ist.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Legt den Wert oder Ausdruck fest, der mit dieser Formatbedingung verknüpft ist.|



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
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
