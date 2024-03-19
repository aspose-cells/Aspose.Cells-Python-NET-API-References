---
title: ImageOrPrintOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions Klasse
Ermöglicht die Angabe von Optionen beim Rendern von Arbeitsblättern in Bilder, beim Drucken von Arbeitsblättern oder beim Rendern von Diagrammen in Bilder.



Der Typ ImageOrPrintOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/__init__/#) | Konstruiert eine neue Instanz von ImageOrPrintOptions|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/save_format) | Ruft den Formattyp der Ausgabedatei ab oder legt diesen fest<br/> Unterstützen Sie Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | Wenn PrintWithStatusDialog = true ist, wird ein Dialog angezeigt, der den aktuellen Druckstatus anzeigt.<br/>Andernfalls wird kein solcher Dialog angezeigt.|
| [horizontal_resolution](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Ruft die horizontale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt diese fest.<br/> Wendet die Methode zur Bildgenerierung an, mit Ausnahme von Bildern im EMF-Format.|
| [vertical_resolution](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Ruft die vertikale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt diese fest.<br/> Wendet die Methode zur Bildgenerierung an, mit Ausnahme von Bildern im Emf-Format.|
| [tiff_compression](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Ruft den Komprimierungstyp ab, der nur beim Speichern von Seiten im Format `Tiff` angewendet werden soll, oder legt diesen fest.|
| [tiff_color_depth](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Ruft die Bittiefe ab, die nur beim Speichern von Seiten im Format `Tiff` angewendet wird, oder legt diese fest.|
| [tiff_binarization_method](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Ruft die Methode ab, die beim Konvertieren von Bildern in das 1-bpp-Format verwendet wird, oder legt diese fest<br/> wenn [`ImageOrPrintOptions.image_type`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#image_type) Tiff ist und [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions#tiff_compression) gleich Ccitt3 oder Ccitt4 ist.|
| [printing_page](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/printing_page) | Gibt an, welche Seiten nicht gedruckt werden.|
| [quality](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/quality) | Ruft einen Wert ab, der die Qualität der generierten Bilder bestimmt, oder legt diesen fest<br/> Wird nur angewendet, wenn Seiten im Format `Jpeg` gespeichert werden. Der Standardwert ist 100|
| [image_type](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/image_type) | Ruft das Format der generierten Bilder ab oder legt es fest.<br/> Standardwert: PNG.|
| [is_cell_auto_fit](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Gibt an, ob die Breite und Höhe der Zellen automatisch an den Zellenwert angepasst wird.<br/> Der Standardwert ist false.|
| [one_page_per_sheet](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | Wenn OnePagePerSheet true ist, wird der gesamte Inhalt eines Blattes im Ergebnis nur auf einer Seite ausgegeben.<br/> Das Papierformat von „pagesetup“ und die anderen Einstellungen von „pagesetup“ sind ungültig<br/> wird weiterhin wirksam.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | Wenn AllColumnsInOnePagePerSheet true ist, wird der gesamte Spalteninhalt eines Blattes nur auf einer Seite im Ergebnis ausgegeben.<br/>Die Breite des Papierformats von „pagesetup“ und die anderen Einstellungen von „pagesetup“ sind ungültig<br/> wird weiterhin wirksam.|
| [draw_object_event_handler](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/draw_object_event_handler) | Implementiert diese Schnittstelle, um DrawObject und Bound beim Rendern abzurufen.|
| [chart_image_type](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Geben Sie beim Konvertieren den Bildtyp des Diagramms an.<br/> Standardwert: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Geben Sie den Dateinamen des eingebetteten Bildes in SVG an.<br/> Dies sollte ein vollständiger Pfad mit einem Verzeichnis wie „c:\\xpsEmbedded“ sein.|
| [svg_fit_to_view_port](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | Wenn diese Eigenschaft wahr ist, passt die generierte SVG-Datei in den Ansichtsport.|
| [only_area](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/only_area) | Wenn diese Eigenschaft true ist, wird eine Fläche ausgegeben und es wird keine Skalierung wirksam.|
| [text_rendering_hint](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Gibt die Qualität der Textwiedergabe an.<br/> Der Standardwert ist TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Gibt an, ob eine Glättung (Antialiasing) auf Linien und Kurven sowie die Kanten gefüllter Bereiche angewendet wird.<br/> Der Standardwert ist SmoothingMode.None|
| [transparent](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/transparent) | Gibt an, ob der Hintergrund des generierten Bildes transparent sein soll.|
| [pixel_format](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/pixel_format) | Ruft das Pixelformat für die generierten Bilder ab oder legt es fest.|
| [warning_callback](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/warning_callback) | Ruft einen Warnrückruf ab oder legt diesen fest.|
| [page_saving_callback](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/page_saving_callback) | Kontrollieren/Anzeigen des Fortschritts des Seitenspeichervorgangs.|
| [is_font_substitution_char_granularity](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |Gibt an, ob die Schriftart des Zeichens nur dann ersetzt werden soll, wenn die Zellenschriftart nicht damit kompatibel ist.|
| [page_index](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/page_index) | Ruft den 0-basierten Index der ersten zu speichernden Seite ab oder legt diesen fest.|
| [page_count](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/page_count) | Ruft die Anzahl der zu speichernden Seiten ab oder legt diese fest.|
| [is_optimized](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/is_optimized) | Gibt an, ob die Ausgabeelemente optimiert werden sollen.|
| [default_font](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/>Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese Zeichen anzuzeigen.<br/> Wenn diese Eigenschaft nicht festgelegt ist, verwendet Aspose.Cells die Standardschriftart des Systems, um diese Unicode-Zeichen anzuzeigen.|
| [check_workbook_default_font](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | Wenn Zeichen in Excel Unicode sind und nicht mit der richtigen Schriftart im Zellenstil festgelegt sind,<br/>Sie können als Block im PDF-Bild erscheinen.<br/> Setzen Sie dies auf „true“, um zu versuchen, die Standardschriftart der Arbeitsmappe zu verwenden, um diese Zeichen zuerst anzuzeigen.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Gibt an, ob eine leere Seite ausgegeben werden soll, wenn nichts zu drucken ist.|
| [gridline_type](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/gridline_type) | Ruft den Rasterlinientyp ab oder legt diesen fest.|
| [text_cross_type](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Ruft den Anzeigetexttyp ab oder legt diesen fest, wenn die Textbreite größer als die Zellenbreite ist.|
| [emf_type](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/emf_type) | Ruft einen EmfType ab oder legt diesen fest, der das Format der Metadatei angibt.<br/>Der Standardwert ist EmfPlusDual.|
| [default_edit_language](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Ruft die Standardbearbeitungssprache ab oder legt diese fest.|
| [sheet_set](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/sheet_set) |Ruft die zu rendernden Blätter ab oder legt diese fest. Standardmäßig sind alle sichtbaren Blätter in der Arbeitsmappe: [`SheetSet.visible`](/cells/python-net/de/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Einstellung zum Rendern der EMF-Metadatei.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_desired_size](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Legt die gewünschte Breite und Höhe des Bildes fest.|
| [set_desired_size](/cells/python-net/de/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Legt die gewünschte Breite und Höhe des Bildes fest.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  Siehe auch
* Modul [`aspose.cells.rendering`](..)
