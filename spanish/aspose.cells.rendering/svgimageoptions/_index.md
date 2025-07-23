---
title: SvgImageOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cells.rendering/svgimageoptions/
is_root: false
---
##  SvgImageOptions clase
Opciones para generar imágenes Svg.



**Herencia:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions)



El tipo SvgImageOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/__init__/#) | Director.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/save_format) | Obtiene o establece el tipo de formato del archivo de salida<br/> Soporte Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | Si PrintWithStatusDialog = true, habrá un cuadro de diálogo que mostrará el estado de impresión actual.<br/> De lo contrario, no se mostrará dicho diálogo.|
| [horizontal_resolution](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | Obtiene o establece la resolución horizontal de las imágenes generadas, en puntos por pulgada.|
| [vertical_resolution](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/vertical_resolution) | Obtiene o establece la resolución vertical de las imágenes generadas, en puntos por pulgada.|
| [tiff_compression](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/tiff_compression) | Obtiene o establece el tipo de compresión que se aplicará solo al guardar páginas en el formato `Tiff`.|
| [tiff_color_depth](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | Obtiene o establece la profundidad de bits para aplicar solo al guardar páginas en el formato `Tiff`.|
| [tiff_binarization_method](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | Obtiene o establece el método utilizado al convertir imágenes a formato de 1 bpp<br/>cuando [`ImageOrPrintOptions.image_type`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#image_type) es Tiff y [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#tiff_compression) es igual a Ccitt3 o Ccitt4.|
| [printing_page](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/printing_page) | Indica qué páginas no se imprimirán.|
| [quality](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/quality) | Obtiene o establece un valor que determina la calidad de las imágenes generadas<br/> Se aplica solo al guardar páginas en el formato `Jpeg`. El valor predeterminado es 100.|
| [image_type](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/image_type) | Obtiene o establece el formato de las imágenes generadas.<br/> valor predeterminado: PNG.|
| [is_cell_auto_fit](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | Indica si el ancho y la altura de las celdas se ajustan automáticamente al valor de la celda.<br/> El valor predeterminado es falso.|
| [one_page_per_sheet](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | Si OnePagePerSheet es verdadero, todo el contenido de una hoja se mostrará en una sola página como resultado.<br/> El tamaño del papel de la configuración de página no será válido y las demás configuraciones de la configuración de página no serán válidas.<br/> Todavía tendrá efecto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet es verdadero, todo el contenido de las columnas de una hoja se mostrará en una sola página en el resultado.<br/> El ancho del tamaño del papel de la configuración de página no será válido, y las demás configuraciones de la configuración de página<br/> Todavía tendrá efecto.|
| [chart_image_type](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/chart_image_type) | Indique el tipo de imagen del gráfico al realizar la conversión.<br/> valor predeterminado: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | Indique el nombre del archivo de la imagen incrustada en SVG.<br/> Esta debería ser la ruta completa con un directorio como "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | Si esta propiedad es verdadera, el SVG generado se ajustará al puerto de visualización.|
| [svg_css_prefix](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/svg_css_prefix) |Obtiene y establece el prefijo del nombre css en SVG, el valor predeterminado es una cadena vacía.|
| [only_area](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/only_area) | Si esta propiedad es verdadera, se generará un área y no tendrá efecto ninguna escala.|
| [text_rendering_hint](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | Especifica la calidad de la representación del texto.<br/> El valor predeterminado es TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/smoothing_mode) | Especifica si se aplica suavizado (antialiasing) a líneas y curvas y a los bordes de áreas rellenas.<br/> El valor predeterminado es SmoothingMode.None|
| [transparent](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/transparent) | Indica si el fondo de la imagen generada debe ser transparente.|
| [pixel_format](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/pixel_format) | Obtiene o establece el formato de píxel para las imágenes generadas.|
| [is_font_substitution_char_granularity](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | Indica si solo se debe sustituir la fuente del carácter cuando la fuente de la celda no es compatible con él.|
| [page_index](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/page_index) | Obtiene o establece el índice basado en 0 de la primera página a guardar.|
| [page_count](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/page_count) | Obtiene o establece el número de páginas a guardar.|
| [is_optimized](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/is_optimized) | Indica si se deben optimizar los elementos de salida.|
| [default_font](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/default_font) | Cuando los caracteres en Excel son Unicode y no están configurados con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloques en formato PDF o imagen.<br/>Establezca la fuente predeterminada, como MingLiu o MS Gothic, para mostrar estos caracteres.<br/>Si esta propiedad no está configurada, Aspose.Cells utilizará la fuente predeterminada del sistema para mostrar estos caracteres Unicode.|
| [check_workbook_default_font](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | Cuando los caracteres en Excel son Unicode y no están configurados con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloques en formato PDF o imagen.<br/> Establezca esto como verdadero para intentar usar la fuente predeterminada del libro de trabajo para mostrar estos caracteres primero.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | Indica si se debe imprimir una página en blanco cuando no hay nada que imprimir.|
| [gridline_type](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/gridline_type) | Obtiene o establece el tipo de línea de cuadrícula.|
| [gridline_color](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/gridline_color) | Obtiene o establece el color de la línea de cuadrícula.|
| [text_cross_type](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/text_cross_type) | Obtiene o establece el tipo de texto que se muestra cuando el ancho del texto es mayor que el ancho de la celda.|
| [emf_type](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/emf_type) | Obtiene o establece un EmfType que especifica el formato del Metafile.<br/> El valor predeterminado es EmfPlusDual.|
| [default_edit_language](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/default_edit_language) | Obtiene o establece el idioma de edición predeterminado.|
| [sheet_set](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/sheet_set) | Obtiene o establece las hojas que se van a representar. El valor predeterminado son todas las hojas visibles en el libro: [`SheetSet.visible`](/cells/python-net/es/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/emf_render_setting) | Configuración para representar metarchivos Emf en el archivo de origen.|
| [custom_render_settings](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/custom_render_settings) | Obtiene o establece configuraciones personalizadas durante la renderización.|
| [fit_to_view_port](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | Si esta propiedad es verdadera, el SVG generado se ajustará al puerto de visualización.|
| [css_prefix](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/css_prefix) |Obtiene y establece el prefijo del nombre css en SVG, el valor predeterminado es una cadena vacía.|
| [embedded_font_type](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/embedded_font_type) | Obtiene o establece el tipo de fuente que se incrusta en Svg.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | Establece el ancho y alto deseados de la imagen.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/es/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | Establece el ancho y alto deseados de la imagen.|



###  Ver también
* módulo [`aspose.cells.rendering`](..)
* clase [`ImageOrPrintOptions`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions)
* clase [`SvgImageOptions`](/cells/python-net/es/aspose.cells.rendering/svgimageoptions)
