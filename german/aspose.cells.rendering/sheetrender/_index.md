---
title: SheetRender Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 100
url: /de/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender Klasse
Stellt ein Arbeitsblatt dar, das ein Arbeitsblatt in verschiedene Bilder wie (BMP, PNG, JPEG, TIFF..) rendern kann.
Der Konstruktor dieser Klasse muss nach der Änderung von pagesetup, cell style, verwendet werden.



Der Typ SheetRender macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [SheetRender(worksheet, options)](/cells/python-net/de/aspose.cells.rendering/sheetrender/__init__/#Worksheet-ImageOrPrintOptions) | das Konstrukt von SheetRender, benötigen Arbeitsblatt und ImageOrPrintOptions als Parameter|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [page_count](/cells/python-net/de/aspose.cells.rendering/sheetrender/page_count) | Ruft die Gesamtseitenzahl des aktuellen Arbeitsblatts ab.|
| [page_scale](/cells/python-net/de/aspose.cells.rendering/sheetrender/page_scale) | Ruft den berechneten Seitenmaßstab des Blatts ab.<br/> Gibt die eingestellte Skala zurück, wenn [PageSetup.zoom](/cells/python-net/de/aspose.cells/pagesetup#zoom) eingestellt ist. Gibt andernfalls die berechnete Skala gemäß [PageSetup.fit_to_pages_wide](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_wide) und [PageSetup.fit_to_pages_tall](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_tall) zurück.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [to_image(page_index, file_name)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_image/#int-str) | Bestimmte Seite in eine Datei rendern.|
| [to_image(page_index, stream)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Bestimmte Seite in einem Stream rendern.|
| [to_tiff(stream)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Rendern Sie das gesamte Arbeitsblatt als Tiff-Bild zum Streamen.|
| [to_tiff(filename)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_tiff/#str) | Rendern Sie das gesamte Arbeitsblatt als Tiff-Bild in eine Datei.|
| [to_printer(printer_name)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str) | Arbeitsblatt auf Drucker übertragen|
| [to_printer(printer_name, job_name)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Arbeitsblatt auf Drucker übertragen|
| [to_printer(printer_settings)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Arbeitsblatt auf Drucker übertragen|
| [to_printer(printer_settings, job_name)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Arbeitsblatt auf Drucker übertragen|
| [to_printer(printer_name, print_page_index, print_page_count)](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Arbeitsblatt auf Drucker übertragen|
| [get_page_size_inch(page_index)](/cells/python-net/de/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) |Holen Sie sich die Seitengröße in Zoll des Ausgabebildes.|
| [custom_print(next_page_after_print, print_page_event_args)](/cells/python-net/de/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Der Client kann die Seiteneinstellung des Druckers beim Drucken jeder Seite mit dieser Funktion steuern.|



###  Siehe auch
* Modul [aspose.cells.rendering](..)
