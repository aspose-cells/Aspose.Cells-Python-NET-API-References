---
title: CellsHelper clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 210
url: /es/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper clase
Proporciona funciones auxiliares.



El tipo CellsHelper expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [significant_digits](/cells/python-net/es/aspose.cells/cellshelper/significant_digits) | Obtiene y establece el número de dígitos significativos.<br/> El valor predeterminado es 17.|
| [dpi](/cells/python-net/es/aspose.cells/cellshelper/dpi) | Obtiene el DPI de la máquina.|
| [startup_path](/cells/python-net/es/aspose.cells/cellshelper/startup_path) | Obtiene o establece la ruta de inicio, a la que hacen referencia algunas referencias de fórmulas externas.|
| [alt_start_path](/cells/python-net/es/aspose.cells/cellshelper/alt_start_path) | Obtiene o establece la ruta de inicio alternativa, a la que hacen referencia algunas referencias de fórmulas externas.|
| [library_path](/cells/python-net/es/aspose.cells/cellshelper/library_path) |Obtiene o establece la ruta de la biblioteca a la que hacen referencia algunas referencias de fórmulas externas.|
| [custom_implementation_factory](/cells/python-net/es/aspose.cells/cellshelper/custom_implementation_factory) | Obtiene o establece la fábrica para crear instancias con implementación especial.|
| [is_cloud_platform](/cells/python-net/es/aspose.cells/cellshelper/is_cloud_platform) | Establezca esta propiedad en Verdadero cuando se ejecute en una plataforma en la nube, como: Azure, AWSLambda, etc.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/es/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Comprueba el nombre de la hoja dada y crea uno válido cuando sea necesario.<br/>Si el nombre de la hoja dada cumple con las reglas del nombre de hoja de Excel, devuélvalo.<br/>De lo contrario, la cadena se truncará si la longitud excede el límite.<br/> y los caracteres no válidos se reemplazarán con ' ' y luego se devolverá el valor de la cadena reconstruida.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/es/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Comprueba el nombre de la hoja dada y crea uno válido cuando sea necesario.<br/>Si el nombre de la hoja dada cumple con las reglas del nombre de hoja de Excel, devuélvalo.<br/>De lo contrario, la cadena se truncará si la longitud excede el límite.<br/> y los caracteres no válidos serán reemplazados con el carácter dado y luego se devolverá el valor de la cadena reconstruida.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/es/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | Obtener el ancho del texto en unidades de puntos.|
| [`get_version()`](/cells/python-net/es/aspose.cells/cellshelper/get_version/#) | Obtenga la versión de lanzamiento.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/es/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Obtiene los índices de filas y columnas de celdas según su nombre.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/es/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Obtiene el nombre de la celda según sus índices de fila y columna.|
| [`column_index_to_name(, column)`](/cells/python-net/es/aspose.cells/cellshelper/column_index_to_name/#int) | Obtiene el nombre de la columna según el índice de la columna.|
| [`column_name_to_index(, column_name)`](/cells/python-net/es/aspose.cells/cellshelper/column_name_to_index/#str) | Obtiene el índice de la columna según el nombre de la columna.|
| [`row_index_to_name(, row)`](/cells/python-net/es/aspose.cells/cellshelper/row_index_to_name/#int) | Obtiene el nombre de la fila según el índice de fila.|
| [`row_name_to_index(, row_name)`](/cells/python-net/es/aspose.cells/cellshelper/row_name_to_index/#str) | Obtiene el índice de fila según el nombre de fila.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/es/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Convierte la fórmula r1c1 de la celda en la fórmula A1.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/es/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |Convierte la fórmula A1 de la celda en la fórmula r1c1.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/es/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Convierte el valor doble en valor de fecha y hora.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/es/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | Convierte la fecha y hora en valor doble.|
| [`get_used_colors(, workbook)`](/cells/python-net/es/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | Obtiene todos los colores utilizados en el libro de trabajo.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/es/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | Añadir función complementaria.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/es/aspose.cells/cellshelper/merge_files/#list-str-str) | Fusiona algunos archivos xls grandes en un archivo xls.|
| [`get_cache_folder()`](/cells/python-net/es/aspose.cells/cellshelper/get_cache_folder/#) | Obtiene la carpeta para archivos temporales que pueden usarse como caché de datos.|
| [`set_cache_folder(, cache)`](/cells/python-net/es/aspose.cells/cellshelper/set_cache_folder/#str) | Establece la carpeta para archivos temporales que pueden usarse como caché de datos.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/es/aspose.cells/cellshelper/need_quote_in_formula/#str) | Indica si el nombre de la hoja debe estar entre comillas simples.|
| [`init_for_dot_net_core()`](/cells/python-net/es/aspose.cells/cellshelper/init_for_dot_net_core/#) | Realice la inicialización del programa .NetCore.<br/> Le sugerimos que llame a este método para toda la inicialización de .NetCore primero.<br/>Por ejemplo:<br/>CellsHelper.InitForDotNetCore();<br/> Libro de trabajo wb = new Libro de trabajo();|



###  Ver también
* módulo [`aspose.cells`](..)
