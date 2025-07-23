---
title: PivotTable clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 230
url: /es/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable clase
Descripción resumida para PivotTable.



El tipo PivotTable expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/es/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Especifica si la tabla dinámica es compatible con Excel2003 al actualizar la tabla dinámica.<br/>Si es verdadero, una cadena debe ser menor o igual a 255 caracteres, por lo que si la cadena es mayor a 255 caracteres,<br/>se truncará. Si es falso, una cadena no tendrá la restricción antes mencionada.<br/> El valor predeterminado es verdadero.|
| [refreshed_by_who](/cells/python-net/es/aspose.cells.pivot/pivottable/refreshed_by_who) | Obtiene el nombre del último usuario que actualizó esta tabla dinámica|
| [refresh_date](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_date) | Obtiene la última fecha y hora en que se actualizó la tabla dinámica.|
| [pivot_table_style_name](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_table_style_name) | Obtiene y establece el nombre del estilo de tabla dinámica.|
| [pivot_table_style_type](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_table_style_type) | Obtiene y establece el estilo de tabla dinámica incorporado.|
| [column_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/column_fields) | Devuelve un objeto PivotFields que actualmente se muestra como campos de columna.|
| [row_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/row_fields) | Devuelve un objeto PivotFields que actualmente se muestra como campos de fila.|
| [page_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/page_fields) | Devuelve un objeto PivotFields que actualmente se muestra como campos de página.|
| [data_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/data_fields) | Obtiene un objeto PivotField que representa todos los campos de datos en una tabla dinámica.<br/>Solo lectura. Se inicializará solo cuando haya dos o más campos de datos en DataPiovtFiels.<br/> Solo se utiliza para agregar un DataPivotField al área de filas/columnas de la tabla dinámica. El valor predeterminado es en el área de filas.|
| [data_field](/cells/python-net/es/aspose.cells.pivot/pivottable/data_field) |Obtiene un objeto [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield) que representa todos los campos de datos en una tabla dinámica.<br/>Sólo lectura.<br/>Solo se creará cuando haya dos o más campos de datos en la región de datos.<br/> Por defecto, se encuentra en la región de filas. Puede arrastrarlo a la región de filas/columnas con el método PivotTable.AddFieldToArea().|
| [base_fields](/cells/python-net/es/aspose.cells.pivot/pivottable/base_fields) | Devuelve todos los campos dinámicos base en la tabla dinámica.|
| [pivot_filters](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_filters) | Devuelve todos los filtros de los campos dinámicos en la tabla dinámica.|
| [column_range](/cells/python-net/es/aspose.cells.pivot/pivottable/column_range) | Devuelve un objeto CellArea que representa el rango<br/> Que contiene el área de columna en el informe de tabla dinámica. Solo lectura.|
| [row_range](/cells/python-net/es/aspose.cells.pivot/pivottable/row_range) | Devuelve un objeto CellArea que representa el rango<br/> Que contiene el área de fila en el informe de tabla dinámica. Solo lectura.|
| [data_body_range](/cells/python-net/es/aspose.cells.pivot/pivottable/data_body_range) | Devuelve un objeto [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) que representa el rango que contiene el área de datos<br/> En la lista entre la fila de encabezado y la fila de inserción. Solo lectura.|
| [table_range1](/cells/python-net/es/aspose.cells.pivot/pivottable/table_range1) | Devuelve un objeto CellArea que representa el rango que contiene todo el informe de tabla dinámica.<br/> pero no incluye campos de página. Solo lectura.|
| [table_range2](/cells/python-net/es/aspose.cells.pivot/pivottable/table_range2) | Devuelve un objeto CellArea que representa el rango que contiene todo el informe de tabla dinámica.<br/> Incluye campos de página. Solo lectura.|
| [is_grid_drop_zones](/cells/python-net/es/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Indica si el informe de tabla dinámica muestra el diseño de tabla dinámica clásico.<br/> (permite arrastrar campos en la cuadrícula)|
| [show_column_grand_totals](/cells/python-net/es/aspose.cells.pivot/pivottable/show_column_grand_totals) |Indica si se deben mostrar los totales generales de las columnas de esta tabla dinámica.|
| [show_row_grand_totals](/cells/python-net/es/aspose.cells.pivot/pivottable/show_row_grand_totals) | Indica si se deben mostrar los totales generales de las filas de la tabla dinámica.|
| [column_grand](/cells/python-net/es/aspose.cells.pivot/pivottable/column_grand) | Indica si el informe de tabla dinámica muestra totales generales de las columnas.|
| [row_grand](/cells/python-net/es/aspose.cells.pivot/pivottable/row_grand) | Indica si se deben mostrar los totales generales de las filas de esta tabla dinámica.|
| [display_null_string](/cells/python-net/es/aspose.cells.pivot/pivottable/display_null_string) | Indica si el informe de tabla dinámica muestra una cadena personalizada si el valor es nulo.|
| [null_string](/cells/python-net/es/aspose.cells.pivot/pivottable/null_string) | Obtiene la cadena que se muestra en las celdas que contienen valores nulos<br/> cuando la propiedad DisplayNullString es verdadera. El valor predeterminado es una cadena vacía.|
| [display_error_string](/cells/python-net/es/aspose.cells.pivot/pivottable/display_error_string) | Indica si el informe de tabla dinámica muestra una cadena personalizada en las celdas que contienen errores.|
| [data_field_header_name](/cells/python-net/es/aspose.cells.pivot/pivottable/data_field_header_name) | Obtiene y establece el nombre del encabezado del campo del área de valor en la tabla dinámica.|
| [error_string](/cells/python-net/es/aspose.cells.pivot/pivottable/error_string) | Obtiene la cadena que se muestra en las celdas que contienen errores.<br/> cuando la propiedad DisplayErrorString es verdadera. El valor predeterminado es una cadena vacía.|
| [is_auto_format](/cells/python-net/es/aspose.cells.pivot/pivottable/is_auto_format) | Indica si el informe de tabla dinámica se formatea automáticamente.<br/>Casilla de verificación "Autoformato de tabla" que se encuentra en la opción de tabla dinámica de Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/es/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Indica si se ajusta automáticamente el ancho de la columna al actualizar|
| [auto_format_type](/cells/python-net/es/aspose.cells.pivot/pivottable/auto_format_type) | Obtiene y establece el tipo de formato automático de la tabla dinámica.|
| [has_blank_rows](/cells/python-net/es/aspose.cells.pivot/pivottable/has_blank_rows) | Indica si se deben agregar filas en blanco.<br/> Esta propiedad solo se aplica a los tipos de formato automático de tabla dinámica que necesitan agregar filas en blanco.|
| [merge_labels](/cells/python-net/es/aspose.cells.pivot/pivottable/merge_labels) | Verdadero si las etiquetas de elemento de fila exterior, elemento de columna, subtotal y total general del informe de tabla dinámica especificado utilizan celdas combinadas.|
| [preserve_formatting](/cells/python-net/es/aspose.cells.pivot/pivottable/preserve_formatting) | Indica si se conserva el formato cuando se actualiza o se recalcula la tabla dinámica.|
| [show_drill](/cells/python-net/es/aspose.cells.pivot/pivottable/show_drill) | Obtiene y establece si se muestran los botones expandir/contraer.|
| [enable_drilldown](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_drilldown) | Obtiene si la exploración en profundidad está habilitada.|
| [enable_field_dialog](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_field_dialog) | Indica si el cuadro de diálogo Campo de tabla dinámica está disponible<br/> cuando el usuario hace doble clic en el campo de tabla dinámica.|
| [enable_field_list](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_field_list) | Indica si la lista de campos de la tabla dinámica está disponible en la vista de Excel.|
| [enable_wizard](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_wizard) | Indica si el Asistente para tablas dinámicas está disponible.|
| [subtotal_hidden_page_items](/cells/python-net/es/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |Indica si hay elementos de campos de página ocultos en el informe de tabla dinámica<br/>se incluyen en los subtotales de filas y columnas, los totales de bloque y los totales generales.<br/> El valor predeterminado es Falso.|
| [grand_total_name](/cells/python-net/es/aspose.cells.pivot/pivottable/grand_total_name) | Devuelve la etiqueta que se muestra en el encabezado de fila o columna de total general.<br/> El valor predeterminado es la cadena "Total general".|
| [manual_update](/cells/python-net/es/aspose.cells.pivot/pivottable/manual_update) | Indica si el informe de tabla dinámica se recalcula solo a solicitud del usuario.|
| [is_multiple_field_filters](/cells/python-net/es/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Especifica un valor booleano que indica si los campos de una tabla dinámica pueden tener múltiples filtros establecidos en ellos.|
| [allow_multiple_filters_per_field](/cells/python-net/es/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | Especifica un valor booleano que indica si los campos de una tabla dinámica pueden tener múltiples filtros establecidos en ellos.|
| [missing_items_limit](/cells/python-net/es/aspose.cells.pivot/pivottable/missing_items_limit) | Especifica un valor booleano que indica si los campos de una tabla dinámica pueden tener múltiples filtros establecidos en ellos.|
| [enable_data_value_editing](/cells/python-net/es/aspose.cells.pivot/pivottable/enable_data_value_editing) | Especifica un valor booleano que indica si el usuario puede editar las celdas en el área de datos de la tabla dinámica.<br/> Habilitar la edición de celdas en el área de valores|
| [show_data_tips](/cells/python-net/es/aspose.cells.pivot/pivottable/show_data_tips) | Especifica un valor booleano que indica si se deben mostrar informaciones sobre herramientas para las celdas de datos de la tabla dinámica.|
| [show_member_property_tips](/cells/python-net/es/aspose.cells.pivot/pivottable/show_member_property_tips) | Especifica un valor booleano que indica si la información de las propiedades de los miembros debe omitirse en la información sobre herramientas de la tabla dinámica.|
| [show_values_row](/cells/python-net/es/aspose.cells.pivot/pivottable/show_values_row) | Indica si se muestran valores en fila.|
| [show_empty_col](/cells/python-net/es/aspose.cells.pivot/pivottable/show_empty_col) | Indica si se deben incluir columnas vacías en la tabla|
| [show_empty_row](/cells/python-net/es/aspose.cells.pivot/pivottable/show_empty_row) |Indica si se deben incluir filas vacías en la tabla.|
| [field_list_sort_ascending](/cells/python-net/es/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Indica si los campos de la tabla dinámica están ordenados en un orden no predeterminado en la lista de campos.|
| [print_drill](/cells/python-net/es/aspose.cells.pivot/pivottable/print_drill) | Especifica un valor booleano que indica si se deben imprimir los indicadores de perforación.<br/> Imprimir botones para expandir/contraer cuando se muestran en la tabla dinámica.|
| [alt_text_title](/cells/python-net/es/aspose.cells.pivot/pivottable/alt_text_title) | Obtiene y establece el título del texto alternativo.|
| [alt_text_description](/cells/python-net/es/aspose.cells.pivot/pivottable/alt_text_description) | Obtiene la descripción del texto alternativo.|
| [name](/cells/python-net/es/aspose.cells.pivot/pivottable/name) | Obtiene el nombre de la tabla dinámica|
| [column_header_caption](/cells/python-net/es/aspose.cells.pivot/pivottable/column_header_caption) | Obtiene el título del encabezado de columna de la tabla dinámica.|
| [indent](/cells/python-net/es/aspose.cells.pivot/pivottable/indent) | Especifica el incremento de sangría para el eje compacto y se puede utilizar para establecer el diseño del informe en formato compacto.|
| [row_header_caption](/cells/python-net/es/aspose.cells.pivot/pivottable/row_header_caption) | Obtiene el título del encabezado de fila de la tabla dinámica.|
| [show_row_header_caption](/cells/python-net/es/aspose.cells.pivot/pivottable/show_row_header_caption) | Indica si el título del encabezado de fila se muestra en el informe de tabla dinámica<br/> Indica si se muestran los títulos de los campos y los filtros desplegables|
| [custom_list_sort](/cells/python-net/es/aspose.cells.pivot/pivottable/custom_list_sort) | Indica si se tiene en cuenta la lista personalizada incorporada al ordenar datos|
| [pivot_format_conditions](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_format_conditions) | Obtiene las condiciones de formato de la tabla dinámica.|
| [conditional_formats](/cells/python-net/es/aspose.cells.pivot/pivottable/conditional_formats) | Obtiene los formatos condicionales de la tabla dinámica.|
| [page_field_order](/cells/python-net/es/aspose.cells.pivot/pivottable/page_field_order) |Obtiene y establece el orden en que se agregan los campos de página al diseño del informe de tabla dinámica.|
| [page_field_wrap_count](/cells/python-net/es/aspose.cells.pivot/pivottable/page_field_wrap_count) | Obtiene el número de campos de página en cada columna o fila del informe de tabla dinámica.|
| [tag](/cells/python-net/es/aspose.cells.pivot/pivottable/tag) | Obtiene una cadena guardada con el informe de tabla dinámica.|
| [save_data](/cells/python-net/es/aspose.cells.pivot/pivottable/save_data) | Indica si los datos del informe de tabla dinámica se guardan con el libro de trabajo.|
| [refresh_data_on_opening_file](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indica si se deben actualizar los datos al abrir el archivo.|
| [refresh_data_flag](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data_flag) | Indica si se actualizan los datos o no.|
| [source_type](/cells/python-net/es/aspose.cells.pivot/pivottable/source_type) | Obtiene el tipo de fuente de datos de la tabla dinámica.|
| [external_connection_data_source](/cells/python-net/es/aspose.cells.pivot/pivottable/external_connection_data_source) | Obtiene la fuente de datos de conexión externa.|
| [data_source](/cells/python-net/es/aspose.cells.pivot/pivottable/data_source) | Obtiene y establece la fuente de datos de la tabla dinámica.|
| [pivot_formats](/cells/python-net/es/aspose.cells.pivot/pivottable/pivot_formats) | Obtiene la colección de formatos aplicados a la tabla dinámica.|
| [item_print_titles](/cells/python-net/es/aspose.cells.pivot/pivottable/item_print_titles) | Indica si los nombres de PivotItem deben repetirse en la parte superior de cada página impresa.|
| [repeat_items_on_each_printed_page](/cells/python-net/es/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | Indica si los títulos de los elementos pivote en el área de fila se repiten en cada página impresa para los campos pivote en formato tabular.|
| [print_titles](/cells/python-net/es/aspose.cells.pivot/pivottable/print_titles) | Indica si los títulos de impresión para la hoja de trabajo se establecen en función<br/> En el informe de tabla dinámica. El valor predeterminado es falso.|
| [display_immediate_items](/cells/python-net/es/aspose.cells.pivot/pivottable/display_immediate_items) |Indica si los elementos en las áreas de filas y columnas son visibles<br/> Cuando el área de datos de la tabla dinámica está vacía. El valor predeterminado es "true".|
| [is_selected](/cells/python-net/es/aspose.cells.pivot/pivottable/is_selected) | Indica si esta tabla dinámica está seleccionada.|
| [show_pivot_style_row_header](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Indica si se debe aplicar el estilo al encabezado de fila de la tabla dinámica.|
| [show_pivot_style_column_header](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Indica si se debe aplicar el estilo al encabezado de columna de la tabla dinámica.|
| [show_pivot_style_row_stripes](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indica si se aplica el formato de franja de fila.|
| [show_pivot_style_column_stripes](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indica si se aplica el formato de banda para la columna.|
| [show_pivot_style_last_column](/cells/python-net/es/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indica si se aplica el formato de columna.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/es/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | Elimina un campo de un área de campo específica|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/es/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | Elimina un campo de un área de campo específica|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/es/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Eliminar campo de un área de campo específica|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/es/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | Agrega el campo al área específica.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/es/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | Agrega el campo al área específica.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/es/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Agrega el campo al área específica.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/es/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Agrega un campo calculado al campo pivote.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/es/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Agrega un campo calculado al campo pivote y lo arrastra al área de datos.|
| [`move(self, row, column)`](/cells/python-net/es/aspose.cells.pivot/pivottable/move/#int-int) | Mueve la tabla dinámica a una ubicación diferente en la hoja de cálculo.|
| [`move(self, dest_cell_name)`](/cells/python-net/es/aspose.cells.pivot/pivottable/move/#str) | Mueve la tabla dinámica a una ubicación diferente en la hoja de cálculo.|
| [`move_to(self, row, column)`](/cells/python-net/es/aspose.cells.pivot/pivottable/move_to/#int-int) | Mueve la tabla dinámica a una ubicación diferente en la hoja de cálculo.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/es/aspose.cells.pivot/pivottable/move_to/#str) | Mueve la tabla dinámica a una ubicación diferente en la hoja de cálculo.|
| [`get_source(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_source/#) | Obtener los datos de origen de la tabla dinámica.|
| [`get_source(self, is_original)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_source/#bool) | Obtener los datos de origen de la tabla dinámica.|
| [`refresh_data(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data/#) |Actualiza los datos y la configuración de la tabla dinámica desde su fuente de datos.|
| [`refresh_data(self, option)`](/cells/python-net/es/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | Actualiza los datos y la configuración de la tabla dinámica desde su fuente de datos con opciones.|
| [`calculate_data(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/calculate_data/#) | Calcula los datos de la tabla dinámica en celdas.|
| [`calculate_data(self, option)`](/cells/python-net/es/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | Cálculo de tablas dinámicas con opciones|
| [`format(self, pivot_area, style)`](/cells/python-net/es/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | Formatea el área seleccionada de la tabla dinámica.|
| [`format(self, ca, style)`](/cells/python-net/es/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | Formatea el área seleccionada de la tabla dinámica.|
| [`format(self, row, column, style)`](/cells/python-net/es/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | Formatear la celda en el área de la tabla dinámica|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Establece el grupo de campos automáticos mediante la tabla dinámica.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | Establece el grupo de campos automáticos mediante la tabla dinámica.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Establece el grupo de campos manualmente mediante la tabla dinámica.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | Establece el grupo de campos manualmente mediante la tabla dinámica.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | Establece el grupo de campos manualmente mediante la tabla dinámica.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | Establece el grupo de campos manualmente mediante la tabla dinámica.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_ungroup/#int) | Los conjuntos se desagrupan por la tabla dinámica|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/es/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | Los conjuntos se desagrupan por la tabla dinámica|
| [`copy_style(self, pivot_table)`](/cells/python-net/es/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | Copia el estilo nombrado de otra tabla dinámica.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | Mostrar todas las páginas de filtro del informe según PivotField, el PivotField debe estar ubicado en PageFields.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Mostrar todas las páginas de filtro del informe según el nombre del campo dinámico, el campo dinámico debe estar ubicado en PageFields.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Mostrar todas las páginas de filtro de informes según el índice de posición en PageFields|
| [`get_fields(self, field_type)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | Obtiene la lista de campos pivote específicos por región.|
| [`fields(self, field_type)`](/cells/python-net/es/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | Obtiene los campos específicos por tipo de campo.|
| [`get_source_data_connections(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_source_data_connections/#) |Obtiene las fuentes de datos de conexión externa.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | Obtiene el nombre de las conexiones de datos de fuentes externas.|
| [`change_data_source(self, source)`](/cells/python-net/es/aspose.cells.pivot/pivottable/change_data_source/#list) | Establecer los datos de origen de la tabla dinámica.|
| [`clear_data(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/clear_data/#) | Borrar los datos y el formato de la tabla dinámica|
| [`calculate_range(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/calculate_range/#) | Calcula el rango de la tabla dinámica.|
| [`format_all(self, style)`](/cells/python-net/es/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | Formatear todas las celdas en el área de la tabla dinámica|
| [`format_row(self, row, style)`](/cells/python-net/es/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | Formatear los datos de fila en el área de la tabla dinámica|
| [`select_area(self, ca)`](/cells/python-net/es/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | Seleccione un área de la vista de tabla dinámica.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | Mostrar el detalle de un elemento en la región de datos en una nueva tabla.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | Obtiene saltos de página horizontales de esta tabla dinámica.|
| [`get_horizontal_breaks(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Obtiene la lista de índices de filas de la tabla dinámica de saltos de página horizontales|
| [`show_in_compact_form(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Diseña la tabla dinámica en forma compacta.|
| [`show_in_outline_form(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Diseña la tabla dinámica en forma de esquema.|
| [`show_in_tabular_form(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Diseña la tabla dinámica en formato tabular.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Obtiene el objeto [`Cell`](/cells/python-net/es/aspose.cells/cell) por el nombre para mostrar de PivotField.|
| [`get_children(self)`](/cells/python-net/es/aspose.cells.pivot/pivottable/get_children/#) | Obtiene las tablas dinámicas secundarias que utilizan estos datos de tabla dinámica como fuente de datos.|



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
* clase [`CellArea`](/cells/python-net/es/aspose.cells/cellarea)
* clase [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield)
