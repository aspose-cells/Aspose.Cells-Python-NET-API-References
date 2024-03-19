---
title: TxtSaveOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1590
url: /es/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions clase
Representa las opciones de guardado para csv/delimitado por tabulaciones/otro formato de texto.



**Herencia:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)



El tipo TxtSaveOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/txtsaveoptions/__init__/#) | Crea opciones para guardar archivos de texto.|
| [__init__](/cells/python-net/es/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) | Crea opciones para guardar archivos de texto.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells/txtsaveoptions/save_format) | Obtiene el formato del archivo guardado.|
| [clear_data](/cells/python-net/es/aspose.cells/txtsaveoptions/clear_data) | Deje el libro vacío después de guardar el archivo.|
| [cached_file_folder](/cells/python-net/es/aspose.cells/txtsaveoptions/cached_file_folder) | La carpeta de archivos en caché se utiliza para almacenar algunos datos de gran tamaño.|
| [validate_merged_areas](/cells/python-net/es/aspose.cells/txtsaveoptions/validate_merged_areas) | Indica si validar las celdas combinadas antes de guardar el archivo.|
| [merge_areas](/cells/python-net/es/aspose.cells/txtsaveoptions/merge_areas) | Indica si fusionar las áreas de formato condicional y validación antes de guardar el archivo.|
| [create_directory](/cells/python-net/es/aspose.cells/txtsaveoptions/create_directory) | Si es verdadero y el directorio no existe, el directorio se creará automáticamente antes de guardar el archivo.|
| [sort_names](/cells/python-net/es/aspose.cells/txtsaveoptions/sort_names) | Indica si se ordenan los nombres definidos antes de guardar el archivo.|
| [sort_external_names](/cells/python-net/es/aspose.cells/txtsaveoptions/sort_external_names) | Indica si se ordenan los nombres externos definidos antes de guardar el archivo.|
| [refresh_chart_cache](/cells/python-net/es/aspose.cells/txtsaveoptions/refresh_chart_cache) | Indica si se actualizan los datos de la caché del gráfico.|
| [warning_callback](/cells/python-net/es/aspose.cells/txtsaveoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [update_smart_art](/cells/python-net/es/aspose.cells/txtsaveoptions/update_smart_art) | Indica si se actualiza la configuración de arte inteligente.<br/> El valor predeterminado es falso.|
| [separator](/cells/python-net/es/aspose.cells/txtsaveoptions/separator) | Obtiene y establece el delimitador char del archivo de texto.|
| [separator_string](/cells/python-net/es/aspose.cells/txtsaveoptions/separator_string) | Obtiene y establece un valor de cadena como separador.|
| [encoding](/cells/python-net/es/aspose.cells/txtsaveoptions/encoding) | Obtiene y establece la codificación predeterminada.|
| [always_quoted](/cells/python-net/es/aspose.cells/txtsaveoptions/always_quoted) | Indica si siempre se agrega '"' para cada campo.<br/>Si es verdadero, se citarán todos los valores;<br/>Si es falso, los valores sólo se citarán cuando sea necesario (por ejemplo,<br/>cuando los valores contienen caracteres especiales como '"' , '\n' o carácter separador).<br/> El valor predeterminado es falso.|
| [quote_type](/cells/python-net/es/aspose.cells/txtsaveoptions/quote_type) | Obtiene o establece cómo citar valores en el archivo de texto exportado.|
| [format_strategy](/cells/python-net/es/aspose.cells/txtsaveoptions/format_strategy) | Obtiene y establece la estrategia de formato al exportar el valor de la celda como cadena.|
| [light_cells_data_provider](/cells/python-net/es/aspose.cells/txtsaveoptions/light_cells_data_provider) | El proveedor de datos para guardar el libro en modo ligero.|
| [trim_leading_blank_row_and_column](/cells/python-net/es/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Indica si las primeras filas y columnas en blanco deben recortarse como lo hace MS Excel.<br/> El valor predeterminado es verdadero.|
| [trim_tailing_blank_cells](/cells/python-net/es/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Indica si se deben recortar las celdas en blanco finales de una fila. El valor predeterminado es falso.|
| [keep_separators_for_blank_row](/cells/python-net/es/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |Indica si se deben generar separadores para la fila en blanco.<br/> El valor predeterminado es falso, por lo que, de forma predeterminada, el contenido de la fila en blanco estará vacío.|
| [export_area](/cells/python-net/es/aspose.cells/txtsaveoptions/export_area) | El rango de celdas que se exportarán.|
| [export_quote_prefix](/cells/python-net/es/aspose.cells/txtsaveoptions/export_quote_prefix) | Indica si el signo de comilla simple debe exportarse como parte del valor de una celda.<br/> cuando [`Style.quote_prefix`](/cells/python-net/es/aspose.cells/style#quote_prefix) es cierto. El valor predeterminado es falso.|
| [export_all_sheets](/cells/python-net/es/aspose.cells/txtsaveoptions/export_all_sheets) | Indica si se exportan todas las hojas al archivo de texto.<br/> Si es falso, exporte únicamente la hoja activa, como en MS Excel.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)
* clase [`TxtSaveOptions`](/cells/python-net/es/aspose.cells/txtsaveoptions)
