---
title: WorksheetCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1610
url: /de/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection Klasse
Kapselt eine Sammlung von [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet) Objekten.



Der Typ WorksheetCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/de/aspose.cells/worksheetcollection/web_extension_task_panes) | Ruft die Liste der Aufgabenbereiche ab.|
| [web_extensions](/cells/python-net/de/aspose.cells/worksheetcollection/web_extensions) | Ruft die Liste der Aufgabenbereiche ab.|
| [threaded_comment_authors](/cells/python-net/de/aspose.cells/worksheetcollection/threaded_comment_authors) | Ruft die Liste der Autoren von Thread-Kommentaren ab.|
| [is_refresh_all_connections](/cells/python-net/de/aspose.cells/worksheetcollection/is_refresh_all_connections) | Gibt an, ob beim Öffnen der Datei in MS Excel alle Verbindungen aktualisiert werden sollen.|
| [names](/cells/python-net/de/aspose.cells/worksheetcollection/names) | Ruft die Auflistung aller Name-Objekte in der Tabelle ab.|
| [active_sheet_name](/cells/python-net/de/aspose.cells/worksheetcollection/active_sheet_name) | Stellt den Namen des aktiven Arbeitsblatts dar, wenn die Kalkulationstabelle geöffnet wird.|
| [active_sheet_index](/cells/python-net/de/aspose.cells/worksheetcollection/active_sheet_index) | Stellt den Index des aktiven Arbeitsblatts dar, wenn die Tabelle geöffnet wird.|
| [dxfs](/cells/python-net/de/aspose.cells/worksheetcollection/dxfs) | Ruft die Masterdatensätze zur differenziellen Formatierung ab.|
| [xml_maps](/cells/python-net/de/aspose.cells/worksheetcollection/xml_maps) | Ruft die XML-Zuordnungen in der Arbeitsmappe ab und legt sie fest.|
| [built_in_document_properties](/cells/python-net/de/aspose.cells/worksheetcollection/built_in_document_properties) | Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle integrierten Dokumenteigenschaften der Tabelle darstellt.|
| [custom_document_properties](/cells/python-net/de/aspose.cells/worksheetcollection/custom_document_properties) | Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle benutzerdefinierten Dokumenteigenschaften der Tabelle darstellt.|
| [ole_size](/cells/python-net/de/aspose.cells/worksheetcollection/ole_size) | Ruft die angezeigte Größe ab und legt sie fest, wenn die Arbeitsmappendatei als OLE-Objekt verwendet wird.|
| [external_links](/cells/python-net/de/aspose.cells/worksheetcollection/external_links) |Stellt externe Links in einer Arbeitsmappe dar.|
| [table_styles](/cells/python-net/de/aspose.cells/worksheetcollection/table_styles) | Ruft das Objekt [`WorksheetCollection.table_styles`](/cells/python-net/de/aspose.cells/worksheetcollection#table_styles) ab.|
| [revision_logs](/cells/python-net/de/aspose.cells/worksheetcollection/revision_logs) | Stellt Revisionsprotokolle dar.|
| [sensitivity_labels](/cells/python-net/de/aspose.cells/worksheetcollection/sensitivity_labels) | Stellt alle Vertraulichkeitsbezeichnungen dar.|
| [capacity](/cells/python-net/de/aspose.cells/worksheetcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|



Ruft das Element [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet) am angegebenen Index ab.
###  Indexer
| Name| Beschreibung|
| :- | :- |
| [index] | Der nullbasierte Index des Elements.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get(self, index)`](/cells/python-net/de/aspose.cells/worksheetcollection/get/#int) | Add API for Python Via .Net.since this[int index] wird nicht unterstützt|
| [`get(self, sheet_name)`](/cells/python-net/de/aspose.cells/worksheetcollection/get/#str) | Hinzufügen API for Python Via .Net.since this[string sheetName] is unsupported|
| [`add(self, type)`](/cells/python-net/de/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Fügt der Sammlung ein Arbeitsblatt hinzu.|
| [`add(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/add/#) | Fügt der Sammlung ein Arbeitsblatt hinzu.|
| [`add(self, sheet_name)`](/cells/python-net/de/aspose.cells/worksheetcollection/add/#str) | Fügt der Sammlung ein Arbeitsblatt hinzu.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/de/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Fügt der Arbeitsmappe eine Add-In-Funktion hinzu|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/de/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Fügt der Arbeitsmappe eine Add-In-Funktion hinzu|
| [`add_copy(self, sheet_name)`](/cells/python-net/de/aspose.cells/worksheetcollection/add_copy/#str) | Fügt der Sammlung ein Arbeitsblatt hinzu und kopiert Daten aus einem vorhandenen Arbeitsblatt.|
| [`add_copy(self, sheet_index)`](/cells/python-net/de/aspose.cells/worksheetcollection/add_copy/#int) | Fügt der Sammlung ein Arbeitsblatt hinzu und kopiert Daten aus einem vorhandenen Arbeitsblatt.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/de/aspose.cells/worksheetcollection/add_copy/#list-list) | Kopieren Sie eine Gruppe von Arbeitsblättern.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/de/aspose.cells/worksheetcollection/get_range_by_name/#str) | Ruft das Range-Objekt anhand des vordefinierten Namens ab.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/de/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Ruft [`Range`](/cells/python-net/de/aspose.cells/range) anhand des vordefinierten Namens oder Tabellennamens ab|
| [`refresh_pivot_tables(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Aktualisiert alle PivotTables in der Excel-Datei.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/de/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Aktualisiert alle PivotTables in der Excel-Datei.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells/worksheetcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/de/aspose.cells/worksheetcollection/create_range/#str-int) | Erstellt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt aus einer Adresse des Bereichs.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/de/aspose.cells/worksheetcollection/create_union_range/#str-int) | Erstellt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt aus einer Adresse des Bereichs.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/de/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Ruft das Arbeitsblatt anhand des Codenamens ab.|
| [`sort_names(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/sort_names/#) | Sortiert die definierten Namen.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/de/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Vertauscht die beiden Blätter.|
| [`remove_by_name(self, name)`](/cells/python-net/de/aspose.cells/worksheetcollection/remove_by_name/#str) | Entfernen Sie ein Blatt nach Blattnamen. (CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/de/aspose.cells/worksheetcollection/remove_by_index/#int) | Entfernen eines Blatt-für-Blatt-Index|
| [`remove_at(self, name)`](/cells/python-net/de/aspose.cells/worksheetcollection/remove_at/#str) | Entfernt das Element mit einem angegebenen Namen.|
| [`get_named_ranges(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/get_named_ranges/#) | Ruft alle vordefinierten benannten Bereiche in der Tabelle ab.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Ruft alle vordefinierten benannten Bereiche in der Tabelle ab.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/de/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Legt die angezeigte Größe fest, wenn die Arbeitsmappendatei als OLE-Objekt verwendet wird.|
| [`clear_pivottables(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/clear_pivottables/#) |Löscht Pivot-Tabellen aus der Tabelle.|
| [`refresh_all(self)`](/cells/python-net/de/aspose.cells/worksheetcollection/refresh_all/#) | Aktualisieren Sie alle Pivot-Tabellen und Diagramme mit Pivot-Quelle.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
