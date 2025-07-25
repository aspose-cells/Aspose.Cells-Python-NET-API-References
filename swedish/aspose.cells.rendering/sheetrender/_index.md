---
title: SheetRender klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender klass
Representerar en kalkylbladsrendering som kan rendera kalkylblad till olika bilder såsom (BMP, PNG, JPEG, TIFF..)
Konstruktorn för denna klass måste användas efter modifiering av sidinställningar och cellstil.



Typen SheetRender avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | konstruktionen av SheetRender, behöver kalkylblad och ImageOrPrintOptions som parametrar|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [page_count](/cells/python-net/sv/aspose.cells.rendering/sheetrender/page_count) | Hämtar det totala sidantalet för det aktuella kalkylbladet.|
| [page_scale](/cells/python-net/sv/aspose.cells.rendering/sheetrender/page_scale) | Hämtar beräknad sidskala för arket.<br/> Returnerar den inställda skalan om [`PageSetup.zoom`](/cells/python-net/sv/aspose.cells/pagesetup#zoom) är satt. Annars returneras den beräknade skalan enligt [`PageSetup.fit_to_pages_wide`](/cells/python-net/sv/aspose.cells/pagesetup#fit_to_pages_wide) och [`PageSetup.fit_to_pages_tall`](/cells/python-net/sv/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_image/#int-str) | Rendera en viss sida till en fil.|
| [`to_image(self, page_index, stream)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Rendera en viss sida till en ström.|
| [`to_tiff(self, stream)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Rendera hela kalkylbladet som en Tiff-bild för att strömma.|
| [`to_tiff(self, filename)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_tiff/#str) | Rendera hela kalkylbladet som en Tiff-bild till en fil.|
| [`to_printer(self, printer_name)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#str) | Rendera kalkylblad till skrivare|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Rendera kalkylblad till skrivare|
| [`to_printer(self, printer_settings)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Rendera kalkylblad till skrivare|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Rendera kalkylblad till skrivare|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Rendera kalkylblad till skrivare|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Hämta sidstorleken i tum för utdatabilden.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Klienten kan styra skrivarens sidinställningar när varje sida skrivs ut med den här funktionen.|
| [`dispose(self)`](/cells/python-net/sv/aspose.cells.rendering/sheetrender/dispose/#) | Frigör resurser som skapats och använts för rendering.|



###  Se även
* modul [`aspose.cells.rendering`](..)
