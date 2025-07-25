---
title: GlobalizationSettings clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 740
url: /es/aspose.cells/globalizationsettings/
is_root: false
---
##  GlobalizationSettings clase
Representa la configuración de globalización.



El tipo GlobalizationSettings expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/__init__/#) | Construye una nueva instancia de GlobalizationSettings|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [chart_settings](/cells/python-net/es/aspose.cells/globalizationsettings/chart_settings) | Obtiene o establece la configuración de globalización para el gráfico.|
| [pivot_settings](/cells/python-net/es/aspose.cells/globalizationsettings/pivot_settings) | Obtiene o establece la configuración de globalización para la tabla dinámica.|
| [list_separator](/cells/python-net/es/aspose.cells/globalizationsettings/list_separator) | Obtiene el separador de listas, parámetros de función, etc.|
| [row_separator_of_formula_array](/cells/python-net/es/aspose.cells/globalizationsettings/row_separator_of_formula_array) | Obtiene el separador de filas en los datos de la matriz en la fórmula.|
| [column_separator_of_formula_array](/cells/python-net/es/aspose.cells/globalizationsettings/column_separator_of_formula_array) |Obtiene el separador de los elementos en los datos de fila de la matriz en la fórmula.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_pivot_total_name/#) | Obtiene el nombre de la etiqueta "Total" en la tabla dinámica.<br/> Debe anular este método cuando la tabla dinámica contiene dos o más campos dinámicos en el área de datos.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_pivot_grand_total_name/#) | Obtiene el nombre de la etiqueta "Total general" en la tabla dinámica.|
| [`get_multiple_items_name(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_multiple_items_name/#) | Obtiene el nombre de la etiqueta "(Varios elementos)" en la tabla dinámica.|
| [`get_all_name(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_all_name/#) | Obtiene el nombre de la etiqueta "(Todos)" en la tabla dinámica.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_protection_name_of_pivot_table/#) | Obtiene el nombre de protección en la tabla dinámica.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_column_labels_of_pivot_table/#) | Obtiene el nombre de la etiqueta "Etiquetas de columna" en la tabla dinámica.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_row_labels_name_of_pivot_table/#) | Obtiene el nombre de la etiqueta "Etiquetas de fila" en la tabla dinámica.|
| [`get_empty_data_name(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_empty_data_name/#) | Obtiene el nombre de la etiqueta "(en blanco)" en la tabla dinámica.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_data_field_header_name_of_pivot_table/#) | Obtiene el nombre del encabezado del campo del área de valor en la tabla dinámica.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | Obtiene el nombre del tipo [`PivotFieldSubtotalType`](/cells/python-net/es/aspose.cells.pivot/pivotfieldsubtotaltype) en la tabla dinámica.|
| [`get_total_name(self, function_type)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Obtiene el nombre total de la función.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Obtiene el nombre total general de la función.|
| [`get_default_sheet_name(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_default_sheet_name/#) |Obtiene el nombre de hoja predeterminado para agregar hojas de trabajo automáticamente.<br/> El valor predeterminado es "Hoja".|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_table_row_type_of_headers/#) | Obtiene el nombre del tipo de filas de la tabla que constan del encabezado de la tabla.<br/> El valor predeterminado es "Encabezados", por lo que en la fórmula "#Encabezados" representa el encabezado de la tabla.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_table_row_type_of_data/#) | Obtiene el nombre del tipo de filas de la tabla que constan de la región de datos de la tabla referenciada.<br/> El valor predeterminado es "Datos", por lo que en la fórmula "#Datos" representa la región de datos de la tabla.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_table_row_type_of_all/#) | Obtiene el nombre del tipo de filas de la tabla que consta de todas las filas de la tabla referenciada.<br/> El valor predeterminado es "Todos", por lo que en la fórmula "#Todos" representa todas las filas de la tabla referenciada.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_table_row_type_of_totals/#) | Obtiene el nombre del tipo de filas de la tabla que consta de la fila total de la tabla referenciada.<br/> El valor predeterminado es "Totales", por lo que en la fórmula "#Totales" representa la fila total de la tabla referenciada.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_table_row_type_of_current/#) | Obtiene el nombre del tipo de filas de la tabla que constan de la fila actual en la tabla referenciada.<br/>El valor predeterminado es "Esta fila", por lo que en la fórmula "#Esta fila" representa la fila actual en la tabla referenciada.|
| [`get_error_value_string(self, err)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_error_value_string/#str) | Obtiene el valor de la cadena de visualización para el valor de error de la celda|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_boolean_value_string/#bool) | Obtiene el valor de la cadena de visualización para el valor booleano de la celda|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_local_function_name/#str) | Obtiene el nombre de la función dependiente de la configuración regional de acuerdo con el nombre de función estándar dado.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_standard_function_name/#str) | Obtiene el nombre de la función estándar según el nombre de la función dependiente de la configuración regional dada.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_local_built_in_name/#str) | Obtiene el texto dependiente de la configuración regional para el nombre incorporado de acuerdo con el texto estándar dado.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_standard_built_in_name/#str) | Obtiene el texto estándar del nombre incorporado de acuerdo con el texto dependiente de la configuración regional dada.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_standard_header_footer_font_style_name/#str) | Obtiene el nombre del estilo de fuente inglés estándar (Regular, Negrita, Cursiva) para el encabezado/pie de página de acuerdo con el nombre del estilo de fuente de la configuración regional dada.|
| [`get_comment_title_name(self, type)`](/cells/python-net/es/aspose.cells/globalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Obtiene el nombre del título del comentario dependiente de la configuración regional según el tipo de título del comentario.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/es/aspose.cells/globalizationsettings/compare/#str-str-bool) | Compara dos valores de cadena según determinadas reglas de intercalación.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`PivotFieldSubtotalType`](/cells/python-net/es/aspose.cells.pivot/pivotfieldsubtotaltype)
