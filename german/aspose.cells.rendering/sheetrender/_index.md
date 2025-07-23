---
title: SheetRender Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender Klasse
Stellt einen Arbeitsblatt-Render dar, der Arbeitsblätter in verschiedene Bilder rendern kann, z. B. (BMP, PNG, JPEG, TIFF …)
Der Konstruktor dieser Klasse muss nach der Änderung des Seitenaufbaus und des Zellenstils verwendet werden.



Der Typ SheetRender macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | Die Konstruktion von SheetRender benötigt Arbeitsblatt und ImageOrPrintOptions als Parameter|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [page_count](/cells/python-net/de/aspose.cells.rendering/sheetrender/page_count) | Ruft die Gesamtseitenzahl des aktuellen Arbeitsblatts ab.|
| [page_scale](/cells/python-net/de/aspose.cells.rendering/sheetrender/page_scale) | Ruft den berechneten Seitenmaßstab des Blattes ab.<br/> Gibt den eingestellten Maßstab zurück, wenn [`PageSetup.zoom`](/cells/python-net/de/aspose.cells/pagesetup#zoom) eingestellt ist. Andernfalls wird der berechnete Maßstab gemäß [`PageSetup.fit_to_pages_wide`](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_wide) und [`PageSetup.fit_to_pages_tall`](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_tall) zurückgegeben.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_image/#int-str) | Rendern Sie eine bestimmte Seite in einer Datei.|
| [`to_image(self, page_index, stream)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Rendern Sie bestimmte Seiten in einem Stream.|
| [`to_tiff(self, stream)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Rendern Sie das gesamte Arbeitsblatt als TIFF-Bild zum Streamen.|
| [`to_tiff(self, filename)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_tiff/#str) | Rendern Sie das gesamte Arbeitsblatt als TIFF-Bild in eine Datei.|
| [`to_printer(self, printer_name)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str) | Arbeitsblatt zum Drucker rendern|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Arbeitsblatt zum Drucker rendern|
| [`to_printer(self, printer_settings)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Arbeitsblatt zum Drucker rendern|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Arbeitsblatt zum Drucker rendern|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Arbeitsblatt zum Drucker rendern|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Ermitteln Sie die Seitengröße des Ausgabebilds in Zoll.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Mit dieser Funktion kann der Client die Seiteneinstellungen des Druckers steuern, wenn jede Seite gedruckt wird.|
| [`dispose(self)`](/cells/python-net/de/aspose.cells.rendering/sheetrender/dispose/#) | Gibt Ressourcen frei, die zum Rendern erstellt und verwendet werden.|



###  Siehe auch
* Modul [`aspose.cells.rendering`](..)
