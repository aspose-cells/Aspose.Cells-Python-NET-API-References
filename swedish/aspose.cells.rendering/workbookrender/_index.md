---
title: WorkbookRender klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 150
url: /sv/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender klass
 Representerar en arbetsboksrendering.
Konstruktorn för denna klass måste användas efter modifiering av sidinställningar och cellstil.



Typen WorkbookRender avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | Konstruktionen av WorkbookRender|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [page_count](/cells/python-net/sv/aspose.cells.rendering/workbookrender/page_count) | Hämtar det totala sidantalet i arbetsboken.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Rendera hela arbetsboken som en Tiff-bild för att strömma.|
| [`to_image(self, filename)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_image/#str) | Rendera hela arbetsboken som en Tiff-bild till en fil.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_image/#int-str) | Rendera en viss sida till en fil.|
| [`to_image(self, page_index, stream)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Rendera en viss sida till en ström.|
| [`to_printer(self, printer_name)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_printer/#str) | Rendera arbetsbok till skrivare|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Rendera arbetsbok till skrivare|
| [`to_printer(self, printer_settings)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Rendera arbetsbok till skrivare|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Rendera arbetsbok till skrivare|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Rendera arbetsbok till skrivare|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Hämta sidstorleken i tum för utdatabilden.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Klienten kan styra skrivarens sidinställningar när varje sida skrivs ut med den här funktionen.|
| [`dispose(self)`](/cells/python-net/sv/aspose.cells.rendering/workbookrender/dispose/#) | Frigör resurser som skapats och använts för rendering.|



###  Anmärkningar



###  Se även
* modul [`aspose.cells.rendering`](..)
