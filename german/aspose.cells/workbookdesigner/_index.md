---
title: WorkbookDesigner Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1670
url: /de/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner Klasse
Kapselt das Objekt, das eine Designer-Tabelle darstellt.



Der Typ WorkbookDesigner macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/workbookdesigner/__init__/#) | Initialisiert eine neue Instanz der Klasse [`WorkbookDesigner`](/cells/python-net/de/aspose.cells/workbookdesigner).|
| [__init__](/cells/python-net/de/aspose.cells/workbookdesigner/__init__/#aspose.cells.Workbook) | Initialisiert eine neue Instanz der Klasse [`WorkbookDesigner`](/cells/python-net/de/aspose.cells/workbookdesigner).|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [workbook](/cells/python-net/de/aspose.cells/workbookdesigner/workbook) | Ruft das Objekt [`WorkbookDesigner.workbook`](/cells/python-net/de/aspose.cells/workbookdesigner#workbook) ab und legt es fest.|
| [repeat_formulas_with_subtotal](/cells/python-net/de/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Gibt an, ob Formeln mit Zwischensummenzeile wiederholt werden.|
| [update_empty_string_as_null](/cells/python-net/de/aspose.cells/workbookdesigner/update_empty_string_as_null) | Wenn TRUE, wird Null eingefügt, wenn der Wert „“ ist;|
| [update_reference](/cells/python-net/de/aspose.cells/workbookdesigner/update_reference) | Gibt an, ob Verweise in anderen Arbeitsblättern aktualisiert werden.|
| [calculate_formula](/cells/python-net/de/aspose.cells/workbookdesigner/calculate_formula) | Gibt an, ob Formeln berechnet werden sollen.|
| [call_back](/cells/python-net/de/aspose.cells/workbookdesigner/call_back) | Ruft die Rückrufschnittstelle des verarbeitenden Smartmarkers ab und legt diese fest.|
| [line_by_line](/cells/python-net/de/aspose.cells/workbookdesigner/line_by_line) | Gibt an, ob der Smart Marker zeilenweise verarbeitet wird.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_data_source](/cells/python-net/de/aspose.cells/workbookdesigner/set_data_source/#str-aspose.cells.ICellsDataTable) | Legt die Datenquelle eines [`ICellsDataTable`](/cells/python-net/de/aspose.cells/icellsdatatable)-Objekts fest.|
| [set_data_source](/cells/python-net/de/aspose.cells/workbookdesigner/set_data_source/#str-any) | Legt die Datenbindung an eine Variable fest.|
| [process](/cells/python-net/de/aspose.cells/workbookdesigner/process/#) |Verarbeitet die Smart Marker und füllt die Datenquellenwerte auf.|
| [process](/cells/python-net/de/aspose.cells/workbookdesigner/process/#bool) |Verarbeitet die Smart Marker und füllt die Datenquellenwerte auf.|
| [process](/cells/python-net/de/aspose.cells/workbookdesigner/process/#int-bool) |Verarbeitet die Smart Marker und füllt die Datenquellenwerte auf.|
| [clear_data_source](/cells/python-net/de/aspose.cells/workbookdesigner/clear_data_source/#) | Löscht alle Datenquellen.|
| [set_json_data_source](/cells/python-net/de/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [get_smart_markers](/cells/python-net/de/aspose.cells/workbookdesigner/get_smart_markers/#) | Gibt eine Sammlung intelligenter Markierungen in einer Tabelle zurück.|



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
* Klasse [`ICellsDataTable`](/cells/python-net/de/aspose.cells/icellsdatatable)
* Klasse [`WorkbookDesigner`](/cells/python-net/de/aspose.cells/workbookdesigner)
