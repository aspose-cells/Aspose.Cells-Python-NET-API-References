---
title: SheetRender klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender klass
Representerar en kalkylbladsrendering som kan rendera kalkylblad till olika bilder som (BMP, PNG, JPEG, TIFF..)
Konstruktorn för denna klass måste användas efter modifiering av sidinställningar, cellstil.



Typen SheetRender avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | konstruktionen av SheetRender, behöver kalkylblad och ImageOrPrintOptions som parametrar|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [page_count](/cells/python-net/sv/aspose.cells.rendering/sheetrender/page_count) | Hämtar det totala sidantal för aktuellt kalkylblad.|
| [page_scale](/cells/python-net/sv/aspose.cells.rendering/sheetrender/page_scale) | Får beräknad sidskala på arket.<br/> Returnerar den inställda skalan om [`PageSetup.zoom`](/cells/python-net/sv/aspose.cells/pagesetup#zoom) är inställd. I annat fall returnerar den beräknade skalan enligt [`PageSetup.fit_to_pages_wide`](/cells/python-net/sv/aspose.cells/pagesetup#fit_to_pages_wide) och [`PageSetup.fit_to_pages_tall`](/cells/python-net/sv/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [to_image](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_image/#int-str) |Gör en viss sida till en fil.|
| [to_image](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Gör en viss sida till en stream.|
| [to_tiff](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Gör hela kalkylbladet som Tiff-bild för att streama.|
| [to_tiff](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_tiff/#str) | Gör hela kalkylbladet som Tiff-bild till en fil.|
| [to_printer](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#str) | Återge arbetsbladet till skrivaren|
| [to_printer](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Återge arbetsbladet till skrivaren|
| [to_printer](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Återge arbetsbladet till skrivaren|
| [to_printer](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Återge arbetsbladet till skrivaren|
| [to_printer](/cells/python-net/sv/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Återge arbetsbladet till skrivaren|
| [get_page_size_inch](/cells/python-net/sv/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Få sidstorlek i tum av utdatabilden.|
| [custom_print](/cells/python-net/sv/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Klienten kan styra sidinställningarna för skrivaren när du skriver ut varje sida med denna funktion.|
| [dispose](/cells/python-net/sv/aspose.cells.rendering/sheetrender/dispose/#) | Frigör resurser som skapats och används för rendering.|



###  Se även
* modul [`aspose.cells.rendering`](..)
