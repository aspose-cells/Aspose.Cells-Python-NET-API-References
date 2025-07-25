---
title: SheetRender clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender clase
Representa un render de hoja de trabajo que puede renderizar la hoja de trabajo en varias imágenes como (BMP, PNG, JPEG, TIFF..)
El constructor de esta clase debe utilizarse después de modificar la configuración de la página y el estilo de celda.



El tipo SheetRender expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | La construcción de SheetRender, necesita la hoja de trabajo y ImageOrPrintOptions como parámetros|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [page_count](/cells/python-net/es/aspose.cells.rendering/sheetrender/page_count) | Obtiene el recuento total de páginas de la hoja de cálculo actual.|
| [page_scale](/cells/python-net/es/aspose.cells.rendering/sheetrender/page_scale) | Obtiene la escala de página calculada de la hoja.<br/> Devuelve la escala establecida si se establece [`PageSetup.zoom`](/cells/python-net/es/aspose.cells/pagesetup#zoom). De lo contrario, devuelve la escala calculada según [`PageSetup.fit_to_pages_wide`](/cells/python-net/es/aspose.cells/pagesetup#fit_to_pages_wide) y [`PageSetup.fit_to_pages_tall`](/cells/python-net/es/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_image/#int-str) | Representar determinada página en un archivo.|
| [`to_image(self, page_index, stream)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Representar una página determinada en una secuencia.|
| [`to_tiff(self, stream)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Representar toda la hoja de cálculo como imagen Tiff para transmitir.|
| [`to_tiff(self, filename)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_tiff/#str) | Representar toda la hoja de cálculo como imagen Tiff en un archivo.|
| [`to_printer(self, printer_name)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#str) | Renderizar hoja de cálculo a impresora|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Renderizar hoja de cálculo a impresora|
| [`to_printer(self, printer_settings)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Renderizar hoja de cálculo a impresora|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Renderizar hoja de cálculo a impresora|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Renderizar hoja de cálculo a impresora|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Obtenga el tamaño de página en pulgadas de la imagen de salida.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | El cliente puede controlar la configuración de la página de la impresora al imprimir cada página utilizando esta función.|
| [`dispose(self)`](/cells/python-net/es/aspose.cells.rendering/sheetrender/dispose/#) | Libera recursos creados y utilizados para la renderización.|



###  Ver también
* módulo [`aspose.cells.rendering`](..)
