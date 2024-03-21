---
title: ImageOrPrintOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions clase
Permite especificar opciones al representar una hoja de trabajo en imágenes, imprimir una hoja de trabajo o representar un gráfico en una imagen.



El tipo ImageOrPrintOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/__init__/#) | Construye una nueva instancia de ImageOrPrintOptions|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/save_format) | Obtiene o establece el tipo de formato del archivo de salida.<br/> Soporte tiff/XPS|
| [print_with_status_dialog](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | Si PrintWithStatusDialog = true, habrá un cuadro de diálogo que muestra el estado de impresión actual.<br/>de lo contrario, no se mostrará ningún cuadro de diálogo de este tipo.|
| [horizontal_resolution](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Obtiene o establece la resolución horizontal de las imágenes generadas, en puntos por pulgada.<br/> Aplica el método de generación de imágenes excepto imágenes en formato Emf.|
| [vertical_resolution](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Obtiene o establece la resolución vertical de las imágenes generadas, en puntos por pulgada.<br/> Aplica el método de generación de imágenes excepto la imagen en formato Emf.|
| [tiff_compression](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Obtiene o establece el tipo de compresión que se aplicará solo al guardar páginas en el formato `Tiff`.|
| [tiff_color_depth](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Obtiene o establece la profundidad de bits que se aplicará solo al guardar páginas en el formato `Tiff`.|
| [tiff_binarization_method](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Obtiene o establece el método utilizado al convertir imágenes al formato de 1 bpp<br/> cuando [`ImageOrPrintOptions.image_type`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#image_type) es Tiff y [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions#tiff_compression) es igual a Ccitt3 o Ccitt4.|
| [printing_page](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/printing_page) | Indica qué páginas no se imprimirán.|
| [quality](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/quality) | Obtiene o establece un valor que determina la calidad de las imágenes generadas.<br/> se aplica solo al guardar páginas en el formato `Jpeg`. El valor predeterminado es 100|
| [image_type](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/image_type) | Obtiene o establece el formato de las imágenes generadas.<br/> valor predeterminado: PNG.|
| [is_cell_auto_fit](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Indica si el ancho y el alto de las celdas se ajustan automáticamente según el valor de la celda.<br/> El valor predeterminado es falso.|
| [one_page_per_sheet](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | Si OnePagePerSheet es verdadero, todo el contenido de una hoja se generará en una sola página.<br/> El tamaño del papel de pagesetup no será válido y las demás configuraciones de pagesetup<br/> seguirá surtiendo efecto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet es verdadero, todo el contenido de la columna de una hoja se generará en una sola página como resultado.<br/>El ancho del tamaño del papel de pagesetup no será válido y las otras configuraciones de pagesetup<br/> seguirá surtiendo efecto.|
| [draw_object_event_handler](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/draw_object_event_handler) | Implementa esta interfaz para obtener DrawObject y Bound al renderizar.|
| [chart_image_type](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Indique el tipo de imagen del gráfico al realizar la conversión.<br/> valor predeterminado: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Indique el nombre de archivo de la imagen incrustada en svg.<br/> Esta debería ser la ruta completa con un directorio como "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | Si esta propiedad es verdadera, el svg generado se ajustará al puerto de visualización.|
| [only_area](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/only_area) | Si esta propiedad es verdadera, se generará un Área y no se aplicará ninguna escala.|
| [text_rendering_hint](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Especifica la calidad de la representación del texto.<br/> El valor predeterminado es TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Especifica si se aplica suavizado (antialiasing) a líneas y curvas y a los bordes de áreas rellenas.<br/> El valor predeterminado es SmoothingMode.Ninguno|
| [transparent](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/transparent) | Indica si el fondo de la imagen generada debe ser transparente.|
| [pixel_format](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/pixel_format) | Obtiene o establece el formato de píxeles de las imágenes generadas.|
| [warning_callback](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [page_saving_callback](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/page_saving_callback) | Controlar/Indicar el progreso del proceso de guardado de la página.|
| [is_font_substitution_char_granularity](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |Indica si solo se debe sustituir la fuente del carácter cuando la fuente de la celda no sea compatible con él.|
| [page_index](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/page_index) | Obtiene o establece el índice basado en 0 de la primera página que se guardará.|
| [page_count](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/page_count) | Obtiene o establece el número de páginas que se guardarán.|
| [is_optimized](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/is_optimized) | Indica si se deben optimizar los elementos de salida.|
| [default_font](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/default_font) | Cuando los caracteres en Excel son Unicode y no se configuran con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloque en pdf, imagen.<br/>Configure la fuente predeterminada, como MingLiu o MS Gothic, para mostrar estos caracteres.<br/> Si esta propiedad no está configurada, Aspose.Cells utilizará la fuente predeterminada del sistema para mostrar estos caracteres Unicode.|
| [check_workbook_default_font](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | Cuando los caracteres en Excel son Unicode y no se configuran con la fuente correcta en el estilo de celda,<br/>Pueden aparecer como bloque en pdf, imagen.<br/> Establezca esto en verdadero para intentar usar la fuente predeterminada del libro para mostrar estos caracteres primero.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Indica si se debe generar una página en blanco cuando no hay nada que imprimir.|
| [gridline_type](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/gridline_type) | Obtiene o establece el tipo de línea de cuadrícula.|
| [text_cross_type](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Obtiene o establece la visualización del tipo de texto cuando el ancho del texto es mayor que el ancho de la celda.|
| [emf_type](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/emf_type) | Obtiene o establece un EmfType que especifica el formato del metarchivo.<br/>El valor predeterminado es EmfPlusDual.|
| [default_edit_language](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Obtiene o establece el idioma de edición predeterminado.|
| [sheet_set](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/sheet_set) |Obtiene o establece las hojas que se van a representar. El valor predeterminado son todas las hojas visibles del libro: [`SheetSet.visible`](/cells/python-net/es/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Configuración para renderizar el metarchivo Emf.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_desired_size](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Establece el ancho y alto deseados de la imagen.|
| [set_desired_size](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Establece el ancho y alto deseados de la imagen.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  Ver también
* módulo [`aspose.cells.rendering`](..)
