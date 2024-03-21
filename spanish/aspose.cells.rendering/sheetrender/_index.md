---
title: SheetRender clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender clase
Representa una representación de una hoja de trabajo que puede representar una hoja de trabajo en varias imágenes, como (BMP, PNG, JPEG, TIFF..)
El constructor de esta clase debe usarse después de modificar la configuración de página y el estilo de celda.



El tipo SheetRender expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | la construcción de SheetRender, necesita hoja de trabajo e ImageOrPrintOptions como parámetros|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [page_count](/cells/python-net/es/aspose.cells.rendering/sheetrender/page_count) | Obtiene el recuento total de páginas de la hoja de trabajo actual.|
| [page_scale](/cells/python-net/es/aspose.cells.rendering/sheetrender/page_scale) | Obtiene la escala de página calculada de la hoja.<br/> Devuelve la escala establecida si se establece [`PageSetup.zoom`](/cells/python-net/es/aspose.cells/pagesetup#zoom). En caso contrario, devuelve la escala calculada según [`PageSetup.fit_to_pages_wide`](/cells/python-net/es/aspose.cells/pagesetup#fit_to_pages_wide) y [`PageSetup.fit_to_pages_tall`](/cells/python-net/es/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Métodos
| Método| Descripción|
| :- | :- |
| [to_image](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_image/#int-str) |Renderiza cierta página en un archivo.|
| [to_image](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Renderiza cierta página en una secuencia.|
| [to_tiff](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Renderice toda la hoja de trabajo como imagen Tiff para transmitirla.|
| [to_tiff](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_tiff/#str) | Renderice toda la hoja de trabajo como imagen Tiff en un archivo.|
| [to_printer](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#str) | Renderizar hoja de trabajo a impresora|
| [to_printer](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Renderizar hoja de trabajo a impresora|
| [to_printer](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Renderizar hoja de trabajo a impresora|
| [to_printer](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Renderizar hoja de trabajo a impresora|
| [to_printer](/cells/python-net/es/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Renderizar hoja de trabajo a impresora|
| [get_page_size_inch](/cells/python-net/es/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Obtenga el tamaño de página en pulgadas de la imagen de salida.|
| [custom_print](/cells/python-net/es/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | El cliente puede controlar la configuración de página de la impresora cuando imprime cada página usando esta función.|
| [dispose](/cells/python-net/es/aspose.cells.rendering/sheetrender/dispose/#) | Libera recursos creados y utilizados para la renderización.|



###  Ver también
* módulo [`aspose.cells.rendering`](..)
