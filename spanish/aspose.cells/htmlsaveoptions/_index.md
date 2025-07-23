---
title: HtmlSaveOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 790
url: /es/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions clase
Representa las opciones para guardar el archivo html.



**Herencia:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)



El tipo HtmlSaveOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/htmlsaveoptions/__init__/#) | Crea opciones para guardar el archivo html.|
| [`__init__(self, save_format)`](/cells/python-net/es/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.saveformat) | Crea opciones para guardar archivos htm.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells/htmlsaveoptions/save_format) | Obtiene el formato del archivo guardado.|
| [clear_data](/cells/python-net/es/aspose.cells/htmlsaveoptions/clear_data) | Vacíe el libro de trabajo después de guardar el archivo.|
| [cached_file_folder](/cells/python-net/es/aspose.cells/htmlsaveoptions/cached_file_folder) | La carpeta para archivos temporales que pueden usarse como caché de datos.|
| [validate_merged_areas](/cells/python-net/es/aspose.cells/htmlsaveoptions/validate_merged_areas) | Indica si se deben validar las celdas fusionadas antes de guardar el archivo.|
| [merge_areas](/cells/python-net/es/aspose.cells/htmlsaveoptions/merge_areas) | Indica si se deben fusionar las áreas de formato condicional y validación antes de guardar el archivo.|
| [create_directory](/cells/python-net/es/aspose.cells/htmlsaveoptions/create_directory) | Si es verdadero y el directorio no existe, el directorio se creará automáticamente antes de guardar el archivo.|
| [sort_names](/cells/python-net/es/aspose.cells/htmlsaveoptions/sort_names) |Indica si se deben ordenar los nombres definidos antes de guardar el archivo.|
| [sort_external_names](/cells/python-net/es/aspose.cells/htmlsaveoptions/sort_external_names) | Indica si se deben ordenar los nombres definidos externamente antes de guardar el archivo.|
| [refresh_chart_cache](/cells/python-net/es/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Indica si se actualizan los datos de caché del gráfico|
| [check_excel_restriction](/cells/python-net/es/aspose.cells/htmlsaveoptions/check_excel_restriction) | Si verificar la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas.<br/>Por ejemplo, Excel no permite ingresar valores de cadena con una longitud mayor a 32K.<br/> Cuando ingrese un valor mayor a 32K, este se truncará.|
| [update_smart_art](/cells/python-net/es/aspose.cells/htmlsaveoptions/update_smart_art) | Indica si se actualiza la configuración de arte inteligente.<br/> El valor predeterminado es falso.|
| [encrypt_document_properties](/cells/python-net/es/aspose.cells/htmlsaveoptions/encrypt_document_properties) | Indica si se deben cifrar las propiedades del documento al guardarlo como archivo .xls.<br/> El valor predeterminado es verdadero.|
| [ignore_invisible_shapes](/cells/python-net/es/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Indique si desea exportar aquellas formas no visibles|
| [page_title](/cells/python-net/es/aspose.cells/htmlsaveoptions/page_title) | El título de la página html.<br/> Sólo para guardar en secuencia HTML.|
| [attached_files_directory](/cells/python-net/es/aspose.cells/htmlsaveoptions/attached_files_directory) | El directorio donde se guardarán los archivos adjuntos.<br/> Sólo para guardar en secuencia HTML.|
| [attached_files_url_prefix](/cells/python-net/es/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Especifique el prefijo de URL de los archivos adjuntos, como la imagen en el archivo html.<br/> Sólo para guardar en secuencia HTML.|
| [default_font_name](/cells/python-net/es/aspose.cells/htmlsaveoptions/default_font_name) | Especifique el nombre de fuente predeterminado para exportar html, la fuente predeterminada se utilizará cuando la fuente del estilo no exista.<br/>Si esta propiedad es nula, Aspose.Cells utilizará una fuente universal que tiene la misma familia que la fuente original.<br/> El valor predeterminado es nulo.|
| [add_generic_font](/cells/python-net/es/aspose.cells/htmlsaveoptions/add_generic_font) |Indica si se debe agregar una fuente genérica a la familia de fuentes CSS.<br/> El valor predeterminado es verdadero|
| [worksheet_scalable](/cells/python-net/es/aspose.cells/htmlsaveoptions/worksheet_scalable) | Indica si se debe acercar o alejar el HTML a través del nivel de zoom de la hoja de cálculo al guardar el archivo en HTML, el valor predeterminado es falso.|
| [is_export_comments](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_export_comments) | Indica si se exportan comentarios al guardar el archivo en html, el valor predeterminado es falso.|
| [export_comments_type](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_comments_type) | Representa el tipo de exportación de comentarios a archivos html.|
| [disable_downlevel_revealed_comments](/cells/python-net/es/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Indica si se deshabilitan los comentarios condicionales revelados por Downlevel al exportar un archivo a HTML, el valor predeterminado es falso.|
| [is_exp_image_to_temp_dir](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Indica si se exportan archivos de imagen al directorio temporal.<br/> Sólo para guardar en secuencia HTML.|
| [image_scalable](/cells/python-net/es/aspose.cells/htmlsaveoptions/image_scalable) | Indica si se utiliza una unidad escalable para describir el ancho de la imagen<br/>al utilizar una unidad escalable para describir el ancho de la columna.<br/> El valor predeterminado es verdadero.|
| [width_scalable](/cells/python-net/es/aspose.cells/htmlsaveoptions/width_scalable) | Indica si se exporta el ancho de columna en unidad de escala a html.<br/> El valor predeterminado es falso.|
| [export_single_tab](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_single_tab) | Indica si se exporta la pestaña única cuando el archivo solo tiene una hoja de cálculo.<br/> El valor predeterminado es falso.|
| [export_images_as_base64](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_images_as_base64) | Especifica si las imágenes se guardan en formato Base64 en HTML, MHTML o EPUB.|
| [export_active_worksheet_only](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Indica si solo se exporta la hoja de trabajo activa a un archivo html.<br/>Si es verdadero, solo se exportará la hoja de trabajo activa al archivo html;<br/>Si es falso, todo el libro de trabajo se exportará a un archivo html.<br/> El valor predeterminado es falso.|
| [export_print_area_only](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_print_area_only) |Indica si solo se exporta el área de impresión a un archivo HTML. El valor predeterminado es "false".|
| [export_area](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_area) | Obtiene o establece el área de celda de exportación de la hoja de trabajo activa actual.<br/>Si configura este atributo, se omitirá el área de impresión de la hoja de trabajo activa actual.<br/> Solo se exportará el área especificada al guardar el archivo en html.|
| [parse_html_tag_in_cell](/cells/python-net/es/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) | Indica si la etiqueta HTML (como `<div></div>`) en la celda debe analizarse como valor de celda o conservarse tal como está.<br/> El valor predeterminado es verdadero.|
| [html_cross_string_type](/cells/python-net/es/aspose.cells/htmlsaveoptions/html_cross_string_type) | Indica si una cadena entre celdas se mostrará de la misma manera que MS Excel al guardar un archivo Excel en formato html.<br/>De forma predeterminada, el valor es Predeterminado, por lo que, para cadenas entre celdas, hay poca diferencia entre los archivos html creados por Aspose.Cells y MS Excel.<br/> Pero el rendimiento para crear archivos html grandes, al configurar el valor en Cross, sería varias veces más rápido que al configurarlo en Default o Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/es/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Columna oculta (el ancho de esta columna es 0) en Excel, antes de guardarla en formato html,<br/>Si HtmlHiddenColDisplayType es "Eliminar", la columna oculta no se mostrará.<br/> Si el valor es "Oculto", la columna se habría mostrado, pero estaba oculta; el valor predeterminado es "Oculto".|
| [hidden_row_display_type](/cells/python-net/es/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Fila oculta (la altura de esta fila es 0) en Excel, antes de guardarla en formato html,<br/>Si HtmlHiddenRowDisplayType es "Eliminar", la fila oculta no se mostrará.<br/>Si el valor es "Oculto", la fila se habría mostrado, pero estaba oculta; el valor predeterminado es "Oculto".|
| [encoding](/cells/python-net/es/aspose.cells/htmlsaveoptions/encoding) | Si no se configura, utilice Encoding.UTF8 como tipo de codificación predeterminado.|
| [image_options](/cells/python-net/es/aspose.cells/htmlsaveoptions/image_options) | Obtenga el objeto ImageOrPrintOptions antes de exportar|
| [save_as_single_file](/cells/python-net/es/aspose.cells/htmlsaveoptions/save_as_single_file) | Indica si se debe guardar el html como un solo archivo.<br/> El valor predeterminado es falso.|
| [show_all_sheets](/cells/python-net/es/aspose.cells/htmlsaveoptions/show_all_sheets) | Indica si se mostrarán todas las hojas al guardar como un único archivo html.|
| [export_page_headers](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_page_headers) | Indica si se exportan encabezados de página.|
| [export_page_footers](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_page_footers) | Indica si se exportan encabezados de página.|
| [export_hidden_worksheet](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Indica si se exporta el contenido oculto de la hoja de cálculo. El valor predeterminado es verdadero.|
| [presentation_preference](/cells/python-net/es/aspose.cells/htmlsaveoptions/presentation_preference) | Indica si la preferencia de presentación es el archivo html o mht.<br/>El valor predeterminado es falso.<br/> Si desea obtener una presentación más hermosa, configure el valor en verdadero.|
| [cell_css_prefix](/cells/python-net/es/aspose.cells/htmlsaveoptions/cell_css_prefix) | Obtiene y establece el prefijo del nombre CSS, el valor predeterminado es "".|
| [table_css_id](/cells/python-net/es/aspose.cells/htmlsaveoptions/table_css_id) | Obtiene y establece el prefijo del nombre CSS del tipo, como tr, col, td, etc., que están contenidos en el elemento de tabla.<br/> que tiene el atributo específico TableCssId. El valor predeterminado es "".|
| [is_full_path_link](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_full_path_link) |Indica si se utiliza el vínculo de ruta completa en sheet00x.htm, filelist.xml y tabstrip.htm.<br/> El valor predeterminado es falso.|
| [export_worksheet_css_separately](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) | Indica si se debe exportar el CSS de la hoja de cálculo por separado. El valor predeterminado es falso.|
| [export_similar_border_style](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_similar_border_style) | Indica si se debe exportar el estilo de borde similar cuando los navegadores no lo admiten.<br/>Si desea importar el archivo html o mht a Excel, mantenga el valor predeterminado.<br/> El valor predeterminado es falso.|
| [merge_empty_td_forcely](/cells/python-net/es/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Indica si se debe fusionar de forma forzada el elemento TD vacío al exportar el archivo a HTML.<br/> El tamaño del archivo HTML se reducirá significativamente al establecer el valor en "true". El valor predeterminado es "false".<br/> Si desea importar el archivo html a Excel o exportar líneas de cuadrícula perfectas al guardar el archivo en html,<br/> Por favor mantenga el valor predeterminado.|
| [merge_empty_td_type](/cells/python-net/es/aspose.cells/htmlsaveoptions/merge_empty_td_type) | La opción de fusionar celdas vacías contiguas (elementos td vacíos)<br/> El valor predeterminado es MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Indica si se exportan las coordenadas de Excel de celdas no vacías al guardar el archivo en HTML. El valor predeterminado es "false".<br/> Si desea importar el HTML de salida a Excel, mantenga el valor predeterminado.|
| [export_extra_headings](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_extra_headings) | Indica si se exportan encabezados adicionales cuando la longitud del texto es mayor que la columna máxima de visualización.<br/> El valor predeterminado es falso. Si desea importar el archivo HTML a Excel, conserve el valor predeterminado.|
| [export_headings](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_headings) |Indica si se exportan los encabezados de fila y columna de la hoja al guardarla en archivos HTML.|
| [export_row_column_headings](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_row_column_headings) |Indica si se exportan los encabezados de fila y columna de la hoja al guardarla en archivos HTML.|
| [export_formula](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_formula) | Indica si se exporta la fórmula al guardar el archivo en HTML. El valor predeterminado es "true".<br/> Si desea importar el HTML de salida a Excel, mantenga el valor predeterminado.|
| [add_tooltip_text](/cells/python-net/es/aspose.cells/htmlsaveoptions/add_tooltip_text) | Indica si se debe agregar texto de información sobre herramientas cuando los datos no se pueden mostrar completamente.<br/> El valor predeterminado es falso.|
| [export_grid_lines](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_grid_lines) | Indica si se exportan las líneas de cuadrícula. El valor predeterminado es falso.|
| [export_bogus_row_data](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Indica si se exportan datos falsos de la fila inferior. El valor predeterminado es "true". Si desea importar el archivo HTML o MHT.<br/> Para sobresalir, mantenga el valor predeterminado.|
| [exclude_unused_styles](/cells/python-net/es/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Indica si se excluyen estilos no utilizados.<br/>Para los archivos html generados, excluir estilos no utilizados puede hacer que el tamaño del archivo sea más pequeño<br/>Sin afectar los efectos visuales. Por lo tanto, el valor predeterminado de esta propiedad es verdadero.<br/>Si el usuario necesita conservar todos los estilos en el libro de trabajo para el HTML generado (como en el escenario en el que el usuario...<br/> (Si necesita restaurar el libro de trabajo desde el HTML generado más tarde), configure esta propiedad como falsa.|
| [export_document_properties](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_document_properties) | Indica si se exportan las propiedades del documento. El valor predeterminado es verdadero. Si desea importar<br/> el archivo html o mht para sobresalir, mantenga el valor predeterminado.|
| [export_worksheet_properties](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Indica si se exportan las propiedades de la hoja de cálculo. El valor predeterminado es verdadero. Si desea importar<br/> el archivo html o mht para sobresalir, mantenga el valor predeterminado.|
| [export_workbook_properties](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_workbook_properties) |Indica si se exportan las propiedades del libro de trabajo. El valor predeterminado es verdadero. Si desea importar<br/> el archivo html o mht para sobresalir, mantenga el valor predeterminado.|
| [export_frame_scripts_and_properties](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Indica si se exportan scripts de marco y propiedades de documento. El valor predeterminado es "true". Si desea importar el archivo HTML o MHT.<br/> Para sobresalir, mantenga el valor predeterminado.|
| [export_data_options](/cells/python-net/es/aspose.cells/htmlsaveoptions/export_data_options) | Indica la regla de exportación de datos del archivo html. El valor predeterminado es Todo.|
| [link_target_type](/cells/python-net/es/aspose.cells/htmlsaveoptions/link_target_type) | Indica el tipo de atributo de destino en el enlace `<a>`. El valor predeterminado es HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_ie_compatible) | Indica si la salida HTML es compatible con el navegador IE.<br/> El valor predeterminado es falso|
| [format_data_ignore_column_width](/cells/python-net/es/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Indica si se deben mostrar todos los datos formateados de la celda cuando se desborda la columna.<br/>Si es verdadero, ignore el ancho de la columna y se exportarán todos los datos de la celda.<br/>Si es falso, los datos se exportarán igual que Excel.<br/> El valor predeterminado es falso.|
| [calculate_formula](/cells/python-net/es/aspose.cells/htmlsaveoptions/calculate_formula) | Indica si se deben calcular las fórmulas antes de guardar el archivo html.|
| [is_js_browser_compatible](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Indica si JavaScript es compatible con navegadores que no admiten JavaScript.<br/> El valor predeterminado es verdadero.|
| [is_mobile_compatible](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Indica si la salida HTML es compatible con dispositivos móviles.<br/> El valor predeterminado es falso.|
| [css_styles](/cells/python-net/es/aspose.cells/htmlsaveoptions/css_styles) | Obtiene o establece los estilos CSS adicionales para el formateador.<br/>Sólo funciona cuando [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/es/aspose.cells/htmlsaveoptions#save_as_single_file) es Verdadero.<br/><br/> CssStyles="cuerpo { relleno: 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/es/aspose.cells/htmlsaveoptions/hide_overflow_wrapped_text) |Indica si se debe ocultar el texto desbordado cuando el formato de celda está configurado para ajustar el texto.<br/> El valor predeterminado es falso|
| [is_border_collapsed](/cells/python-net/es/aspose.cells/htmlsaveoptions/is_border_collapsed) | Indica si los bordes de la tabla están contraídos.<br/> El valor predeterminado es verdadero.|
| [encode_entity_as_code](/cells/python-net/es/aspose.cells/htmlsaveoptions/encode_entity_as_code) | Indica si las entidades de caracteres html se reemplazan con código decimal.<br/>(por ejemplo, "&nbsp;" se reemplaza por "&#160;").<br/> El valor predeterminado es falso.|
| [office_math_output_mode](/cells/python-net/es/aspose.cells/htmlsaveoptions/office_math_output_mode) | Indica cómo exportar objetos de OfficeMath a HTML, el valor predeterminado es Imagen.|
| [cell_name_attribute](/cells/python-net/es/aspose.cells/htmlsaveoptions/cell_name_attribute) | Especifica el atributo que indica el nombre de celda que se escribirá.<br/>(por ejemplo, si el valor es "id", entonces para la celda "A1", la salida será:<td id='A1'>).<br/> El valor predeterminado es nulo.|
| [disable_css](/cells/python-net/es/aspose.cells/htmlsaveoptions/disable_css) | Indica si solo se aplican estilos en línea, sin depender de CSS.<br/> El valor predeterminado es falso.|
| [enable_css_custom_properties](/cells/python-net/es/aspose.cells/htmlsaveoptions/enable_css_custom_properties) | Optimice la salida HTML mediante propiedades personalizadas de CSS. Por ejemplo, si una imagen base64 tiene varias instancias, con una propiedad personalizada, los datos de la imagen solo se guardan una vez para mejorar el rendimiento del HTML resultante.<br/> El valor predeterminado es falso.|
| [html_version](/cells/python-net/es/aspose.cells/htmlsaveoptions/html_version) | Especifica la versión del estándar HTML que se debe utilizar al guardar el formato HTML.<br/> El valor predeterminado es HtmlVersion.Default.|
| [sheet_set](/cells/python-net/es/aspose.cells/htmlsaveoptions/sheet_set) | Obtiene o establece las hojas que se van a representar. El valor predeterminado son todas las hojas visibles en el libro: [`SheetSet.visible`](/cells/python-net/es/aspose.cells.rendering/sheetset#visible).|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`HtmlSaveOptions`](/cells/python-net/es/aspose.cells/htmlsaveoptions)
* clase [`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)
