---
title: WorkbookRender Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 150
url: /de/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender Klasse
 Stellt ein Arbeitsmappen-Rendering dar.
Der Konstruktor dieser Klasse muss nach der Änderung des Seitenaufbaus und des Zellenstils verwendet werden.



Der Typ WorkbookRender macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | Das Konstrukt von WorkbookRender|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [page_count](/cells/python-net/de/aspose.cells.rendering/workbookrender/page_count) | Ruft die Gesamtseitenzahl der Arbeitsmappe ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Rendern Sie die gesamte Arbeitsmappe als TIFF-Bild zum Streamen.|
| [`to_image(self, filename)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_image/#str) | Rendern Sie die gesamte Arbeitsmappe als TIFF-Bild in eine Datei.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_image/#int-str) | Rendern Sie eine bestimmte Seite in einer Datei.|
| [`to_image(self, page_index, stream)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Rendern Sie bestimmte Seiten in einem Stream.|
| [`to_printer(self, printer_name)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_printer/#str) | Arbeitsmappe zum Drucker rendern|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Arbeitsmappe zum Drucker rendern|
| [`to_printer(self, printer_settings)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Arbeitsmappe zum Drucker rendern|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Arbeitsmappe zum Drucker rendern|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Arbeitsmappe zum Drucker rendern|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Ermitteln Sie die Seitengröße des Ausgabebilds in Zoll.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Mit dieser Funktion kann der Client die Seiteneinstellungen des Druckers steuern, wenn jede Seite gedruckt wird.|
| [`dispose(self)`](/cells/python-net/de/aspose.cells.rendering/workbookrender/dispose/#) | Gibt Ressourcen frei, die zum Rendern erstellt und verwendet werden.|



###  Bemerkungen



###  Siehe auch
* Modul [`aspose.cells.rendering`](..)
