---
title: EbookSaveOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions clase
Representa las opciones para guardar archivos de libros electrónicos.



**Herencia:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)



El tipo EbookSaveOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/__init__/#) | Crea opciones para guardar archivos de libros electrónicos.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/save_format) | Obtiene el formato del archivo guardado.|
| [clear_data](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/clear_data) | Deje el libro vacío después de guardar el archivo.|
| [cached_file_folder](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | La carpeta de archivos en caché se utiliza para almacenar algunos datos de gran tamaño.|
| [validate_merged_areas](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | Indica si validar las celdas combinadas antes de guardar el archivo.|
| [merge_areas](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/merge_areas) | Indica si fusionar las áreas de formato condicional y validación antes de guardar el archivo.|
| [create_directory](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/create_directory) | Si es verdadero y el directorio no existe, el directorio se creará automáticamente antes de guardar el archivo.|
| [sort_names](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/sort_names) | Indica si se ordenan los nombres definidos antes de guardar el archivo.|
| [sort_external_names](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/sort_external_names) | Indica si se ordenan los nombres externos definidos antes de guardar el archivo.|
| [refresh_chart_cache](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | Indica si se actualizan los datos de la caché del gráfico.|
| [warning_callback](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [update_smart_art](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/update_smart_art) | Indica si se actualiza la configuración de arte inteligente.<br/> El valor predeterminado es falso.|
| [ignore_invisible_shapes](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | Indique si exportar esas formas no visibles|
| [page_title](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/page_title) | El título de la página html.<br/> Solo para guardar en secuencia html.|
| [attached_files_directory](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | El directorio en el que se guardarán los archivos adjuntos.<br/> Solo para guardar en secuencia html.|
| [attached_files_url_prefix](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | Especifique el prefijo de URL de los archivos adjuntos, como la imagen, en el archivo html.<br/> Solo para guardar en secuencia html.|
| [default_font_name](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/default_font_name) | Especifique el nombre de fuente predeterminado para exportar html, la fuente predeterminada se usará cuando la fuente del estilo no exista.<br/>Si esta propiedad es nula, Aspose.Cells utilizará una fuente universal que tenga la misma familia que la fuente original.<br/> el valor predeterminado es nulo.|
| [worksheet_scalable](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | Indica si acercar o alejar el html a través del nivel de zoom de la hoja de trabajo al guardar el archivo en html, el valor predeterminado es falso.|
| [is_export_comments](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/is_export_comments) |Indica si al exportar comentarios al guardar el archivo en html, el valor predeterminado es falso.|
| [export_comments_type](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_comments_type) | Representa el tipo de exportación de comentarios a archivos html.|
| [disable_downlevel_revealed_comments](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | Indica que si se desactivan los comentarios condicionales revelados en el nivel inferior al exportar un archivo a HTML, el valor predeterminado es falso.|
| [is_exp_image_to_temp_dir](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | Indica si se exportan archivos de imagen al directorio temporal.<br/> Solo para guardar en secuencia html.|
| [image_scalable](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/image_scalable) | Indica si se utiliza una unidad escalable para describir el ancho de la imagen.<br/>cuando se utiliza una unidad escalable para describir el ancho de la columna.<br/> El valor por defecto es verdadero.|
| [width_scalable](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/width_scalable) | Indica si se exporta el ancho de columna en unidad de escala a html.<br/> El valor predeterminado es falso.|
| [export_single_tab](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_single_tab) | Indica si se exporta la pestaña única cuando el archivo solo tiene una hoja de trabajo.<br/> El valor predeterminado es falso.|
| [export_images_as_base64](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | Especifica si las imágenes se guardan en formato Base64 en HTML, MHTML o EPUB.|
| [export_active_worksheet_only](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | Indica si solo se exporta la hoja de trabajo activa a un archivo html.<br/>Si es verdadero, solo se exportará la hoja de trabajo activa al archivo html;<br/>Si es falso, se exportará todo el libro a un archivo html.<br/> El valor predeterminado es falso.|
| [export_print_area_only](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_print_area_only) | Indica si solo se exporta el área de impresión a un archivo html. El valor predeterminado es falso.|
| [export_area](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_area) | Obtiene o establece el CellArea de exportación de la hoja de trabajo activa actual.<br/>Si configura este atributo, se omitirá el área de impresión de la hoja de trabajo activa actual.<br/> Solo se exportará el área especificada al guardar el archivo en html.|
| [parse_html_tag_in_cell](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) |Indica si la etiqueta html (como `<div></div>`) en la celda debe analizarse como valor de celda o conservarse tal como está.<br/> El valor por defecto es verdadero.|
| [html_cross_string_type](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | Indica si una cadena entre celdas se mostrará de la misma manera que MS Excel al guardar un archivo de Excel en formato html.<br/>De forma predeterminada, el valor es Predeterminado, por lo que, para cadenas entre celdas, hay poca diferencia entre los archivos html creados por Aspose.Cells y MS Excel.<br/> Pero el rendimiento para crear archivos HTML grandes, establecer el valor en Cruz sería varias veces más rápido que configurarlo en Predeterminado o Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Columna oculta (el ancho de esta columna es 0) en Excel, antes de guardarla en formato html,<br/>si HtmlHiddenColDisplayType es "Eliminar", la columna oculta no se generará,<br/> Si el valor está "Oculto", la columna se generará, pero estaba oculta, el valor predeterminado es "Oculto".|
| [hidden_row_display_type](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Fila oculta (la altura de esta fila es 0) en Excel, antes de guardarla en formato html,<br/>si HtmlHiddenRowDisplayType es "Eliminar", la fila oculta no se generará,<br/> Si el valor está "Oculto", la fila se generará, pero estaba oculta, el valor predeterminado es "Oculto".|
| [encoding](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/encoding) | Si no está configurado, utilice Encoding.UTF8 como tipo de codificación predeterminado.|
| [export_object_listener](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_object_listener) | Obtiene o establece ExportObjectListener para exportar objetos.|
| [file_path_provider](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/file_path_provider) |Obtiene o establece IFilePathProvider para exportar la hoja de trabajo a HTML por separado.|
| [stream_provider](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/stream_provider) | Obtiene o establece IStreamProvider para exportar objetos.|
| [image_options](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/image_options) | Obtenga el objeto ImageOrPrintOptions antes de exportar|
| [save_as_single_file](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | Indica si se guarda el html como un solo archivo.<br/> El valor predeterminado es falso.|
| [show_all_sheets](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | Indica si se muestran todas las hojas al guardarlas como un único archivo html.|
| [export_page_headers](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_page_headers) | Indica si se exportan encabezados de página.|
| [export_page_footers](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_page_footers) | Indica si se exportan encabezados de página.|
| [export_hidden_worksheet](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | Indicando si se exporta el contenido oculto de la hoja de trabajo. El valor predeterminado es verdadero.|
| [presentation_preference](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/presentation_preference) | Indicando si el archivo html o mht es la preferencia de presentación.<br/>El valor predeterminado es falso.<br/> Si desea obtener una presentación más hermosa, establezca el valor en verdadero.|
| [cell_css_prefix](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | Obtiene y establece el prefijo del nombre CSS, el valor predeterminado es "".|
| [table_css_id](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/table_css_id) | Obtiene y establece el prefijo del nombre de tipo CSS, como tr,col,td, etc., que están contenidos en el elemento de tabla.<br/> que tiene el atributo TableCssId específico. El valor predeterminado es "".|
| [is_full_path_link](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/is_full_path_link) | Indicando si se utiliza el enlace de ruta completa ensheet00x.htm,filelist.xml y tabstrip.htm.<br/> El valor predeterminado es falso.|
| [export_worksheet_css_separately](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) |Indicando si exportar la hoja de trabajo css por separado. El valor predeterminado es falso.|
| [export_similar_border_style](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | Indica si se exporta el estilo de borde similar cuando el estilo de borde no es compatible con los navegadores.<br/>Si desea importar el archivo html o mht para Excel, mantenga el valor predeterminado.<br/> El valor predeterminado es falso.|
| [merge_empty_td_forcely](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | Indica si se debe fusionar un elemento TD vacío al exportar un archivo a html.<br/> El tamaño del archivo html se reducirá significativamente después de establecer el valor en verdadero. El valor predeterminado es falso.<br/> Si desea importar el archivo html para Excel o exportar líneas de cuadrícula perfectas al guardar el archivo en html,<br/> mantenga el valor predeterminado.|
| [merge_empty_td_type](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | Indica si el elemento TD vacío se fusionará de la misma manera que MS Excel al guardar un archivo de Excel en formato html.<br/> El valor predeterminado es MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | Indica si se exportan las coordenadas de Excel de celdas que no están en blanco al guardar el archivo en HTML. El valor predeterminado es falso.<br/> Si desea importar el HTML de salida a Excel, mantenga el valor predeterminado.|
| [export_extra_headings](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | Indica si se exportan encabezados adicionales cuando la longitud del texto es mayor que la columna de visualización máxima.<br/> El valor predeterminado es falso. Si desea importar el archivo html a Excel, mantenga el valor predeterminado.|
| [export_headings](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_headings) |Indica si exporta los encabezados de fila y columna de la hoja al guardarla en archivos HTML.|
| [export_row_column_headings](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |Indica si exporta los encabezados de fila y columna de la hoja al guardarla en archivos HTML.|
| [export_formula](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_formula) | Indica si se exporta la fórmula al guardar el archivo en html. El valor por defecto es verdadero.<br/> Si desea importar el HTML de salida a Excel, mantenga el valor predeterminado.|
| [add_tooltip_text](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | Indica si se agrega texto de información sobre herramientas cuando los datos no se pueden mostrar completamente.<br/> El valor predeterminado es falso.|
| [export_grid_lines](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | Indicando si se exportan las líneas de la cuadrícula. El valor predeterminado es falso.|
| [export_bogus_row_data](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | Indicando si se exportan datos falsos de la fila inferior. El valor predeterminado es verdadero. Si desea importar el archivo html o mht<br/> para sobresalir, mantenga el valor predeterminado.|
| [exclude_unused_styles](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | Indicando si excluye estilos no utilizados.<br/>Para los archivos html generados, excluir los estilos no utilizados puede reducir el tamaño del archivo.<br/>sin afectar los efectos visuales. Entonces el valor predeterminado de esta propiedad es verdadero.<br/>Si el usuario necesita mantener todos los estilos en el libro de trabajo para el html generado (como el escenario en el que el usuario<br/> necesita restaurar el libro de trabajo a partir del html generado más adelante), establezca esta propiedad como falsa.|
| [export_document_properties](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_document_properties) | Indicando si se exportan las propiedades del documento. El valor predeterminado es verdadero. Si desea importar<br/> el archivo html o mht para sobresalir, mantenga el valor predeterminado.|
| [export_worksheet_properties](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | Indicando si se exportan las propiedades de la hoja de trabajo. El valor predeterminado es verdadero. Si desea importar<br/> el archivo html o mht para sobresalir, mantenga el valor predeterminado.|
| [export_workbook_properties](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |Indicando si se exportan las propiedades del libro. El valor predeterminado es verdadero. Si desea importar<br/> el archivo html o mht para sobresalir, mantenga el valor predeterminado.|
| [export_frame_scripts_and_properties](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | Indica si se exportan scripts de marcos y propiedades del documento. El valor predeterminado es verdadero. Si desea importar el archivo html o mht<br/> para sobresalir, mantenga el valor predeterminado.|
| [export_data_options](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/export_data_options) | Indica la regla de exportación de datos del archivo html. El valor predeterminado es Todo.|
| [link_target_type](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/link_target_type) | Indicando el tipo de atributo de destino en el enlace `<a>`. El valor predeterminado es HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | Indicando si la salida HTML es compatible con el navegador IE.<br/> El valor predeterminado es falso.|
| [format_data_ignore_column_width](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | Indicando si se muestran todos los datos formateados de la celda cuando se desborda la columna.<br/>Si es verdadero, ignore el ancho de la columna y se exportarán todos los datos de la celda.<br/>Si es falso, los datos se exportarán igual que Excel.<br/> El valor predeterminado es falso.|
| [calculate_formula](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/calculate_formula) | Indica si se deben calcular fórmulas antes de guardar el archivo html.|
| [is_js_browser_compatible](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | Indica si JavaScript es compatible con navegadores que no admiten JavaScript.<br/> El valor por defecto es verdadero.|
| [is_mobile_compatible](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | Indica si la salida HTML es compatible con dispositivos móviles.<br/> El valor predeterminado es falso.|
| [css_styles](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions/css_styles) | Obtiene o establece los estilos CSS adicionales para el formateador.<br/>Solo funciona cuando [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/es/aspose.cells/htmlsaveoptions#save_as_single_file) es Verdadero.<br/><br/> CssStyles="cuerpo {relleno: 5px}";|



###  Ver también
* módulo [`aspose.cells.saving`](..)
* clase [`EbookSaveOptions`](/cells/python-net/es/aspose.cells.saving/ebooksaveoptions)
* clase [`HtmlSaveOptions`](/cells/python-net/es/aspose.cells/htmlsaveoptions)
* clase [`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)
