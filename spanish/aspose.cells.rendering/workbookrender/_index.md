---
title: WorkbookRender clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender clase
 Representa una representación de libro de trabajo.
El constructor de esta clase debe usarse después de la modificación de la configuración de página, estilo de celda.



El tipo WorkbookRender expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [WorkbookRender(workbook, options)](/cells/python-net/es/aspose.cells.rendering/workbookrender/__init__/#Workbook-ImageOrPrintOptions) | La construcción de WorkbookRender|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [page_count](/cells/python-net/es/aspose.cells.rendering/workbookrender/page_count) | Obtiene el recuento total de páginas del libro.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [to_image(stream)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#io.RawIOBase) | Renderice todo el libro de trabajo como imagen Tiff para transmitir.|
| [to_image(filename)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#str) | Renderice todo el libro de trabajo como imagen Tiff en un archivo.|
| [to_image(page_index, file_name)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#int-str) | Renderizar cierta página a un archivo.|
| [to_image(page_index, stream)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_image/#int-io.RawIOBase) | Renderizar cierta página a una secuencia.|
| [to_printer(printer_name)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#str) | Renderizar el libro de trabajo a la impresora|
| [to_printer(printer_name, job_name)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Renderizar el libro de trabajo a la impresora|
| [to_printer(printer_settings)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Renderizar el libro de trabajo a la impresora|
| [to_printer(printer_settings, job_name)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Renderizar el libro de trabajo a la impresora|
| [to_printer(printer_name, print_page_index, print_page_count)](/cells/python-net/es/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Renderizar el libro de trabajo a la impresora|
| [get_page_size_inch(page_index)](/cells/python-net/es/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) |Obtenga el tamaño de página en pulgadas de la imagen de salida.|
| [custom_print(next_page_after_print, print_page_event_args)](/cells/python-net/es/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | El cliente puede controlar la configuración de la página de la impresora cuando imprima cada página usando esta función.|



###  Observaciones



###  Ver también
* módulo [aspose.cells.rendering](..)
