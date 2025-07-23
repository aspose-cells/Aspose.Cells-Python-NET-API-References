---
title: SvgImageOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 130
url: /de/aspose.cells.rendering/svgimageoptions/
is_root: false
---
##  SvgImageOptions Klasse
Optionen zum Generieren eines SVG-Bildes.



**Nachlass:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions)



Der Typ SvgImageOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/__init__/#) | Ctor.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/save_format) | Ruft den Ausgabedateiformattyp ab oder legt ihn fest<br/> Support Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | Wenn PrintWithStatusDialog = true ist, wird ein Dialogfeld angezeigt, das den aktuellen Druckstatus anzeigt.<br/> andernfalls wird kein solcher Dialog angezeigt.|
| [horizontal_resolution](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | Ruft die horizontale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt sie fest.|
| [vertical_resolution](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/vertical_resolution) | Ruft die vertikale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt sie fest.|
| [tiff_compression](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/tiff_compression) | Ruft den Komprimierungstyp ab oder legt ihn fest, der nur beim Speichern von Seiten im Format `Tiff` angewendet werden soll.|
| [tiff_color_depth](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | Ruft die Bittiefe ab oder legt sie fest, die nur beim Speichern von Seiten im Format `Tiff` angewendet werden soll.|
| [tiff_binarization_method](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | Ruft die Methode ab oder legt sie fest, die beim Konvertieren von Bildern in das 1-bpp-Format verwendet wird.<br/>wenn [`ImageOrPrintOptions.image_type`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#image_type) Tiff ist und [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#tiff_compression) gleich Ccitt3 oder Ccitt4 ist.|
| [printing_page](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/printing_page) | Gibt an, welche Seiten nicht gedruckt werden.|
| [quality](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/quality) | Ruft einen Wert ab oder legt ihn fest, der die Qualität der generierten Bilder bestimmt<br/> gilt nur beim Speichern von Seiten im Format `Jpeg`. Der Standardwert ist 100|
| [image_type](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/image_type) | Ruft das Format der generierten Bilder ab oder legt es fest.<br/> Standardwert: PNG.|
| [is_cell_auto_fit](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | Gibt an, ob die Breite und Höhe der Zellen automatisch anhand des Zellenwerts angepasst wird.<br/> Der Standardwert ist „false“.|
| [one_page_per_sheet](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | Wenn „OnePagePerSheet“ auf „true“ gesetzt ist, wird der gesamte Inhalt eines Blatts im Ergebnis nur auf einer Seite ausgegeben.<br/> Die Papiergröße von pagesetup wird ungültig sein, und die anderen Einstellungen von pagesetup<br/> bleibt weiterhin wirksam.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | Wenn AllColumnsInOnePagePerSheet true ist, wird der gesamte Spalteninhalt eines Blattes im Ergebnis nur auf einer Seite ausgegeben.<br/> Die Breite der Papiergröße von pagesetup wird ungültig sein, und die anderen Einstellungen von pagesetup<br/> bleibt weiterhin wirksam.|
| [chart_image_type](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/chart_image_type) | Geben Sie beim Konvertieren den Diagrammbildtyp an.<br/> Standardwert: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | Geben Sie den Dateinamen des eingebetteten Bildes in SVG an.<br/> Dies sollte der vollständige Pfad mit Verzeichnis sein, etwa „c:\\xpsEmbedded“.|
| [svg_fit_to_view_port](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | Wenn diese Eigenschaft wahr ist, passt das generierte SVG in den Ansichtsbereich.|
| [svg_css_prefix](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/svg_css_prefix) |Ruft das Präfix des CSS-Namens in SVG ab und legt es fest. Der Standardwert ist eine leere Zeichenfolge.|
| [only_area](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/only_area) | Wenn diese Eigenschaft true ist, wird ein Bereich ausgegeben und es wird kein Maßstab wirksam.|
| [text_rendering_hint](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | Gibt die Qualität der Textwiedergabe an.<br/> Der Standardwert ist TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/smoothing_mode) | Gibt an, ob auf Linien und Kurven sowie auf die Kanten gefüllter Bereiche eine Glättung (Antialiasing) angewendet wird.<br/> Der Standardwert ist SmoothingMode.None|
| [transparent](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/transparent) | Gibt an, ob der Hintergrund des generierten Bildes transparent sein soll.|
| [pixel_format](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/pixel_format) | Ruft das Pixelformat für die generierten Bilder ab oder legt es fest.|
| [is_font_substitution_char_granularity](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | Gibt an, ob die Schriftart des Zeichens nur ersetzt werden soll, wenn die Zellenschriftart nicht damit kompatibel ist.|
| [page_index](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/page_index) | Ruft den 0-basierten Index der ersten zu speichernden Seite ab oder legt ihn fest.|
| [page_count](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/page_count) | Ruft die Anzahl der zu speichernden Seiten ab oder legt sie fest.|
| [is_optimized](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/is_optimized) | Gibt an, ob die Ausgabeelemente optimiert werden sollen.|
| [default_font](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt werden,<br/>Sie können als Block in PDF oder Bild erscheinen.<br/>Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese Zeichen anzuzeigen.<br/>Wenn diese Eigenschaft nicht festgelegt ist, verwendet Aspose.Cells die Standardschriftart des Systems, um diese Unicode-Zeichen anzuzeigen.|
| [check_workbook_default_font](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt werden,<br/>Sie können als Block in PDF oder Bild erscheinen.<br/> Setzen Sie dies auf „true“, um zu versuchen, diese Zeichen zuerst mit der Standardschriftart der Arbeitsmappe anzuzeigen.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | Gibt an, ob eine leere Seite ausgegeben werden soll, wenn nichts zu drucken ist.|
| [gridline_type](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/gridline_type) | Ruft den Gitternetzlinientyp ab oder legt ihn fest.|
| [gridline_color](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/gridline_color) | Ruft die Gitternetzlinienfarbe ab oder legt sie fest.|
| [text_cross_type](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/text_cross_type) | Ruft den anzuzeigenden Texttyp ab oder legt ihn fest, wenn die Textbreite größer als die Zellenbreite ist.|
| [emf_type](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/emf_type) | Ruft einen EmfType ab oder legt ihn fest, der das Format der Metadatei angibt.<br/> Der Standardwert ist EmfPlusDual.|
| [default_edit_language](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/default_edit_language) | Ruft die Standardbearbeitungssprache ab oder legt sie fest.|
| [sheet_set](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/sheet_set) | Ruft die zu rendernden Blätter ab oder legt sie fest. Standardmäßig werden alle sichtbaren Blätter in der Arbeitsmappe angezeigt: [`SheetSet.visible`](/cells/python-net/de/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/emf_render_setting) | Einstellung zum Rendern von EMF-Metadateien in der Quelldatei.|
| [custom_render_settings](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/custom_render_settings) | Ruft während des Renderns benutzerdefinierte Einstellungen ab oder legt diese fest.|
| [fit_to_view_port](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | Wenn diese Eigenschaft wahr ist, passt das generierte SVG in den Ansichtsbereich.|
| [css_prefix](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/css_prefix) |Ruft das Präfix des CSS-Namens in SVG ab und legt es fest. Der Standardwert ist eine leere Zeichenfolge.|
| [embedded_font_type](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/embedded_font_type) | Ruft den in SVG eingebetteten Schriftarttyp ab oder legt ihn fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | Legt die gewünschte Breite und Höhe des Bildes fest.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | Legt die gewünschte Breite und Höhe des Bildes fest.|



###  Siehe auch
* Modul [`aspose.cells.rendering`](..)
* Klasse [`ImageOrPrintOptions`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions)
* Klasse [`SvgImageOptions`](/cells/python-net/de/aspose.cells.rendering/svgimageoptions)
