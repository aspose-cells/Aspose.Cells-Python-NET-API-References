---
title: PptxSaveOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1230
url: /es/aspose.cells/pptxsaveoptions/
is_root: false
---
##  PptxSaveOptions clase
Representa las opciones de guardar pptx.



**Herencia:** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)



El tipo PptxSaveOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/pptxsaveoptions/__init__/#) | Representa las opciones de guardar pptx.|
| [__init__](/cells/python-net/es/aspose.cells/pptxsaveoptions/__init__/#bool) | Representa opciones para guardar el archivo .pptx.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells/pptxsaveoptions/save_format) | Obtiene el formato del archivo guardado.|
| [clear_data](/cells/python-net/es/aspose.cells/pptxsaveoptions/clear_data) | Deje el libro vacío después de guardar el archivo.|
| [cached_file_folder](/cells/python-net/es/aspose.cells/pptxsaveoptions/cached_file_folder) | La carpeta de archivos en caché se utiliza para almacenar algunos datos de gran tamaño.|
| [validate_merged_areas](/cells/python-net/es/aspose.cells/pptxsaveoptions/validate_merged_areas) | Indica si validar las celdas combinadas antes de guardar el archivo.|
| [merge_areas](/cells/python-net/es/aspose.cells/pptxsaveoptions/merge_areas) | Indica si fusionar las áreas de formato condicional y validación antes de guardar el archivo.|
| [create_directory](/cells/python-net/es/aspose.cells/pptxsaveoptions/create_directory) | Si es verdadero y el directorio no existe, el directorio se creará automáticamente antes de guardar el archivo.|
| [sort_names](/cells/python-net/es/aspose.cells/pptxsaveoptions/sort_names) | Indica si se ordenan los nombres definidos antes de guardar el archivo.|
| [sort_external_names](/cells/python-net/es/aspose.cells/pptxsaveoptions/sort_external_names) | Indica si se ordenan los nombres externos definidos antes de guardar el archivo.|
| [refresh_chart_cache](/cells/python-net/es/aspose.cells/pptxsaveoptions/refresh_chart_cache) | Indica si se actualizan los datos de la caché del gráfico.|
| [warning_callback](/cells/python-net/es/aspose.cells/pptxsaveoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [update_smart_art](/cells/python-net/es/aspose.cells/pptxsaveoptions/update_smart_art) | Indica si se actualiza la configuración de arte inteligente.<br/> El valor predeterminado es falso.|
| [default_font](/cells/python-net/es/aspose.cells/pptxsaveoptions/default_font) | Cuando los caracteres en Excel son Unicode y no se configuran con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloque en pdf, imagen.<br/>Configure la fuente predeterminada, como MingLiu o MS Gothic, para mostrar estos caracteres.<br/> Si esta propiedad no está configurada, Aspose.Cells utilizará la fuente predeterminada del sistema para mostrar estos caracteres Unicode.|
| [check_workbook_default_font](/cells/python-net/es/aspose.cells/pptxsaveoptions/check_workbook_default_font) | Cuando los caracteres en Excel son Unicode y no se configuran con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloque en pdf, imagen.<br/> Establezca esto en verdadero para intentar usar la fuente predeterminada del libro para mostrar estos caracteres primero.|
| [check_font_compatibility](/cells/python-net/es/aspose.cells/pptxsaveoptions/check_font_compatibility) | Indica si se debe verificar la compatibilidad de fuentes para cada carácter del texto.|
| [is_font_substitution_char_granularity](/cells/python-net/es/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |Indica si solo se debe sustituir la fuente del carácter cuando la fuente de la celda no sea compatible con él.|
| [one_page_per_sheet](/cells/python-net/es/aspose.cells/pptxsaveoptions/one_page_per_sheet) | Si OnePagePerSheet es verdadero, todo el contenido de una hoja se generará en una sola página.<br/> El tamaño del papel de pagesetup no será válido y las demás configuraciones de pagesetup<br/> seguirá surtiendo efecto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/es/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet es verdadero, todo el contenido de la columna de una hoja se generará en una sola página como resultado.<br/> Se ignorará el ancho del tamaño del papel de pagesetup y el resto de configuraciones de pagesetup<br/> seguirá surtiendo efecto.|
| [ignore_error](/cells/python-net/es/aspose.cells/pptxsaveoptions/ignore_error) | Indica si necesita ocultar el error durante el renderizado.<br/> El error puede ser un error en la forma, la imagen, la representación del gráfico, etc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/es/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) | Indica si se debe generar una página en blanco cuando no hay nada que imprimir.|
| [page_index](/cells/python-net/es/aspose.cells/pptxsaveoptions/page_index) | Obtiene o establece el índice basado en 0 de la primera página que se guardará.|
| [page_count](/cells/python-net/es/aspose.cells/pptxsaveoptions/page_count) | Obtiene o establece el número de páginas que se guardarán.|
| [printing_page_type](/cells/python-net/es/aspose.cells/pptxsaveoptions/printing_page_type) | Indica qué páginas no se imprimirán.|
| [gridline_type](/cells/python-net/es/aspose.cells/pptxsaveoptions/gridline_type) | Obtiene o establece el tipo de línea de cuadrícula.|
| [text_cross_type](/cells/python-net/es/aspose.cells/pptxsaveoptions/text_cross_type) | Obtiene o establece la visualización del tipo de texto cuando el ancho del texto es mayor que el ancho de la celda.|
| [default_edit_language](/cells/python-net/es/aspose.cells/pptxsaveoptions/default_edit_language) | Obtiene o establece el idioma de edición predeterminado.|
| [sheet_set](/cells/python-net/es/aspose.cells/pptxsaveoptions/sheet_set) |Obtiene o establece las hojas que se van a representar. El valor predeterminado son todas las hojas visibles del libro: [`SheetSet.visible`](/cells/python-net/es/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/es/aspose.cells/pptxsaveoptions/draw_object_event_handler) | Implementa esta interfaz para obtener DrawObject y Bound al renderizar.|
| [page_saving_callback](/cells/python-net/es/aspose.cells/pptxsaveoptions/page_saving_callback) | Controlar/Indicar el progreso del proceso de guardado de la página.|
| [emf_render_setting](/cells/python-net/es/aspose.cells/pptxsaveoptions/emf_render_setting) | Configuración para renderizar el metarchivo Emf.|
| [ignore_hidden_rows](/cells/python-net/es/aspose.cells/pptxsaveoptions/ignore_hidden_rows) | Indica si se ignoran las filas ocultas al convertir Excel a PowerPoint.|
| [adjust_font_size_for_row_type](/cells/python-net/es/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) | Representa qué tipo de línea necesita ajustarse al tamaño de fuente si la altura de la fila es pequeña.|
| [export_view_type](/cells/python-net/es/aspose.cells/pptxsaveoptions/export_view_type) | Obtiene y establece el tipo de visualización al exportar a PowerPoint.<br/> El tipo de exportación predeterminado funciona como impresión.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`PaginatedSaveOptions`](/cells/python-net/es/aspose.cells/paginatedsaveoptions)
* clase [`PptxSaveOptions`](/cells/python-net/es/aspose.cells/pptxsaveoptions)
* clase [`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)
