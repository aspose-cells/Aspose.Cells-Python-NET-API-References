---
title: WorkbookRender clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 150
url: /es/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender clase
 Representa una representación de un libro de trabajo.
El constructor de esta clase debe utilizarse después de modificar la configuración de la página y el estilo de celda.



El tipo WorkbookRender expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | La construcción de WorkbookRender|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [page_count](/cells/python-net/es/aspose.cells.rendering/workbookrender/page_count) | Obtiene el recuento total de páginas del libro de trabajo.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Representar todo el libro de trabajo como una imagen TIFF para transmitir.|
| [`to_image(self, filename)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#str) | Representar todo el libro de trabajo como una imagen Tiff en un archivo.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#int-str) | Representar determinada página en un archivo.|
| [`to_image(self, page_index, stream)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Representar una página determinada en una secuencia.|
| [`to_printer(self, printer_name)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#str) | Representar el libro de trabajo en la impresora|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Representar el libro de trabajo en la impresora|
| [`to_printer(self, printer_settings)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Representar el libro de trabajo en la impresora|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Representar el libro de trabajo en la impresora|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Representar el libro de trabajo en la impresora|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Obtenga el tamaño de página en pulgadas de la imagen de salida.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | El cliente puede controlar la configuración de la página de la impresora al imprimir cada página utilizando esta función.|
| [`dispose(self)`](/cells/python-net/es/aspose.cells.rendering/workbookrender/dispose/#) | Libera recursos creados y utilizados para la renderización.|



###  Observaciones



###  Ver también
* módulo [`aspose.cells.rendering`](..)
