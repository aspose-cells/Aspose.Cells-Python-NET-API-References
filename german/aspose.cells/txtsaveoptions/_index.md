---
title: TxtSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1590
url: /de/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions Klasse
Stellt die Speicheroptionen für CSV/Tabulator-getrennte/andere Textformate dar.



**Nachlass:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ TxtSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/txtsaveoptions/__init__/#) | Erstellt Optionen zum Speichern von Textdateien.|
| [__init__](/cells/python-net/de/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) | Erstellt Optionen zum Speichern von Textdateien.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/txtsaveoptions/save_format) | Ruft das Speicherdateiformat ab.|
| [clear_data](/cells/python-net/de/aspose.cells/txtsaveoptions/clear_data) | Machen Sie die Arbeitsmappe leer, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/txtsaveoptions/cached_file_folder) | Der zwischengespeicherte Dateiordner wird zum Speichern großer Datenmengen verwendet.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/txtsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden.|
| [merge_areas](/cells/python-net/de/aspose.cells/txtsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden.|
| [create_directory](/cells/python-net/de/aspose.cells/txtsaveoptions/create_directory) | Wenn „true“ und das Verzeichnis nicht existiert, wird das Verzeichnis automatisch erstellt, bevor die Datei gespeichert wird.|
| [sort_names](/cells/python-net/de/aspose.cells/txtsaveoptions/sort_names) | Gibt an, ob definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/txtsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/txtsaveoptions/refresh_chart_cache) | Gibt an, ob Diagramm-Cache-Daten aktualisiert werden|
| [warning_callback](/cells/python-net/de/aspose.cells/txtsaveoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [update_smart_art](/cells/python-net/de/aspose.cells/txtsaveoptions/update_smart_art) | Gibt an, ob die Smart-Art-Einstellung aktualisiert wird.<br/> Der Standardwert ist false.|
| [separator](/cells/python-net/de/aspose.cells/txtsaveoptions/separator) | Ruft das Zeichentrennzeichen der Textdatei ab und legt es fest.|
| [separator_string](/cells/python-net/de/aspose.cells/txtsaveoptions/separator_string) | Ruft einen Zeichenfolgenwert als Trennzeichen ab und legt diesen fest.|
| [encoding](/cells/python-net/de/aspose.cells/txtsaveoptions/encoding) | Ruft die Standardkodierung ab und legt sie fest.|
| [always_quoted](/cells/python-net/de/aspose.cells/txtsaveoptions/always_quoted) | Gibt an, ob für jedes Feld immer „““ hinzugefügt wird.<br/>Wenn true, werden alle Werte in Anführungszeichen gesetzt.<br/>Bei „false“ werden Werte nur bei Bedarf in Anführungszeichen gesetzt (z. B.<br/>wenn Werte Sonderzeichen wie „““, „\n“ oder Trennzeichen enthalten).<br/> Der Standardwert ist falsch.|
| [quote_type](/cells/python-net/de/aspose.cells/txtsaveoptions/quote_type) | Ruft ab oder legt fest, wie Werte in der exportierten Textdatei in Anführungszeichen gesetzt werden.|
| [format_strategy](/cells/python-net/de/aspose.cells/txtsaveoptions/format_strategy) | Ruft die Formatstrategie beim Exportieren des Zellenwerts als Zeichenfolge ab und legt diese fest.|
| [light_cells_data_provider](/cells/python-net/de/aspose.cells/txtsaveoptions/light_cells_data_provider) | Der Datenanbieter zum Speichern von Arbeitsmappen im Light-Modus.|
| [trim_leading_blank_row_and_column](/cells/python-net/de/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Gibt an, ob führende leere Zeilen und Spalten wie in MS Excel gekürzt werden sollen.<br/> Der Standardwert ist wahr.|
| [trim_tailing_blank_cells](/cells/python-net/de/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Gibt an, ob abschließende leere Zellen in einer Zeile abgeschnitten werden sollen. Der Standardwert ist falsch.|
| [keep_separators_for_blank_row](/cells/python-net/de/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |Gibt an, ob Trennzeichen für leere Zeilen ausgegeben werden sollen.<br/> Der Standardwert ist „false“, sodass der Inhalt einer leeren Zeile standardmäßig leer ist.|
| [export_area](/cells/python-net/de/aspose.cells/txtsaveoptions/export_area) | Der Bereich der zu exportierenden Zellen.|
| [export_quote_prefix](/cells/python-net/de/aspose.cells/txtsaveoptions/export_quote_prefix) | Gibt an, ob das einfache Anführungszeichen als Teil des Werts einer Zelle exportiert werden soll<br/> wenn [`Style.quote_prefix`](/cells/python-net/de/aspose.cells/style#quote_prefix) dafür wahr ist. Der Standardwert ist falsch.|
| [export_all_sheets](/cells/python-net/de/aspose.cells/txtsaveoptions/export_all_sheets) | Gibt an, ob alle Blätter in die Textdatei exportiert werden.<br/> Wenn es falsch ist, exportieren Sie nur das Activesheet, genau wie MS Excel.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
* Klasse [`TxtSaveOptions`](/cells/python-net/de/aspose.cells/txtsaveoptions)
