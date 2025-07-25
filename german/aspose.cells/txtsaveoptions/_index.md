---
title: TxtSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1500
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
| [`__init__(self)`](/cells/python-net/de/aspose.cells/txtsaveoptions/__init__/#) | Erstellt Optionen zum Speichern von Textdateien.|
| [`__init__(self, save_format)`](/cells/python-net/de/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | Erstellt Optionen zum Speichern von Textdateien.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/txtsaveoptions/save_format) | Ruft das Format der gespeicherten Datei ab.|
| [clear_data](/cells/python-net/de/aspose.cells/txtsaveoptions/clear_data) | Leeren Sie die Arbeitsmappe, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/txtsaveoptions/cached_file_folder) | Der Ordner für temporäre Dateien, die als Datencache verwendet werden können.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/txtsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden sollen.|
| [merge_areas](/cells/python-net/de/aspose.cells/txtsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden sollen.|
| [create_directory](/cells/python-net/de/aspose.cells/txtsaveoptions/create_directory) | Wenn der Wert auf „true“ gesetzt ist und das Verzeichnis nicht existiert, wird das Verzeichnis vor dem Speichern der Datei automatisch erstellt.|
| [sort_names](/cells/python-net/de/aspose.cells/txtsaveoptions/sort_names) |Gibt an, ob vor dem Speichern der Datei die definierten Namen sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/txtsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/txtsaveoptions/refresh_chart_cache) | Gibt an, ob die Aktualisierung der Diagramm-Cache-Daten|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/txtsaveoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/> Wenn Sie einen Wert eingeben, der länger als 32 KB ist, wird er abgeschnitten.|
| [update_smart_art](/cells/python-net/de/aspose.cells/txtsaveoptions/update_smart_art) | Gibt an, ob die SmartArt-Einstellung aktualisiert wird.<br/> Der Standardwert ist „false“.|
| [encrypt_document_properties](/cells/python-net/de/aspose.cells/txtsaveoptions/encrypt_document_properties) | Gibt an, ob Dokumenteigenschaften beim Speichern als XLS-Datei verschlüsselt werden sollen.<br/> Der Standardwert ist „true“.|
| [separator](/cells/python-net/de/aspose.cells/txtsaveoptions/separator) | Ruft das Zeichentrennzeichen der Textdatei ab und legt es fest.|
| [separator_string](/cells/python-net/de/aspose.cells/txtsaveoptions/separator_string) | Ruft einen Zeichenfolgenwert als Trennzeichen ab und legt ihn fest.|
| [encoding](/cells/python-net/de/aspose.cells/txtsaveoptions/encoding) | Ruft die Standardcodierung ab und legt sie fest.|
| [always_quoted](/cells/python-net/de/aspose.cells/txtsaveoptions/always_quoted) | Gibt an, ob für jedes Feld immer „“ hinzugefügt werden soll.<br/>Wenn wahr, werden alle Werte in Anführungszeichen gesetzt;<br/>Wenn „false“, werden Werte nur dann in Anführungszeichen gesetzt, wenn sie benötigt werden (zum Beispiel<br/>wenn Werte Sonderzeichen wie „““, „\n“ oder Trennzeichen enthalten).<br/> Der Standardwert ist „false“.|
| [quote_type](/cells/python-net/de/aspose.cells/txtsaveoptions/quote_type) |Ruft ab oder legt fest, wie Werte in der exportierten Textdatei in Anführungszeichen gesetzt werden.|
| [format_strategy](/cells/python-net/de/aspose.cells/txtsaveoptions/format_strategy) | Ruft die Formatierungsstrategie beim Exportieren des Zellenwerts als Zeichenfolge ab und legt sie fest.|
| [trim_leading_blank_row_and_column](/cells/python-net/de/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Gibt an, ob führende leere Zeilen und Spalten wie in MS Excel abgeschnitten werden sollen.<br/> Der Standardwert ist „true“.|
| [trim_tailing_blank_cells](/cells/python-net/de/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Gibt an, ob leere Zellen in einer Zeile entfernt werden sollen. Der Standardwert ist „false“.|
| [keep_separators_for_blank_row](/cells/python-net/de/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Gibt an, ob für leere Zeilen Trennzeichen ausgegeben werden sollen.<br/> Der Standardwert ist „false“, daher ist der Inhalt für die leere Zeile standardmäßig leer.|
| [export_area](/cells/python-net/de/aspose.cells/txtsaveoptions/export_area) | Der zu exportierende Zellbereich.|
| [export_quote_prefix](/cells/python-net/de/aspose.cells/txtsaveoptions/export_quote_prefix) | Gibt an, ob das einfache Anführungszeichen als Teil des Wertes einer Zelle exportiert werden soll<br/> wenn [`Style.quote_prefix`](/cells/python-net/de/aspose.cells/style#quote_prefix) dafür zutrifft. Der Standardwert ist „false“.|
| [export_all_sheets](/cells/python-net/de/aspose.cells/txtsaveoptions/export_all_sheets) | Gibt an, ob alle Blätter in die Textdatei exportiert werden.<br/> Wenn der Wert „false“ ist, wird nur das aktive Blatt exportiert, genau wie bei MS Excel.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
* Klasse [`TxtSaveOptions`](/cells/python-net/de/aspose.cells/txtsaveoptions)
