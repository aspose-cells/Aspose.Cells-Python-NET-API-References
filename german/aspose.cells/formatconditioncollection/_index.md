---
title: FormatConditionCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 710
url: /de/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection Klasse
Stellt eine bedingte Formatierung dar.
Die FormatConditions können bis zu drei bedingte Formate enthalten.



Der Typ FormatConditionCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [count](/cells/python-net/de/aspose.cells/formatconditioncollection/count) | Ruft die Anzahl der Bedingungen ab.|
| [range_count](/cells/python-net/de/aspose.cells/formatconditioncollection/range_count) | Ruft die Anzahl der bedingt formatierten Bereiche ab.|



Ruft die Formatierungsbedingung nach Index ab.
###  Indexer
| Name| Beschreibung|
| :- | :- |
| [index] | der Index der zurückzugebenden Formatierungsbedingung.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_condition(self, type, operator_type, formula1, formula2)`](/cells/python-net/de/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) | Fügt eine Formatierungsbedingung hinzu.|
| [`add_condition(self, type)`](/cells/python-net/de/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype) | Fügen Sie eine Formatbedingung hinzu.|
| [`remove_area(self, index)`](/cells/python-net/de/aspose.cells/formatconditioncollection/remove_area/#int) | Entfernt bedingt formatierte Zellbereiche nach Index.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/de/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Entfernen Sie die bedingte Formatierung im Bereich.|
| [`add(self, cell_area, type, operator_type, formula1, formula2)`](/cells/python-net/de/aspose.cells/formatconditioncollection/add/#aspose.cells.cellarea-aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) |Fügt den FormatConditions eine Formatierungsbedingung und den betroffenen Zellbereich hinzu<br/>Die FormatConditions können bis zu drei bedingte Formate enthalten.<br/> Verweise auf andere Blätter sind in den Formeln der bedingten Formatierung nicht zulässig.|
| [`add_area(self, cell_area)`](/cells/python-net/de/aspose.cells/formatconditioncollection/add_area/#aspose.cells.cellarea) | Fügt einen bedingt formatierten Zellbereich hinzu.|
| [`get_cell_area(self, index)`](/cells/python-net/de/aspose.cells/formatconditioncollection/get_cell_area/#int) | Ruft den bedingt formatierten Zellbereich nach Index ab.|
| [`remove_condition(self, index)`](/cells/python-net/de/aspose.cells/formatconditioncollection/remove_condition/#int) | Entfernt die Formatierungsbedingung nach Index.|



###  Beispiel

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet.
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
