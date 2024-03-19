---
title: PptxSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1230
url: /de/aspose.cells/pptxsaveoptions/
is_root: false
---
##  PptxSaveOptions Klasse
Stellt die PPTX-Speicheroptionen dar.



**Nachlass:** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ PptxSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/pptxsaveoptions/__init__/#) | Stellt die PPTX-Speicheroptionen dar.|
| [__init__](/cells/python-net/de/aspose.cells/pptxsaveoptions/__init__/#bool) | Stellt Optionen zum Speichern einer PPTX-Datei dar.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/pptxsaveoptions/save_format) | Ruft das Speicherdateiformat ab.|
| [clear_data](/cells/python-net/de/aspose.cells/pptxsaveoptions/clear_data) | Machen Sie die Arbeitsmappe leer, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/pptxsaveoptions/cached_file_folder) | Der zwischengespeicherte Dateiordner wird zum Speichern großer Datenmengen verwendet.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/pptxsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden.|
| [merge_areas](/cells/python-net/de/aspose.cells/pptxsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden.|
| [create_directory](/cells/python-net/de/aspose.cells/pptxsaveoptions/create_directory) | Wenn „true“ und das Verzeichnis nicht existiert, wird das Verzeichnis automatisch erstellt, bevor die Datei gespeichert wird.|
| [sort_names](/cells/python-net/de/aspose.cells/pptxsaveoptions/sort_names) | Gibt an, ob definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/pptxsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/pptxsaveoptions/refresh_chart_cache) | Gibt an, ob Diagramm-Cache-Daten aktualisiert werden|
| [warning_callback](/cells/python-net/de/aspose.cells/pptxsaveoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [update_smart_art](/cells/python-net/de/aspose.cells/pptxsaveoptions/update_smart_art) | Gibt an, ob die Smart-Art-Einstellung aktualisiert wird.<br/> Der Standardwert ist false.|
| [default_font](/cells/python-net/de/aspose.cells/pptxsaveoptions/default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/>Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese Zeichen anzuzeigen.<br/> Wenn diese Eigenschaft nicht festgelegt ist, verwendet Aspose.Cells die Standardschriftart des Systems, um diese Unicode-Zeichen anzuzeigen.|
| [check_workbook_default_font](/cells/python-net/de/aspose.cells/pptxsaveoptions/check_workbook_default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/> Setzen Sie dies auf „true“, um zu versuchen, die Standardschriftart der Arbeitsmappe zu verwenden, um diese Zeichen zuerst anzuzeigen.|
| [check_font_compatibility](/cells/python-net/de/aspose.cells/pptxsaveoptions/check_font_compatibility) | Gibt an, ob die Schriftartkompatibilität für jedes Zeichen im Text überprüft werden soll.|
| [is_font_substitution_char_granularity](/cells/python-net/de/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |Gibt an, ob die Schriftart des Zeichens nur dann ersetzt werden soll, wenn die Zellenschriftart nicht damit kompatibel ist.|
| [one_page_per_sheet](/cells/python-net/de/aspose.cells/pptxsaveoptions/one_page_per_sheet) | Wenn OnePagePerSheet true ist, wird der gesamte Inhalt eines Blattes im Ergebnis nur auf einer Seite ausgegeben.<br/> Das Papierformat von „pagesetup“ und die anderen Einstellungen von „pagesetup“ sind ungültig<br/> wird weiterhin wirksam.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/de/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) | Wenn AllColumnsInOnePagePerSheet true ist, wird der gesamte Spalteninhalt eines Blattes nur auf einer Seite im Ergebnis ausgegeben.<br/> Die Breite des Papierformats von „pagesetup“ und die anderen Einstellungen von „pagesetup“ werden ignoriert<br/> wird weiterhin wirksam.|
| [ignore_error](/cells/python-net/de/aspose.cells/pptxsaveoptions/ignore_error) | Gibt an, ob Sie den Fehler beim Rendern ausblenden müssen.<br/> Der Fehler kann ein Fehler in Form, Bild, Diagrammdarstellung usw. sein.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/de/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) | Gibt an, ob eine leere Seite ausgegeben werden soll, wenn nichts zu drucken ist.|
| [page_index](/cells/python-net/de/aspose.cells/pptxsaveoptions/page_index) | Ruft den 0-basierten Index der ersten zu speichernden Seite ab oder legt diesen fest.|
| [page_count](/cells/python-net/de/aspose.cells/pptxsaveoptions/page_count) | Ruft die Anzahl der zu speichernden Seiten ab oder legt diese fest.|
| [printing_page_type](/cells/python-net/de/aspose.cells/pptxsaveoptions/printing_page_type) | Gibt an, welche Seiten nicht gedruckt werden.|
| [gridline_type](/cells/python-net/de/aspose.cells/pptxsaveoptions/gridline_type) | Ruft den Rasterlinientyp ab oder legt diesen fest.|
| [text_cross_type](/cells/python-net/de/aspose.cells/pptxsaveoptions/text_cross_type) | Ruft den Anzeigetexttyp ab oder legt diesen fest, wenn die Textbreite größer als die Zellenbreite ist.|
| [default_edit_language](/cells/python-net/de/aspose.cells/pptxsaveoptions/default_edit_language) | Ruft die Standardbearbeitungssprache ab oder legt diese fest.|
| [sheet_set](/cells/python-net/de/aspose.cells/pptxsaveoptions/sheet_set) |Ruft die zu rendernden Blätter ab oder legt diese fest. Standardmäßig sind alle sichtbaren Blätter in der Arbeitsmappe: [`SheetSet.visible`](/cells/python-net/de/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/de/aspose.cells/pptxsaveoptions/draw_object_event_handler) | Implementiert diese Schnittstelle, um DrawObject und Bound beim Rendern abzurufen.|
| [page_saving_callback](/cells/python-net/de/aspose.cells/pptxsaveoptions/page_saving_callback) | Kontrollieren/Anzeigen des Fortschritts des Seitenspeichervorgangs.|
| [emf_render_setting](/cells/python-net/de/aspose.cells/pptxsaveoptions/emf_render_setting) | Einstellung zum Rendern der EMF-Metadatei.|
| [ignore_hidden_rows](/cells/python-net/de/aspose.cells/pptxsaveoptions/ignore_hidden_rows) | Gibt an, ob ausgeblendete Zeilen beim Konvertieren von Excel in PowerPoint ignoriert werden.|
| [adjust_font_size_for_row_type](/cells/python-net/de/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) | Stellt dar, welcher Zeilentyp angepasst werden muss. Die Schriftgröße muss angepasst werden, wenn die Zeilenhöhe klein ist.|
| [export_view_type](/cells/python-net/de/aspose.cells/pptxsaveoptions/export_view_type) | Ruft den Anzeigetyp beim Exportieren nach PowerPoint ab und legt ihn fest.<br/> Der Standard-Exporttyp ist das Drucken.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`PaginatedSaveOptions`](/cells/python-net/de/aspose.cells/paginatedsaveoptions)
* Klasse [`PptxSaveOptions`](/cells/python-net/de/aspose.cells/pptxsaveoptions)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
