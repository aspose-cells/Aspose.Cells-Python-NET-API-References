---
title: PdfSaveOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1220
url: /es/aspose.cells/pdfsaveoptions/
is_root: false
---
##  PdfSaveOptions clase
Representa las opciones para guardar un archivo pdf.



**Herencia:** [`PdfSaveOptions`](/cells/python-net/aspose.cells/pdfsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)



El tipo PdfSaveOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/pdfsaveoptions/__init__/#) | Crea las opciones para guardar el archivo pdf.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells/pdfsaveoptions/save_format) | Obtiene el formato del archivo guardado.|
| [clear_data](/cells/python-net/es/aspose.cells/pdfsaveoptions/clear_data) | Deje el libro vacío después de guardar el archivo.|
| [cached_file_folder](/cells/python-net/es/aspose.cells/pdfsaveoptions/cached_file_folder) | La carpeta de archivos en caché se utiliza para almacenar algunos datos de gran tamaño.|
| [validate_merged_areas](/cells/python-net/es/aspose.cells/pdfsaveoptions/validate_merged_areas) | Indica si validar las celdas combinadas antes de guardar el archivo.|
| [merge_areas](/cells/python-net/es/aspose.cells/pdfsaveoptions/merge_areas) | Indica si fusionar las áreas de formato condicional y validación antes de guardar el archivo.|
| [create_directory](/cells/python-net/es/aspose.cells/pdfsaveoptions/create_directory) | Si es verdadero y el directorio no existe, el directorio se creará automáticamente antes de guardar el archivo.|
| [sort_names](/cells/python-net/es/aspose.cells/pdfsaveoptions/sort_names) | Indica si se ordenan los nombres definidos antes de guardar el archivo.|
| [sort_external_names](/cells/python-net/es/aspose.cells/pdfsaveoptions/sort_external_names) | Indica si se ordenan los nombres externos definidos antes de guardar el archivo.|
| [refresh_chart_cache](/cells/python-net/es/aspose.cells/pdfsaveoptions/refresh_chart_cache) | Indica si se actualizan los datos de la caché del gráfico.|
| [warning_callback](/cells/python-net/es/aspose.cells/pdfsaveoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [update_smart_art](/cells/python-net/es/aspose.cells/pdfsaveoptions/update_smart_art) | Indica si se actualiza la configuración de arte inteligente.<br/> El valor predeterminado es falso.|
| [default_font](/cells/python-net/es/aspose.cells/pdfsaveoptions/default_font) | Cuando los caracteres en Excel son Unicode y no se configuran con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloque en pdf, imagen.<br/>Configure la fuente predeterminada, como MingLiu o MS Gothic, para mostrar estos caracteres.<br/> Si esta propiedad no está configurada, Aspose.Cells utilizará la fuente predeterminada del sistema para mostrar estos caracteres Unicode.|
| [check_workbook_default_font](/cells/python-net/es/aspose.cells/pdfsaveoptions/check_workbook_default_font) | Cuando los caracteres en Excel son Unicode y no se configuran con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloque en pdf, imagen.<br/> Establezca esto en verdadero para intentar usar la fuente predeterminada del libro para mostrar estos caracteres primero.|
| [check_font_compatibility](/cells/python-net/es/aspose.cells/pdfsaveoptions/check_font_compatibility) | Indica si se debe verificar la compatibilidad de fuentes para cada carácter del texto.|
| [is_font_substitution_char_granularity](/cells/python-net/es/aspose.cells/pdfsaveoptions/is_font_substitution_char_granularity) |Indica si solo se debe sustituir la fuente del carácter cuando la fuente de la celda no sea compatible con él.|
| [one_page_per_sheet](/cells/python-net/es/aspose.cells/pdfsaveoptions/one_page_per_sheet) | Si OnePagePerSheet es verdadero, todo el contenido de una hoja se generará en una sola página.<br/> El tamaño del papel de pagesetup no será válido y las demás configuraciones de pagesetup<br/> seguirá surtiendo efecto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/es/aspose.cells/pdfsaveoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet es verdadero, todo el contenido de la columna de una hoja se generará en una sola página como resultado.<br/> Se ignorará el ancho del tamaño del papel de pagesetup y el resto de configuraciones de pagesetup<br/> seguirá surtiendo efecto.|
| [ignore_error](/cells/python-net/es/aspose.cells/pdfsaveoptions/ignore_error) | Indica si necesita ocultar el error durante el renderizado.<br/> El error puede ser un error en la forma, la imagen, la representación del gráfico, etc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/es/aspose.cells/pdfsaveoptions/output_blank_page_when_nothing_to_print) | Indica si se debe generar una página en blanco cuando no hay nada que imprimir.|
| [page_index](/cells/python-net/es/aspose.cells/pdfsaveoptions/page_index) | Obtiene o establece el índice basado en 0 de la primera página que se guardará.|
| [page_count](/cells/python-net/es/aspose.cells/pdfsaveoptions/page_count) | Obtiene o establece el número de páginas que se guardarán.|
| [printing_page_type](/cells/python-net/es/aspose.cells/pdfsaveoptions/printing_page_type) | Indica qué páginas no se imprimirán.|
| [gridline_type](/cells/python-net/es/aspose.cells/pdfsaveoptions/gridline_type) | Obtiene o establece el tipo de línea de cuadrícula.|
| [text_cross_type](/cells/python-net/es/aspose.cells/pdfsaveoptions/text_cross_type) | Obtiene o establece la visualización del tipo de texto cuando el ancho del texto es mayor que el ancho de la celda.|
| [default_edit_language](/cells/python-net/es/aspose.cells/pdfsaveoptions/default_edit_language) | Obtiene o establece el idioma de edición predeterminado.|
| [sheet_set](/cells/python-net/es/aspose.cells/pdfsaveoptions/sheet_set) |Obtiene o establece las hojas que se van a representar. El valor predeterminado son todas las hojas visibles del libro: [`SheetSet.visible`](/cells/python-net/es/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/es/aspose.cells/pdfsaveoptions/draw_object_event_handler) | Implementa esta interfaz para obtener DrawObject y Bound al renderizar.|
| [page_saving_callback](/cells/python-net/es/aspose.cells/pdfsaveoptions/page_saving_callback) | Controlar/Indicar el progreso del proceso de guardado de la página.|
| [emf_render_setting](/cells/python-net/es/aspose.cells/pdfsaveoptions/emf_render_setting) | Configuración para renderizar el metarchivo Emf.|
| [embed_standard_windows_fonts](/cells/python-net/es/aspose.cells/pdfsaveoptions/embed_standard_windows_fonts) | Verdadero para incrustar fuentes de tipo verdadero.<br/>Afecta sólo a los caracteres ASCII 32-127.<br/>Las fuentes para códigos de caracteres superiores a 127 siempre están incrustadas.<br/>Las fuentes siempre están integradas para los estándares PDF/A-1a, PDF/A-1b.<br/> El valor predeterminado es verdadero.|
| [bookmark](/cells/python-net/es/aspose.cells/pdfsaveoptions/bookmark) | Obtiene y establece el objeto [`PdfBookmarkEntry`](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry).|
| [compliance](/cells/python-net/es/aspose.cells/pdfsaveoptions/compliance) | Obtiene o establece el nivel de cumplimiento de los estándares PDF para los documentos de salida.|
| [security_options](/cells/python-net/es/aspose.cells/pdfsaveoptions/security_options) | Configure estas opciones cuando se necesite seguridad en el resultado de xls2pdf.|
| [image_type](/cells/python-net/es/aspose.cells/pdfsaveoptions/image_type) |Representa el tipo de imagen al convertir el gráfico y la forma.|
| [calculate_formula](/cells/python-net/es/aspose.cells/pdfsaveoptions/calculate_formula) | Indica si se deben calcular fórmulas antes de guardar el archivo pdf.|
| [pdf_compression](/cells/python-net/es/aspose.cells/pdfsaveoptions/pdf_compression) | Indicar el algoritmo de compresión.|
| [created_time](/cells/python-net/es/aspose.cells/pdfsaveoptions/created_time) | Obtiene y establece la hora de generación del documento pdf.|
| [producer](/cells/python-net/es/aspose.cells/pdfsaveoptions/producer) | Obtiene y establece el productor del documento pdf generado.|
| [optimization_type](/cells/python-net/es/aspose.cells/pdfsaveoptions/optimization_type) | Obtiene y establece el tipo de optimización de pdf.|
| [custom_properties_export](/cells/python-net/es/aspose.cells/pdfsaveoptions/custom_properties_export) | Obtiene o establece un valor que determina la forma en que se exportan [`CustomDocumentPropertyCollection`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection) al archivo PDF. El valor predeterminado es Ninguno.|
| [export_document_structure](/cells/python-net/es/aspose.cells/pdfsaveoptions/export_document_structure) | Indica si se exporta la estructura del documento.|
| [display_doc_title](/cells/python-net/es/aspose.cells/pdfsaveoptions/display_doc_title) | Indica si la barra de título de la ventana debe mostrar el título del documento.|
| [font_encoding](/cells/python-net/es/aspose.cells/pdfsaveoptions/font_encoding) | Obtiene o establece la codificación de fuentes incrustadas en pdf.|
| [watermark](/cells/python-net/es/aspose.cells/pdfsaveoptions/watermark) | Obtiene o establece una marca de agua para la salida.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_image_resample](/cells/python-net/es/aspose.cells/pdfsaveoptions/set_image_resample/#int-int) | Establece el PPI (píxeles por pulgada) deseado de imágenes de remuestreo y calidad jpeg.<br/> Todas las imágenes se convertirán a JPEG con la configuración de calidad especificada,<br/> y se volverán a muestrear las imágenes que sean mayores que el PPI (píxeles por pulgada) especificado.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`CustomDocumentPropertyCollection`](/cells/python-net/es/aspose.cells.properties/customdocumentpropertycollection)
* clase [`PaginatedSaveOptions`](/cells/python-net/es/aspose.cells/paginatedsaveoptions)
* clase [`PdfBookmarkEntry`](/cells/python-net/es/aspose.cells.rendering/pdfbookmarkentry)
* clase [`PdfSaveOptions`](/cells/python-net/es/aspose.cells/pdfsaveoptions)
* clase [`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)
