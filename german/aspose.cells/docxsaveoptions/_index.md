---
title: DocxSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 510
url: /de/aspose.cells/docxsaveoptions/
is_root: false
---
##  DocxSaveOptions Klasse
Stellt Optionen zum Speichern einer DOCX-Datei dar.



**Nachlass:** [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ DocxSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/docxsaveoptions/__init__/#) | Stellt Optionen zum Speichern einer DOCX-Datei dar.|
| [__init__](/cells/python-net/de/aspose.cells/docxsaveoptions/__init__/#bool) | Stellt Optionen zum Speichern einer DOCX-Datei dar.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/docxsaveoptions/save_format) | Ruft das Speicherdateiformat ab.|
| [clear_data](/cells/python-net/de/aspose.cells/docxsaveoptions/clear_data) | Machen Sie die Arbeitsmappe leer, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/docxsaveoptions/cached_file_folder) | Der zwischengespeicherte Dateiordner wird zum Speichern großer Datenmengen verwendet.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/docxsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden.|
| [merge_areas](/cells/python-net/de/aspose.cells/docxsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden.|
| [create_directory](/cells/python-net/de/aspose.cells/docxsaveoptions/create_directory) | Wenn „true“ und das Verzeichnis nicht existiert, wird das Verzeichnis automatisch erstellt, bevor die Datei gespeichert wird.|
| [sort_names](/cells/python-net/de/aspose.cells/docxsaveoptions/sort_names) | Gibt an, ob definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/docxsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/docxsaveoptions/refresh_chart_cache) | Gibt an, ob Diagramm-Cache-Daten aktualisiert werden|
| [warning_callback](/cells/python-net/de/aspose.cells/docxsaveoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [update_smart_art](/cells/python-net/de/aspose.cells/docxsaveoptions/update_smart_art) | Gibt an, ob die Smart-Art-Einstellung aktualisiert wird.<br/> Der Standardwert ist false.|
| [default_font](/cells/python-net/de/aspose.cells/docxsaveoptions/default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/>Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese Zeichen anzuzeigen.<br/> Wenn diese Eigenschaft nicht festgelegt ist, verwendet Aspose.Cells die Standardschriftart des Systems, um diese Unicode-Zeichen anzuzeigen.|
| [check_workbook_default_font](/cells/python-net/de/aspose.cells/docxsaveoptions/check_workbook_default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/> Setzen Sie dies auf „true“, um zu versuchen, die Standardschriftart der Arbeitsmappe zu verwenden, um diese Zeichen zuerst anzuzeigen.|
| [check_font_compatibility](/cells/python-net/de/aspose.cells/docxsaveoptions/check_font_compatibility) | Gibt an, ob die Schriftartkompatibilität für jedes Zeichen im Text überprüft werden soll.|
| [is_font_substitution_char_granularity](/cells/python-net/de/aspose.cells/docxsaveoptions/is_font_substitution_char_granularity) |Gibt an, ob die Schriftart des Zeichens nur dann ersetzt werden soll, wenn die Zellenschriftart nicht damit kompatibel ist.|
| [one_page_per_sheet](/cells/python-net/de/aspose.cells/docxsaveoptions/one_page_per_sheet) | Wenn OnePagePerSheet true ist, wird der gesamte Inhalt eines Blattes im Ergebnis nur auf einer Seite ausgegeben.<br/> Das Papierformat von „pagesetup“ und die anderen Einstellungen von „pagesetup“ sind ungültig<br/> wird weiterhin wirksam.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/de/aspose.cells/docxsaveoptions/all_columns_in_one_page_per_sheet) | Wenn AllColumnsInOnePagePerSheet true ist, wird der gesamte Spalteninhalt eines Blattes nur auf einer Seite im Ergebnis ausgegeben.<br/> Die Breite des Papierformats von „pagesetup“ und die anderen Einstellungen von „pagesetup“ werden ignoriert<br/> wird weiterhin wirksam.|
| [ignore_error](/cells/python-net/de/aspose.cells/docxsaveoptions/ignore_error) | Gibt an, ob Sie den Fehler beim Rendern ausblenden müssen.<br/> Der Fehler kann ein Fehler in Form, Bild, Diagrammdarstellung usw. sein.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/de/aspose.cells/docxsaveoptions/output_blank_page_when_nothing_to_print) | Gibt an, ob eine leere Seite ausgegeben werden soll, wenn nichts zu drucken ist.|
| [page_index](/cells/python-net/de/aspose.cells/docxsaveoptions/page_index) | Ruft den 0-basierten Index der ersten zu speichernden Seite ab oder legt diesen fest.|
| [page_count](/cells/python-net/de/aspose.cells/docxsaveoptions/page_count) | Ruft die Anzahl der zu speichernden Seiten ab oder legt diese fest.|
| [printing_page_type](/cells/python-net/de/aspose.cells/docxsaveoptions/printing_page_type) | Gibt an, welche Seiten nicht gedruckt werden.|
| [gridline_type](/cells/python-net/de/aspose.cells/docxsaveoptions/gridline_type) | Ruft den Rasterlinientyp ab oder legt diesen fest.|
| [text_cross_type](/cells/python-net/de/aspose.cells/docxsaveoptions/text_cross_type) | Ruft den Anzeigetexttyp ab oder legt diesen fest, wenn die Textbreite größer als die Zellenbreite ist.|
| [default_edit_language](/cells/python-net/de/aspose.cells/docxsaveoptions/default_edit_language) | Ruft die Standardbearbeitungssprache ab oder legt diese fest.|
| [sheet_set](/cells/python-net/de/aspose.cells/docxsaveoptions/sheet_set) |Ruft die zu rendernden Blätter ab oder legt diese fest. Standardmäßig sind alle sichtbaren Blätter in der Arbeitsmappe: [`SheetSet.visible`](/cells/python-net/de/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/de/aspose.cells/docxsaveoptions/draw_object_event_handler) | Implementiert diese Schnittstelle, um DrawObject und Bound beim Rendern abzurufen.|
| [page_saving_callback](/cells/python-net/de/aspose.cells/docxsaveoptions/page_saving_callback) | Kontrollieren/Anzeigen des Fortschritts des Seitenspeichervorgangs.|
| [emf_render_setting](/cells/python-net/de/aspose.cells/docxsaveoptions/emf_render_setting) | Einstellung zum Rendern der EMF-Metadatei.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`DocxSaveOptions`](/cells/python-net/de/aspose.cells/docxsaveoptions)
* Klasse [`PaginatedSaveOptions`](/cells/python-net/de/aspose.cells/paginatedsaveoptions)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
