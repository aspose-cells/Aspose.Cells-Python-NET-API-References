---
title: ListObject Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject Klasse
Stellt ein Listenobjekt auf einem Arbeitsblatt dar.
 Das Objekt ListObject ist ein Mitglied der ListObjects-Sammlung.
Die ListObjects-Auflistung enthält alle Listenobjekte auf einem Arbeitsblatt.



Der Typ ListObject macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [start_row](/cells/python-net/de/aspose.cells.tables/listobject/start_row) | Ruft die Startzeile des Bereichs ab.|
| [start_column](/cells/python-net/de/aspose.cells.tables/listobject/start_column) | Ruft die Startspalte des Bereichs ab.|
| [end_row](/cells/python-net/de/aspose.cells.tables/listobject/end_row) | Ruft die Endzeile des Bereichs ab.|
| [end_column](/cells/python-net/de/aspose.cells.tables/listobject/end_column) | Ruft die Endspalte des Bereichs ab.|
| [list_columns](/cells/python-net/de/aspose.cells.tables/listobject/list_columns) | Ruft die ListColumns des ListObject ab.|
| [show_header_row](/cells/python-net/de/aspose.cells.tables/listobject/show_header_row) | Ruft ab und legt fest, ob dieses ListObject die Kopfzeile anzeigt.|
| [show_totals](/cells/python-net/de/aspose.cells.tables/listobject/show_totals) | Ruft ab und legt fest, ob dieses ListObject die Gesamtzeile anzeigt.|
| [data_range](/cells/python-net/de/aspose.cells.tables/listobject/data_range) | Ruft den Datenbereich des ListObject ab.|
| [query_table](/cells/python-net/de/aspose.cells.tables/listobject/query_table) | Ruft die verknüpfte Abfragetabelle ab.|
| [data_source_type](/cells/python-net/de/aspose.cells.tables/listobject/data_source_type) |Ruft den Datenquellentyp der Tabelle ab.|
| [auto_filter](/cells/python-net/de/aspose.cells.tables/listobject/auto_filter) | Ruft einen automatischen Filter ab.|
| [display_name](/cells/python-net/de/aspose.cells.tables/listobject/display_name) | Ruft den Anzeigenamen ab und legt ihn fest.|
| [comment](/cells/python-net/de/aspose.cells.tables/listobject/comment) | Ruft den Kommentar der Tabelle ab und legt ihn fest.|
| [show_table_style_first_column](/cells/python-net/de/aspose.cells.tables/listobject/show_table_style_first_column) | Gibt an, ob der Stil auf die erste Spalte in der Tabelle angewendet werden soll.|
| [show_table_style_last_column](/cells/python-net/de/aspose.cells.tables/listobject/show_table_style_last_column) | Gibt an, ob der Stil auf die letzte Spalte in der Tabelle angewendet werden soll.|
| [show_table_style_row_stripes](/cells/python-net/de/aspose.cells.tables/listobject/show_table_style_row_stripes) | Gibt an, ob die Zeilenstreifenformatierung angewendet wird.|
| [show_table_style_column_stripes](/cells/python-net/de/aspose.cells.tables/listobject/show_table_style_column_stripes) | Gibt an, ob die Spaltenstreifenformatierung angewendet wird.|
| [table_style_type](/cells/python-net/de/aspose.cells.tables/listobject/table_style_type) | Ruft den integrierten Tabellenstil ab.|
| [table_style_name](/cells/python-net/de/aspose.cells.tables/listobject/table_style_name) | Ruft den Tabellenstilnamen ab und legt ihn fest.|
| [xml_map](/cells/python-net/de/aspose.cells.tables/listobject/xml_map) | Ruft eine [`ListObject.xml_map`](/cells/python-net/de/aspose.cells.tables/listobject#xml_map) ab, die für diese Liste verwendet wird.|
| [alternative_text](/cells/python-net/de/aspose.cells.tables/listobject/alternative_text) | Ruft den Alternativtext ab und legt ihn fest.|
| [alternative_description](/cells/python-net/de/aspose.cells.tables/listobject/alternative_description) | Ruft die alternative Beschreibung ab und legt sie fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/de/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Tragen Sie den Wert in die Zelle ein.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/de/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Tragen Sie den Wert in die Zelle ein.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/de/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Fügen Sie die Formel in die Zelle der Tabelle ein.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/de/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Fügen Sie die Formel in die Zelle der Tabelle ein.|
| [`convert_to_range(self)`](/cells/python-net/de/aspose.cells.tables/listobject/convert_to_range/#) | Konvertieren Sie die Tabelle in einen Bereich.|
| [`convert_to_range(self, options)`](/cells/python-net/de/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Konvertieren Sie die Tabelle in einen Bereich.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/de/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Ändern Sie die Größe des Bereichs des Listenobjekts.|
| [`update_column_name(self)`](/cells/python-net/de/aspose.cells.tables/listobject/update_column_name/#) | Aktualisiert alle Listenspaltennamen aus dem Arbeitsblatt.|
| [`filter(self)`](/cells/python-net/de/aspose.cells.tables/listobject/filter/#) | Filtern Sie die Tabelle.|
| [`apply_style_to_range(self)`](/cells/python-net/de/aspose.cells.tables/listobject/apply_style_to_range/#) | Wenden Sie den Tabellenstil auf den Bereich an.|



###  Beispiel

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.tables`](..)
