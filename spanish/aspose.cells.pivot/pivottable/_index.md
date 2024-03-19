---
title: PivotTable clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable clase
Descripción resumida de PivotTable.



El tipo PivotTable expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/es/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Especifica si la tabla dinámica es compatible con Excel2003 al actualizar la tabla dinámica.<br/>si es verdadero, una cadena debe tener menos o igual a 255 caracteres, por lo que si la cadena tiene más de 255 caracteres,<br/>quedará truncado. si es falso, una cadena no tendrá la restricción antes mencionada.<br/> El valor por defecto es verdadero.|
| [refreshed_by_who](/cells/python-net/es/aspose.cells.pivot/pivottable/refreshed_by_who) | Obtiene el nombre del usuario que actualizó la tabla dinámica por última vez.|
| [refresh_date](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_date) | Obtiene la fecha en la que se actualizó por última vez la tabla dinámica.|
| [pivot_table_style_name](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_table_style_name) | Obtiene y establece el nombre del estilo de la tabla dinámica.|
| [pivot_table_style_type](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_table_style_type) | Obtiene y establece el estilo de la tabla dinámica integrada.|
| [column_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/column_fields) | Devuelve un objeto PivotFields que actualmente se muestra como campos de columna.|
| [row_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/row_fields) | Devuelve un objeto PivotFields que actualmente se muestra como campos de fila.|
| [page_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/page_fields) | Devuelve un objeto PivotFields que actualmente se muestra como campos de página.|
| [data_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/data_fields) | Obtiene un objeto PivotField que representa todos los campos de datos de una tabla dinámica.<br/>Solo lectura. Se iniciará solo cuando haya dos o más campos de datos en DataPiovtFiels.<br/> Solo se usa para agregar DataPivotField al área de fila/columna de la tabla dinámica. El valor predeterminado está en el área de la fila.|
| [data_field](/cells/python-net/es/aspose.cells.pivot/pivottable/data_field) | Obtiene un objeto PivotField que representa todos los campos de datos de una tabla dinámica.<br/>Solo lectura. Se iniciará solo cuando haya dos o más campos de datos en DataPiovtFiels.<br/> Solo se usa para agregar DataPivotField al área de fila/columna de la tabla dinámica. El valor predeterminado está en el área de la fila.|
| [base_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/base_fields) | Devuelve un objeto PivotFields que incluye todos los campos del informe de tabla dinámica|
| [pivot_filters](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_filters) | Devuelve un objeto PivotFilterCollection.|
| [column_range](/cells/python-net/es/aspose.cells.pivot/pivottable/column_range) |Devuelve un objeto CellArea que representa el rango<br/> que contiene el área de la columna en el informe de tabla dinámica. Solo lectura.|
| [row_range](/cells/python-net/es/aspose.cells.pivot/pivottable/row_range) |Devuelve un objeto CellArea que representa el rango<br/> que contiene el área de la fila en el informe de tabla dinámica. Solo lectura.|
| [data_body_range](/cells/python-net/es/aspose.cells.pivot/pivottable/data_body_range) | Devuelve un objeto CellArea que representa el rango que contiene el área de datos<br/> en la lista entre la fila del encabezado y la fila de inserción. Solo lectura.|
| [table_range1](/cells/python-net/es/aspose.cells.pivot/pivottable/table_range1) | Devuelve un objeto CellArea que representa el rango que contiene todo el informe de tabla dinámica.<br/> pero no incluye campos de página. Solo lectura.|
| [table_range2](/cells/python-net/es/aspose.cells.pivot/pivottable/table_range2) | Devuelve un objeto CellArea que representa el rango que contiene todo el informe de tabla dinámica.<br/> Incluye campos de página. Solo lectura.|
| [column_grand](/cells/python-net/es/aspose.cells.pivot/pivottable/column_grand) | Indica si el informe de tabla dinámica muestra los totales generales de las columnas.|
| [is_grid_drop_zones](/cells/python-net/es/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Indica si el informe de tabla dinámica muestra un diseño de tabla dinámica clásico.<br/> (permite arrastrar campos en la cuadrícula)|
| [row_grand](/cells/python-net/es/aspose.cells.pivot/pivottable/row_grand) | Indica si el informe de tabla dinámica muestra totales generales para las filas.|
| [display_null_string](/cells/python-net/es/aspose.cells.pivot/pivottable/display_null_string) | Indica si el informe de tabla dinámica muestra una cadena personalizada<br/> en celdas que contienen valores nulos.|
| [null_string](/cells/python-net/es/aspose.cells.pivot/pivottable/null_string) | Obtiene la cadena que se muestra en las celdas que contienen valores nulos.<br/>cuando la propiedad DisplayNullString es verdadera. El valor predeterminado es una cadena vacía.|
| [display_error_string](/cells/python-net/es/aspose.cells.pivot/pivottable/display_error_string) | Indica si el informe de tabla dinámica muestra una cadena personalizada en las celdas que contienen errores.|
| [data_field_header_name](/cells/python-net/es/aspose.cells.pivot/pivottable/data_field_header_name) | Obtiene y establece el nombre del encabezado del campo del área de valor en la tabla dinámica.|
| [error_string](/cells/python-net/es/aspose.cells.pivot/pivottable/error_string) | Obtiene la cadena que se muestra en las celdas que contienen errores.<br/> cuando la propiedad DisplayErrorString es verdadera. El valor predeterminado es una cadena vacía.|
| [is_auto_format](/cells/python-net/es/aspose.cells.pivot/pivottable/is_auto_format) | Indica si el informe de tabla dinámica se formatea automáticamente.<br/> Casilla de verificación "tabla de formato automático" que se encuentra en la opción de tabla dinámica para Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/es/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Indica si el ancho de columna se ajusta automáticamente al actualizar|
| [auto_format_type](/cells/python-net/es/aspose.cells.pivot/pivottable/auto_format_type) | Obtiene el tipo de formato automático de tabla dinámica.|
| [has_blank_rows](/cells/python-net/es/aspose.cells.pivot/pivottable/has_blank_rows) | Indica si se deben agregar filas en blanco.<br/> Esta propiedad solo se aplica a los tipos de formato automático de tabla dinámica que necesitan agregar filas en blanco.|
| [merge_labels](/cells/python-net/es/aspose.cells.pivot/pivottable/merge_labels) | Indica si el elemento de la fila exterior, el elemento de la columna, el subtotal, el elemento de la fila exterior del informe de tabla dinámica especificado.<br/> y las etiquetas de total general utilizan celdas combinadas.|
| [preserve_formatting](/cells/python-net/es/aspose.cells.pivot/pivottable/preserve_formatting) |Indica si el formato se conserva cuando se actualiza o se vuelve a calcular la tabla dinámica.|
| [show_drill](/cells/python-net/es/aspose.cells.pivot/pivottable/show_drill) | Obtiene si se muestran los botones expandir/contraer.|
| [enable_drilldown](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_drilldown) | Obtiene si la profundización está habilitada.|
| [enable_field_dialog](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_field_dialog) | Indica si el cuadro de diálogo Campo de tabla dinámica está disponible<br/> cuando el usuario hace doble clic en el campo de la tabla dinámica.|
| [enable_field_list](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_field_list) | Obtiene si se habilita la lista de campos para la tabla dinámica.|
| [enable_wizard](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_wizard) | Indica si el Asistente para tablas dinámicas está disponible.|
| [subtotal_hidden_page_items](/cells/python-net/es/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Indica si los elementos de campo de página ocultos en el informe de tabla dinámica<br/>se incluyen en subtotales de filas y columnas, totales de bloque y totales generales.<br/> El valor predeterminado es Falso.|
| [grand_total_name](/cells/python-net/es/aspose.cells.pivot/pivottable/grand_total_name) | Devuelve la etiqueta de cadena de texto que se muestra en el encabezado de la columna o fila del total general.<br/> El valor predeterminado es la cadena "Gran Total".|
| [manual_update](/cells/python-net/es/aspose.cells.pivot/pivottable/manual_update) | Indica si el informe de tabla dinámica se vuelve a calcular solo a petición del usuario.|
| [is_multiple_field_filters](/cells/python-net/es/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Especifica un valor booleano que indica si los campos de una tabla dinámica pueden tener varios filtros establecidos.|
| [missing_items_limit](/cells/python-net/es/aspose.cells.pivot/pivottable/missing_items_limit) | Especifica un valor booleano que indica si los campos de una tabla dinámica pueden tener varios filtros establecidos.|
| [enable_data_value_editing](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_data_value_editing) |Especifica un valor booleano que indica si el usuario puede editar las celdas en el área de datos de la tabla dinámica.<br/> Habilitar la edición de celdas en el área de valores|
| [show_data_tips](/cells/python-net/es/aspose.cells.pivot/pivottable/show_data_tips) | Especifica un valor booleano que indica si se debe mostrar información sobre herramientas para las celdas de datos de la tabla dinámica.|
| [show_member_property_tips](/cells/python-net/es/aspose.cells.pivot/pivottable/show_member_property_tips) | Especifica un valor booleano que indica si la información de propiedad del miembro debe omitirse en la información sobre herramientas de la tabla dinámica.|
| [show_values_row](/cells/python-net/es/aspose.cells.pivot/pivottable/show_values_row) | Especifica un valor booleano que indica si se muestra la fila de valores.<br/> mostrar la fila de valores|
| [show_empty_col](/cells/python-net/es/aspose.cells.pivot/pivottable/show_empty_col) | Especifica un valor booleano que indica si se deben incluir columnas vacías en la tabla.|
| [show_empty_row](/cells/python-net/es/aspose.cells.pivot/pivottable/show_empty_row) | Especifica un valor booleano que indica si se deben incluir filas vacías en la tabla.|
| [field_list_sort_ascending](/cells/python-net/es/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Especifica un valor booleano que indica si los campos de la tabla dinámica están ordenados en un orden no predeterminado en la lista de campos.|
| [print_drill](/cells/python-net/es/aspose.cells.pivot/pivottable/print_drill) | Especifica un valor booleano que indica si se deben imprimir los indicadores de exploración.<br/> Imprima los botones de expandir/contraer cuando se muestren en la tabla dinámica.|
| [alt_text_title](/cells/python-net/es/aspose.cells.pivot/pivottable/alt_text_title) |Obtiene el título del altertext.|
| [alt_text_description](/cells/python-net/es/aspose.cells.pivot/pivottable/alt_text_description) | Obtiene la descripción del texto alternativo.|
| [name](/cells/python-net/es/aspose.cells.pivot/pivottable/name) | Obtiene el nombre de la tabla dinámica.|
| [column_header_caption](/cells/python-net/es/aspose.cells.pivot/pivottable/column_header_caption) | Obtiene el título del encabezado de columna de la tabla dinámica.|
| [indent](/cells/python-net/es/aspose.cells.pivot/pivottable/indent) | Especifica el incremento de sangría para el eje compacto y se puede utilizar para configurar el diseño del informe en formato compacto.|
| [row_header_caption](/cells/python-net/es/aspose.cells.pivot/pivottable/row_header_caption) | Obtiene el título del encabezado de fila de la tabla dinámica.|
| [show_row_header_caption](/cells/python-net/es/aspose.cells.pivot/pivottable/show_row_header_caption) | Indica si el título del encabezado de fila se muestra en el informe de tabla dinámica<br/> Indica si Mostrar títulos de campo y menús desplegables de filtro|
| [custom_list_sort](/cells/python-net/es/aspose.cells.pivot/pivottable/custom_list_sort) | Indica si se considera la lista personalizada incorporada al ordenar datos|
| [pivot_format_conditions](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_format_conditions) | Obtiene las condiciones de formato de la tabla dinámica.|
| [page_field_order](/cells/python-net/es/aspose.cells.pivot/pivottable/page_field_order) | Obtiene el orden en que se agregan los campos de página al diseño del informe de tabla dinámica.|
| [page_field_wrap_count](/cells/python-net/es/aspose.cells.pivot/pivottable/page_field_wrap_count) | Obtiene el número de campos de página en cada columna o fila del informe de tabla dinámica.|
| [tag](/cells/python-net/es/aspose.cells.pivot/pivottable/tag) | Obtiene una cadena guardada con el informe de tabla dinámica.|
| [save_data](/cells/python-net/es/aspose.cells.pivot/pivottable/save_data) | Indica si los datos del informe de tabla dinámica se guardan con el libro.|
| [refresh_data_on_opening_file](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indica si se actualizan los datos al abrir el archivo.|
| [refresh_data_flag](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data_flag) |Indica si se están actualizando datos o no.|
| [external_connection_data_source](/cells/python-net/es/aspose.cells.pivot/pivottable/external_connection_data_source) | Obtiene el origen de datos de la conexión externa.|
| [data_source](/cells/python-net/es/aspose.cells.pivot/pivottable/data_source) | Obtiene y establece el origen de datos de la tabla dinámica.|
| [pivot_formats](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_formats) | Obtiene la colección de formatos aplicados a la tabla dinámica.|
| [item_print_titles](/cells/python-net/es/aspose.cells.pivot/pivottable/item_print_titles) | Un bit que especifica si los títulos de los elementos pivotantes en el eje de la fila<br/> se repiten en cada página impresa para los campos dinámicos en forma tabular.|
| [print_titles](/cells/python-net/es/aspose.cells.pivot/pivottable/print_titles) | Indica si los títulos de impresión de la hoja de cálculo están configurados en función<br/> en el informe de tabla dinámica. El valor predeterminado es falso.|
| [display_immediate_items](/cells/python-net/es/aspose.cells.pivot/pivottable/display_immediate_items) | Indica si los elementos en las áreas de fila y columna son visibles<br/> cuando el área de datos de la tabla dinámica está vacía. El valor por defecto es verdadero.|
| [is_selected](/cells/python-net/es/aspose.cells.pivot/pivottable/is_selected) | Indica si la tabla dinámica está seleccionada.|
| [show_pivot_style_row_header](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Indica si el encabezado de fila en la tabla dinámica debe tener aplicado el estilo.|
| [show_pivot_style_column_header](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Indica si el encabezado de columna de la tabla dinámica debe tener aplicado el estilo.|
| [show_pivot_style_row_stripes](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indica si se aplica el formato de franja de fila.|
| [show_pivot_style_column_stripes](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indica si se aplica el formato de franja de columna.|
| [show_pivot_style_last_column](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indica si se aplica el formato de franja de columna.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [remove_field](/cells/python-net/es/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) |Elimina un campo de un área de campo específica|
| [remove_field](/cells/python-net/es/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) |Elimina un campo de un área de campo específica|
| [remove_field](/cells/python-net/es/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Eliminar campo de un área de campo específica|
| [add_field_to_area](/cells/python-net/es/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Agrega el campo al área específica.|
| [add_field_to_area](/cells/python-net/es/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Agrega el campo al área específica.|
| [add_field_to_area](/cells/python-net/es/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Agrega el campo al área específica.|
| [add_calculated_field](/cells/python-net/es/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Agrega un campo calculado al campo dinámico.|
| [add_calculated_field](/cells/python-net/es/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Agrega un campo calculado para pivotar el campo y arrastrarlo al área de datos.|
| [move](/cells/python-net/es/aspose.cells.pivot/pivottable/move/#int-int) | Mueve la tabla dinámica a una ubicación diferente en la hoja de trabajo.|
| [move](/cells/python-net/es/aspose.cells.pivot/pivottable/move/#str) | Mueve la tabla dinámica a una ubicación diferente en la hoja de trabajo.|
| [format](/cells/python-net/es/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Da formato al área seleccionada de la tabla dinámica.|
| [format](/cells/python-net/es/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Formatee la celda en el área de la tabla dinámica|
| [set_auto_group_field](/cells/python-net/es/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Establece el grupo de campos automático según la tabla dinámica.|
| [set_auto_group_field](/cells/python-net/es/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Establece el grupo de campos automático según la tabla dinámica.|
| [set_manual_group_field](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Establece el grupo de campos manual según la tabla dinámica.|
| [set_manual_group_field](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Establece el grupo de campos manual según la tabla dinámica.|
| [set_manual_group_field](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Establece el grupo de campos manual según la tabla dinámica.|
| [set_manual_group_field](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Establece el grupo de campos manual según la tabla dinámica.|
| [set_ungroup](/cells/python-net/es/aspose.cells.pivot/pivottable/set_ungroup/#int) | Conjuntos desagrupados por la tabla dinámica|
| [set_ungroup](/cells/python-net/es/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Conjuntos desagrupados por la tabla dinámica|
| [copy_style](/cells/python-net/es/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Copia el estilo con nombre de otra tabla dinámica.|
| [show_report_filter_page](/cells/python-net/es/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Muestra todas las páginas de filtrado del informe según PivotField, el PivotField debe estar ubicado en PageFields.|
| [show_report_filter_page_by_name](/cells/python-net/es/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Muestra todas las páginas de filtro del informe según el nombre de PivotField, el PivotField debe estar ubicado en PageFields.|
| [show_report_filter_page_by_index](/cells/python-net/es/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Mostrar todas las páginas de filtro del informe según el índice de posición en PageFields|
| [fields](/cells/python-net/es/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Obtiene los campos específicos por tipo de campo.|
| [change_data_source](/cells/python-net/es/aspose.cells.pivot/pivottable/change_data_source/#list) |Establezca los datos de origen de la tabla dinámica.<br/> Hoja1!$A$1:$C$3|
| [get_source](/cells/python-net/es/aspose.cells.pivot/pivottable/get_source/#) | Obtenga los datos de origen de la tabla dinámica.|
| [refresh_data](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data/#) | Actualiza los datos de la tabla dinámica y la configuración desde su fuente de datos.|
| [calculate_data](/cells/python-net/es/aspose.cells.pivot/pivottable/calculate_data/#) | Calcula los datos de la tabla dinámica en celdas.|
| [clear_data](/cells/python-net/es/aspose.cells.pivot/pivottable/clear_data/#) | Borrar los datos y el formato de la tabla dinámica|
| [calculate_range](/cells/python-net/es/aspose.cells.pivot/pivottable/calculate_range/#) | Calcula el rango de la tabla dinámica.|
| [format_all](/cells/python-net/es/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Formatee todas las celdas en el área de la tabla dinámica|
| [format_row](/cells/python-net/es/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Formatee los datos de la fila en el área de la tabla dinámica|
| [get_horizontal_breaks](/cells/python-net/es/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | obtener la lista de índice de filas de la tabla dinámica de saltos de página horizontales|
| [show_in_compact_form](/cells/python-net/es/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Diseña la tabla dinámica en forma compacta.|
| [show_in_outline_form](/cells/python-net/es/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Diseña la tabla dinámica en forma de esquema.|
| [show_in_tabular_form](/cells/python-net/es/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Diseña la tabla dinámica en forma tabular.|
| [get_cell_by_display_name](/cells/python-net/es/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Obtiene el objeto [`Cell`](/cells/python-net/es/aspose.cells/cell) por el nombre para mostrar de PivotField.|
| [get_children](/cells/python-net/es/aspose.cells.pivot/pivottable/get_children/#) | Obtiene las tablas dinámicas secundarias que utilizan estos datos de la tabla dinámica como fuente de datos.|



###  Ejemplo

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ver también
* módulo [`aspose.cells.pivot`](..)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
