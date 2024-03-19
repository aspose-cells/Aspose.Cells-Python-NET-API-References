---
title: PdfSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1220
url: /de/aspose.cells/pdfsaveoptions/
is_root: false
---
##  PdfSaveOptions Klasse
Stellt die Optionen zum Speichern einer PDF-Datei dar.



**Nachlass:** [`PdfSaveOptions`](/cells/python-net/aspose.cells/pdfsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ PdfSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/pdfsaveoptions/__init__/#) | Erstellt die Optionen zum Speichern einer PDF-Datei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/pdfsaveoptions/save_format) | Ruft das Speicherdateiformat ab.|
| [clear_data](/cells/python-net/de/aspose.cells/pdfsaveoptions/clear_data) | Machen Sie die Arbeitsmappe leer, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/pdfsaveoptions/cached_file_folder) | Der zwischengespeicherte Dateiordner wird zum Speichern großer Datenmengen verwendet.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/pdfsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden.|
| [merge_areas](/cells/python-net/de/aspose.cells/pdfsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden.|
| [create_directory](/cells/python-net/de/aspose.cells/pdfsaveoptions/create_directory) | Wenn „true“ und das Verzeichnis nicht existiert, wird das Verzeichnis automatisch erstellt, bevor die Datei gespeichert wird.|
| [sort_names](/cells/python-net/de/aspose.cells/pdfsaveoptions/sort_names) | Gibt an, ob definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/pdfsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/pdfsaveoptions/refresh_chart_cache) | Gibt an, ob Diagramm-Cache-Daten aktualisiert werden|
| [warning_callback](/cells/python-net/de/aspose.cells/pdfsaveoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [update_smart_art](/cells/python-net/de/aspose.cells/pdfsaveoptions/update_smart_art) | Gibt an, ob die Smart-Art-Einstellung aktualisiert wird.<br/> Der Standardwert ist false.|
| [default_font](/cells/python-net/de/aspose.cells/pdfsaveoptions/default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/>Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese Zeichen anzuzeigen.<br/> Wenn diese Eigenschaft nicht festgelegt ist, verwendet Aspose.Cells die Standardschriftart des Systems, um diese Unicode-Zeichen anzuzeigen.|
| [check_workbook_default_font](/cells/python-net/de/aspose.cells/pdfsaveoptions/check_workbook_default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/> Setzen Sie dies auf „true“, um zu versuchen, die Standardschriftart der Arbeitsmappe zu verwenden, um diese Zeichen zuerst anzuzeigen.|
| [check_font_compatibility](/cells/python-net/de/aspose.cells/pdfsaveoptions/check_font_compatibility) | Gibt an, ob die Schriftartkompatibilität für jedes Zeichen im Text überprüft werden soll.|
| [is_font_substitution_char_granularity](/cells/python-net/de/aspose.cells/pdfsaveoptions/is_font_substitution_char_granularity) |Gibt an, ob die Schriftart des Zeichens nur dann ersetzt werden soll, wenn die Zellenschriftart nicht damit kompatibel ist.|
| [one_page_per_sheet](/cells/python-net/de/aspose.cells/pdfsaveoptions/one_page_per_sheet) | Wenn OnePagePerSheet true ist, wird der gesamte Inhalt eines Blattes im Ergebnis nur auf einer Seite ausgegeben.<br/> Das Papierformat von „pagesetup“ und die anderen Einstellungen von „pagesetup“ sind ungültig<br/> wird weiterhin wirksam.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/de/aspose.cells/pdfsaveoptions/all_columns_in_one_page_per_sheet) | Wenn AllColumnsInOnePagePerSheet true ist, wird der gesamte Spalteninhalt eines Blattes nur auf einer Seite im Ergebnis ausgegeben.<br/> Die Breite des Papierformats von „pagesetup“ und die anderen Einstellungen von „pagesetup“ werden ignoriert<br/> wird weiterhin wirksam.|
| [ignore_error](/cells/python-net/de/aspose.cells/pdfsaveoptions/ignore_error) | Gibt an, ob Sie den Fehler beim Rendern ausblenden müssen.<br/> Der Fehler kann ein Fehler in Form, Bild, Diagrammdarstellung usw. sein.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/de/aspose.cells/pdfsaveoptions/output_blank_page_when_nothing_to_print) | Gibt an, ob eine leere Seite ausgegeben werden soll, wenn nichts zu drucken ist.|
| [page_index](/cells/python-net/de/aspose.cells/pdfsaveoptions/page_index) | Ruft den 0-basierten Index der ersten zu speichernden Seite ab oder legt diesen fest.|
| [page_count](/cells/python-net/de/aspose.cells/pdfsaveoptions/page_count) | Ruft die Anzahl der zu speichernden Seiten ab oder legt diese fest.|
| [printing_page_type](/cells/python-net/de/aspose.cells/pdfsaveoptions/printing_page_type) | Gibt an, welche Seiten nicht gedruckt werden.|
| [gridline_type](/cells/python-net/de/aspose.cells/pdfsaveoptions/gridline_type) | Ruft den Rasterlinientyp ab oder legt diesen fest.|
| [text_cross_type](/cells/python-net/de/aspose.cells/pdfsaveoptions/text_cross_type) | Ruft den Anzeigetexttyp ab oder legt diesen fest, wenn die Textbreite größer als die Zellenbreite ist.|
| [default_edit_language](/cells/python-net/de/aspose.cells/pdfsaveoptions/default_edit_language) | Ruft die Standardbearbeitungssprache ab oder legt diese fest.|
| [sheet_set](/cells/python-net/de/aspose.cells/pdfsaveoptions/sheet_set) |Ruft die zu rendernden Blätter ab oder legt diese fest. Standardmäßig sind alle sichtbaren Blätter in der Arbeitsmappe: [`SheetSet.visible`](/cells/python-net/de/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/de/aspose.cells/pdfsaveoptions/draw_object_event_handler) | Implementiert diese Schnittstelle, um DrawObject und Bound beim Rendern abzurufen.|
| [page_saving_callback](/cells/python-net/de/aspose.cells/pdfsaveoptions/page_saving_callback) | Kontrollieren/Anzeigen des Fortschritts des Seitenspeichervorgangs.|
| [emf_render_setting](/cells/python-net/de/aspose.cells/pdfsaveoptions/emf_render_setting) | Einstellung zum Rendern der EMF-Metadatei.|
| [embed_standard_windows_fonts](/cells/python-net/de/aspose.cells/pdfsaveoptions/embed_standard_windows_fonts) | True, um True-Type-Schriftarten einzubetten.<br/>Betrifft nur die ASCII-Zeichen 32–127.<br/>Schriftarten für Zeichencodes größer als 127 werden immer eingebettet.<br/>Schriftarten werden für den Standard PDF/A-1a, PDF/A-1b immer eingebettet.<br/> Der Standardwert ist wahr.|
| [bookmark](/cells/python-net/de/aspose.cells/pdfsaveoptions/bookmark) | Ruft das Objekt [`PdfBookmarkEntry`](/cells/python-net/de/aspose.cells.rendering/pdfbookmarkentry) ab und legt es fest.|
| [compliance](/cells/python-net/de/aspose.cells/pdfsaveoptions/compliance) | Ruft die Konformitätsstufe des Standards PDF für Ausgabedokumente ab oder legt diese fest.|
| [security_options](/cells/python-net/de/aspose.cells/pdfsaveoptions/security_options) | Legen Sie diese Optionen fest, wenn Sicherheit im xls2pdf-Ergebnis erforderlich ist.|
| [image_type](/cells/python-net/de/aspose.cells/pdfsaveoptions/image_type) |Stellt den Bildtyp beim Konvertieren des Diagramms und der Form dar.|
| [calculate_formula](/cells/python-net/de/aspose.cells/pdfsaveoptions/calculate_formula) | Gibt an, ob Formeln berechnet werden sollen, bevor die PDF-Datei gespeichert wird.|
| [pdf_compression](/cells/python-net/de/aspose.cells/pdfsaveoptions/pdf_compression) | Geben Sie den Komprimierungsalgorithmus an|
| [created_time](/cells/python-net/de/aspose.cells/pdfsaveoptions/created_time) | Ruft den Zeitpunkt der Generierung des PDF-Dokuments ab und legt diesen fest.|
| [producer](/cells/python-net/de/aspose.cells/pdfsaveoptions/producer) | Ruft den Produzenten des generierten PDF-Dokuments ab und legt diesen fest.|
| [optimization_type](/cells/python-net/de/aspose.cells/pdfsaveoptions/optimization_type) | Ruft den PDF-Optimierungstyp ab und legt ihn fest.|
| [custom_properties_export](/cells/python-net/de/aspose.cells/pdfsaveoptions/custom_properties_export) | Ruft einen Wert ab oder legt diesen fest, der bestimmt, wie [`CustomDocumentPropertyCollection`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection) in die Datei PDF exportiert werden. Der Standardwert ist „Keine“.|
| [export_document_structure](/cells/python-net/de/aspose.cells/pdfsaveoptions/export_document_structure) | Gibt an, ob die Dokumentstruktur exportiert werden soll.|
| [display_doc_title](/cells/python-net/de/aspose.cells/pdfsaveoptions/display_doc_title) | Gibt an, ob in der Titelleiste des Fensters der Dokumenttitel angezeigt werden soll.|
| [font_encoding](/cells/python-net/de/aspose.cells/pdfsaveoptions/font_encoding) | Ruft die eingebettete Schriftartenkodierung im PDF ab oder legt diese fest.|
| [watermark](/cells/python-net/de/aspose.cells/pdfsaveoptions/watermark) | Ruft das Wasserzeichen für die Ausgabe ab oder legt es fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_image_resample](/cells/python-net/de/aspose.cells/pdfsaveoptions/set_image_resample/#int-int) | Legt den gewünschten PPI (Pixel pro Zoll) für Resample-Bilder und die JPEG-Qualität fest.<br/> Alle Bilder werden mit der angegebenen Qualitätseinstellung in JPEG konvertiert.<br/> und Bilder, die größer als der angegebene PPI (Pixel pro Zoll) sind, werden neu abgetastet.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`CustomDocumentPropertyCollection`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection)
* Klasse [`PaginatedSaveOptions`](/cells/python-net/de/aspose.cells/paginatedsaveoptions)
* Klasse [`PdfBookmarkEntry`](/cells/python-net/de/aspose.cells.rendering/pdfbookmarkentry)
* Klasse [`PdfSaveOptions`](/cells/python-net/de/aspose.cells/pdfsaveoptions)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
