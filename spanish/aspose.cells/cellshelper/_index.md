---
title: CellsHelper clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 240
url: /es/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper clase
Proporciona funciones de ayuda.



El tipo CellsHelper expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [significant_digits](/cells/python-net/es/aspose.cells/cellshelper/significant_digits) | Obtiene y establece el número de dígitos significativos.<br/> El valor predeterminado es 17.|
| [dpi](/cells/python-net/es/aspose.cells/cellshelper/dpi) | Obtiene el DPI de la máquina.|
| [startup_path](/cells/python-net/es/aspose.cells/cellshelper/startup_path) | Obtiene o establece la ruta de inicio, a la que hacen referencia algunas referencias de fórmulas externas.|
| [alt_start_path](/cells/python-net/es/aspose.cells/cellshelper/alt_start_path) | Obtiene o establece la ruta de inicio alternativa, a la que hacen referencia algunas referencias de fórmulas externas.|
| [library_path](/cells/python-net/es/aspose.cells/cellshelper/library_path) | Obtiene o establece la ruta de la biblioteca a la que hacen referencia algunas referencias de fórmulas externas.|
| [custom_implementation_factory](/cells/python-net/es/aspose.cells/cellshelper/custom_implementation_factory) | Obtiene o establece el generador para crear instancias con implementación especial.|
| [is_cloud_platform](/cells/python-net/es/aspose.cells/cellshelper/is_cloud_platform) | Establezca esta propiedad en Verdadero cuando se ejecute en una plataforma en la nube, como: Azure, AWSLambda, etc.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/es/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Comprueba el nombre de la hoja dado y crea uno válido cuando sea necesario.<br/>Si el nombre de la hoja dado se ajusta a las reglas del nombre de la hoja de Excel, devuélvalo.<br/>De lo contrario, la cadena se truncará si la longitud excede el límite.<br/> los caracteres no válidos se reemplazarán con " " y luego se devolverá el valor de cadena reconstruido.|
| [create_safe_sheet_name](/cells/python-net/es/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Comprueba el nombre de la hoja dado y crea uno válido cuando sea necesario.<br/>Si el nombre de la hoja dado se ajusta a las reglas del nombre de la hoja de Excel, devuélvalo.<br/>De lo contrario, la cadena se truncará si la longitud excede el límite.<br/> y los caracteres no válidos se reemplazarán con el carácter dado y luego se devolverá el valor de cadena reconstruido.|
| [get_text_width](/cells/python-net/es/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | Obtenga el ancho del texto en unidades de puntos.|
| [get_version](/cells/python-net/es/aspose.cells/cellshelper/get_version/#) | Obtenga la versión de lanzamiento.|
| [cell_name_to_index](/cells/python-net/es/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Obtiene los índices de filas y columnas de la celda según su nombre.|
| [cell_index_to_name](/cells/python-net/es/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Obtiene el nombre de la celda según sus índices de filas y columnas.|
| [column_index_to_name](/cells/python-net/es/aspose.cells/cellshelper/column_index_to_name/#int) | Obtiene el nombre de la columna según el índice de la columna.|
| [column_name_to_index](/cells/python-net/es/aspose.cells/cellshelper/column_name_to_index/#str) | Obtiene el índice de la columna según el nombre de la columna.|
| [row_index_to_name](/cells/python-net/es/aspose.cells/cellshelper/row_index_to_name/#int) | Obtiene el nombre de la fila según el índice de la fila.|
| [row_name_to_index](/cells/python-net/es/aspose.cells/cellshelper/row_name_to_index/#str) | Obtiene el índice de fila según el nombre de la fila.|
| [convert_r1c1_formula_to_a1](/cells/python-net/es/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Convierte la fórmula r1c1 de la celda a fórmula A1.|
| [convert_a1_formula_to_r1c1](/cells/python-net/es/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | Convierte la fórmula A1 de la celda a la fórmula r1c1.|
| [get_date_time_from_double](/cells/python-net/es/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Convierta el valor doble al valor de fecha y hora.|
| [get_double_from_date_time](/cells/python-net/es/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | Convierta la fecha y hora al valor doble.|
| [get_used_colors](/cells/python-net/es/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | Obtiene todos los colores utilizados en el libro de trabajo.|
| [add_add_in_function](/cells/python-net/es/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | Agregar función complementaria.|
| [merge_files](/cells/python-net/es/aspose.cells/cellshelper/merge_files/#list-str-str) | Fusiona algunos archivos xls grandes en un archivo xls.|
| [need_quote_in_formula](/cells/python-net/es/aspose.cells/cellshelper/need_quote_in_formula/#str) |Indica si el nombre de la hoja debe estar entre comillas simples.|
| [init_for_dot_net_core](/cells/python-net/es/aspose.cells/cellshelper/init_for_dot_net_core/#) | Realice la inicialización del programa .NetCore.<br/> Le sugerimos que llame primero a este método para todas las inicializaciones de .NetCore.<br/>Por ejemplo:<br/>CellsHelper.InitForDotNetCore();<br/> Libro de trabajo wb = nuevo libro de trabajo();|



###  Ver también
* módulo [`aspose.cells`](..)
