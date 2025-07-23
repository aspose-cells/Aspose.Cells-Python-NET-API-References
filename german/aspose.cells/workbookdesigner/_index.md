---
title: WorkbookDesigner Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1580
url: /de/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner Klasse
Kapselt das Objekt ein, das eine Designer-Tabelle darstellt.



Der Typ WorkbookDesigner macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/workbookdesigner/__init__/#) | Initialisiert eine neue Instanz der Klasse [`WorkbookDesigner`](/cells/python-net/de/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/de/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | Initialisiert eine neue Instanz der Klasse [`WorkbookDesigner`](/cells/python-net/de/aspose.cells/workbookdesigner).|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [workbook](/cells/python-net/de/aspose.cells/workbookdesigner/workbook) | Ruft das Objekt [`WorkbookDesigner.workbook`](/cells/python-net/de/aspose.cells/workbookdesigner#workbook) ab und legt es fest.|
| [repeat_formulas_with_subtotal](/cells/python-net/de/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Gibt an, ob Formeln mit Zwischensummenzeile wiederholt werden.|
| [update_empty_string_as_null](/cells/python-net/de/aspose.cells/workbookdesigner/update_empty_string_as_null) |Wenn TRUE, wird Null eingefügt, wenn der Wert "" ist;|
| [update_reference](/cells/python-net/de/aspose.cells/workbookdesigner/update_reference) | Gibt an, ob Verweise in anderen Arbeitsblättern aktualisiert werden.|
| [calculate_formula](/cells/python-net/de/aspose.cells/workbookdesigner/calculate_formula) | Gibt an, ob Formeln berechnet werden sollen.|
| [line_by_line](/cells/python-net/de/aspose.cells/workbookdesigner/line_by_line) | Gibt an, ob der Smartmarker zeilenweise verarbeitet wird.|
| [contains_variables](/cells/python-net/de/aspose.cells/workbookdesigner/contains_variables) | Gibt an, ob das erste Arbeitsblatt benutzerdefinierte Variablen enthält.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/de/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/de/aspose.cells/workbookdesigner/set_data_source/#str-any) | Legt die Datenbindung für eine Variable fest.|
| [`process(self, range, is_preserved)`](/cells/python-net/de/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | Verarbeitet die Smartmarker und füllt die Datenquellenwerte.|
| [`process(self)`](/cells/python-net/de/aspose.cells/workbookdesigner/process/#) | Verarbeitet die Smartmarker und füllt die Datenquellenwerte.|
| [`process(self, is_preserved)`](/cells/python-net/de/aspose.cells/workbookdesigner/process/#bool) | Verarbeitet die Smartmarker und füllt die Datenquellenwerte.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/de/aspose.cells/workbookdesigner/process/#int-bool) | Verarbeitet die Smartmarker und füllt die Datenquellenwerte.|
| [`clear_data_source(self)`](/cells/python-net/de/aspose.cells/workbookdesigner/clear_data_source/#) | Löscht alle Datenquellen.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/de/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/de/aspose.cells/workbookdesigner/get_smart_markers/#) | Gibt eine Sammlung intelligenter Markierungen in einer Tabelle zurück.|



###  Beispiel

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`WorkbookDesigner`](/cells/python-net/de/aspose.cells/workbookdesigner)
