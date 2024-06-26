---
title: Config clase
second_title: Aspose.Cells.GridJs for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cellsgridjs/config/
is_root: false
---
##  Config clase

Representa todas las configuraciones para GridJs.



El tipo Config expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cellsgridjs/config/__init__/#) | Construye una nueva instancia de Config.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_html_as_zip](/cells/python-net/es/aspose.cellsgridjs/config/save_html_as_zip) | Establece/obtiene si se debe guardar el archivo html como archivo zip, el valor predeterminado es falso.|
| [same_image_detecting](/cells/python-net/es/aspose.cellsgridjs/config/same_image_detecting) | Establece/obtiene si se debe verificar si la imagen tiene la misma fuente, el valor predeterminado es verdadero<br/> El valor por defecto es verdadero.|
| [auto_optimize_for_large_cells](/cells/python-net/es/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Establece/obtiene si se debe optimizar automáticamente el rendimiento de carga para hojas de trabajo con celdas grandes<br/> ignorar algunos estilos/bordes para reducir el tiempo de carga<br/> El valor por defecto es verdadero.|
| [islimit_shape_or_image](/cells/python-net/es/aspose.cellsgridjs/config/islimit_shape_or_image) |Establece/obtiene si se debe limitar el recuento total de formas/imágenes de visualización dentro de una hoja de trabajo, si se establece en verdadero,<br/> GridJs limitará el tamaño total de la forma/imagen de visualización dentro de una hoja de trabajo a MaxShapeOrImageCount<br/> El valor por defecto es verdadero.|
| [max_shape_or_image_count](/cells/python-net/es/aspose.cellsgridjs/config/max_shape_or_image_count) | Establece/obtiene el recuento total de formas/imágenes de visualización dentro de la hoja activa; entrará en vigor cuando IslimitShapes=true.<br/> el valor predeterminado es 100.|
| [max_total_shape_or_image_count](/cells/python-net/es/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Establece/obtiene el recuento total de formas/imágenes de visualización dentro de todo el libro de trabajo; entrará en vigor cuando IslimitShapes=true.<br/> el valor predeterminado es 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/es/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Establece/obtiene el ancho o alto máximo para una forma/imagen. GridJs ignorará la forma/imagen con un ancho o alto mayor que esto, afectará cuando IslimitShapes=true.<br/> el valor predeterminado es 10000.|
| [max_pdf_save_seconds](/cells/python-net/es/aspose.cellsgridjs/config/max_pdf_save_seconds) | Establece/obtiene el tiempo máximo de segundos cuando se guarda en pdf.<br/> el valor predeterminado es 10.|
| [ignore_empty_content](/cells/python-net/es/aspose.cellsgridjs/config/ignore_empty_content) | Establece/obtiene si se debe mostrar el rango máximo que incluye datos, estilo, celdas combinadas y formas.<br/> si la última fila o columna contiene celdas sin valor ni fórmula pero tiene un estilo personalizado<br/>entonces no mostraremos esta fila/columna cuando este valor sea verdadero.<br/> El valor por defecto es verdadero .|
| [use_print_area](/cells/python-net/es/aspose.cellsgridjs/config/use_print_area) |Establece/obtiene si se debe usar PageSetup.PrintArea para el rango de visualización de la interfaz de usuario cuando la hoja de trabajo tiene la configuración PageSetup para PrintArea.<br/> el valor predeterminado es falso.|
| [load_time_out](/cells/python-net/es/aspose.cellsgridjs/config/load_time_out) | Establece/obtiene una interrupción de tiempo de espera en milisegundos al cargar el archivo, cuando el período de tiempo de costo de cargar el archivo es más largo que lo esperado, generará una excepción.<br/> el valor predeterminado es -1, lo que significa que no se establece ninguna interrupción de tiempo de espera.|
| [show_chart_sheet](/cells/python-net/es/aspose.cellsgridjs/config/show_chart_sheet) | Establece/obtiene si se debe mostrar la hoja de cálculo del gráfico.<br/> el valor predeterminado es falso.|
| [page_size](/cells/python-net/es/aspose.cellsgridjs/config/page_size) | Establece/Obtiene si se debe hacer paginación<br/> GridJs limitará el tamaño de la fila según el tamaño de la página, si el tamaño de la página es -1, no realizará la paginación<br/> el valor predeterminado es -1|
| [empty_sheet_max_row](/cells/python-net/es/aspose.cellsgridjs/config/empty_sheet_max_row) | Establece/obtiene la fila máxima predeterminada para una hoja de trabajo vacía.<br/> el valor predeterminado es 12.|
| [empty_sheet_max_col](/cells/python-net/es/aspose.cellsgridjs/config/empty_sheet_max_col) | Establece/obtiene la columna máxima predeterminada para una hoja de trabajo vacía.<br/> el valor predeterminado es 15.|
| [picture_cache_directory](/cells/python-net/es/aspose.cellsgridjs/config/picture_cache_directory) | Establece/obtiene el directorio de caché para las imágenes (esto tendrá efecto cuando GridJsWorkbook.CacheImp sea nulo)<br/> la ruta predeterminada será "_piccache" dentro de FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/es/aspose.cellsgridjs/config/file_cache_directory) |Establece/obtiene el directorio de caché para el archivo de hoja de cálculo.<br/> Necesitamos configurarlo en una ruta específica antes de usar GridJs.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_license](/cells/python-net/es/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/es/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Licencia el componente.|
| [set_font_folder](/cells/python-net/es/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Establece la carpeta de fuentes|
| [set_font_folders](/cells/python-net/es/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Establece las carpetas de fuentes.|



###  Ver también
* módulo [`aspose.cellsgridjs`](..)
