---
title: SqlScriptSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells.saving/sqlscriptsaveoptions/
is_root: false
---
##  SqlScriptSaveOptions Klasse
Stellt die Optionen zum Speichern von SQL dar.



**Nachlass:** [`SqlScriptSaveOptions`](/cells/python-net/aspose.cells.saving/sqlscriptsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ SqlScriptSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/__init__/#) | Erstellt Optionen zum Speichern der SQL-Datei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/save_format) | Ruft das Format der gespeicherten Datei ab.|
| [clear_data](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/clear_data) | Leeren Sie die Arbeitsmappe, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/cached_file_folder) | Der Ordner für temporäre Dateien, die als Datencache verwendet werden können.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden sollen.|
| [merge_areas](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden sollen.|
| [create_directory](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/create_directory) | Wenn der Wert auf „true“ gesetzt ist und das Verzeichnis nicht existiert, wird das Verzeichnis vor dem Speichern der Datei automatisch erstellt.|
| [sort_names](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/sort_names) |Gibt an, ob vor dem Speichern der Datei die definierten Namen sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/refresh_chart_cache) | Gibt an, ob die Aktualisierung der Diagramm-Cache-Daten|
| [check_excel_restriction](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/> Wenn Sie einen Wert eingeben, der länger als 32 KB ist, wird er abgeschnitten.|
| [update_smart_art](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/update_smart_art) | Gibt an, ob die SmartArt-Einstellung aktualisiert wird.<br/> Der Standardwert ist „false“.|
| [encrypt_document_properties](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/encrypt_document_properties) | Gibt an, ob Dokumenteigenschaften beim Speichern als XLS-Datei verschlüsselt werden sollen.<br/> Der Standardwert ist „true“.|
| [check_if_table_exists](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/check_if_table_exists) | Überprüfen Sie vor dem Erstellen, ob der Tabellenname vorhanden ist|
| [column_type_map](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/column_type_map) | Ruft die Zuordnung des Spaltentyps für verschiedene Datenbanken ab und legt sie fest.|
| [check_all_data_for_column_type](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/check_all_data_for_column_type) | Überprüfen Sie alle Daten, um den Datentyp der Spalten zu ermitteln.|
| [add_blank_line_between_rows](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/add_blank_line_between_rows) | Fügen Sie zwischen den einzelnen Daten eine Leerzeile ein.|
| [separator](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/separator) | Ruft das Zeichentrennzeichen des SQL-Skripts ab und legt es fest.|
| [operator_type](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/operator_type) | Ruft den Operatortyp von SQL ab und legt ihn fest.|
| [primary_key](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/primary_key) | Gibt an, welche Spalte der Primärschlüssel der Datentabelle ist.|
| [create_table](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/create_table) | Gibt an, ob SQL exportiert oder eine Tabelle erstellt wird.|
| [id_name](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/id_name) | Ruft den Namen der ID-Spalte ab und legt ihn fest.|
| [start_id](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/start_id) | Ruft die Start-ID ab und legt sie fest.|
| [table_name](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/table_name) | Ruft den Tabellennamen ab und legt ihn fest.|
| [export_as_string](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/export_as_string) | Gibt an, ob alle Daten als Zeichenfolgenwert exportiert werden.|
| [sheet_indexes](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/sheet_indexes) |Stellt die Indizes der exportierten Blätter dar.|
| [export_area](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/export_area) | Ruft den Exportbereich ab oder legt ihn fest.|
| [has_header_row](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions/has_header_row) | Gibt an, ob der Bereich eine Kopfzeile enthält.|



###  Siehe auch
* Modul [`aspose.cells.saving`](..)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
* Klasse [`SqlScriptSaveOptions`](/cells/python-net/de/aspose.cells.saving/sqlscriptsaveoptions)
