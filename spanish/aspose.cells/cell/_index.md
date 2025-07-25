---
title: Cell clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells/cell/
is_root: false
---
##  Cell clase
Encapsula el objeto que representa una sola celda del Libro de trabajo.



El tipo Cell expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [worksheet](/cells/python-net/es/aspose.cells/cell/worksheet) | Obtiene la hoja de trabajo principal.|
| [date_time_value](/cells/python-net/es/aspose.cells/cell/date_time_value) | Obtiene el valor de fecha y hora contenido en la celda.|
| [row](/cells/python-net/es/aspose.cells/cell/row) | Obtiene el número de fila (basado en cero) de la celda.|
| [column](/cells/python-net/es/aspose.cells/cell/column) | Obtiene el número de columna (basado en cero) de la celda.|
| [is_formula](/cells/python-net/es/aspose.cells/cell/is_formula) | Representa si la celda especificada contiene fórmula.|
| [has_custom_function](/cells/python-net/es/aspose.cells/cell/has_custom_function) |Comprueba si hay una función personalizada (función no compatible) en la fórmula de esta celda.|
| [type](/cells/python-net/es/aspose.cells/cell/type) | Representa el tipo de valor de celda.|
| [name](/cells/python-net/es/aspose.cells/cell/name) | Obtiene el nombre de la celda.|
| [is_error_value](/cells/python-net/es/aspose.cells/cell/is_error_value) | Comprueba si el valor de esta celda es un error.|
| [is_numeric_value](/cells/python-net/es/aspose.cells/cell/is_numeric_value) | Indica si el valor de esta celda es numérico (int, double y datetime)|
| [string_value](/cells/python-net/es/aspose.cells/cell/string_value) | Obtiene el valor de la cadena contenida en la celda. Si el tipo de esta celda es cadena, devuelve el valor de la cadena.<br/>Para otros tipos de celdas, se devolverá el valor de la cadena formateada (formateada con el estilo especificado de esta celda).<br/>El valor de la celda formateada es el mismo que se puede obtener de Excel al copiar una celda como texto (por ejemplo,<br/> copiar la celda al editor de texto o exportar a csv).|
| [string_value_without_format](/cells/python-net/es/aspose.cells/cell/string_value_without_format) | Obtiene el valor de la celda como cadena sin ningún formato.|
| [number_category_type](/cells/python-net/es/aspose.cells/cell/number_category_type) | Representa el tipo de categoría del formato de número de esta celda.|
| [display_string_value](/cells/python-net/es/aspose.cells/cell/display_string_value) | Obtiene el valor de la cadena formateada de esta celda según el estilo de visualización de la celda.|
| [int_value](/cells/python-net/es/aspose.cells/cell/int_value) | Obtiene el valor entero contenido en la celda.|
| [double_value](/cells/python-net/es/aspose.cells/cell/double_value) | Obtiene el valor doble contenido en la celda.|
| [float_value](/cells/python-net/es/aspose.cells/cell/float_value) | Obtiene el valor flotante contenido en la celda.|
| [bool_value](/cells/python-net/es/aspose.cells/cell/bool_value) | Obtiene el valor booleano contenido en la celda.|
| [has_custom_style](/cells/python-net/es/aspose.cells/cell/has_custom_style) | Indica si esta celda tiene configuraciones de estilo personalizadas (diferentes de la predeterminada heredada)<br/>de la fila, columna o libro de trabajo correspondiente).|
| [shared_style_index](/cells/python-net/es/aspose.cells/cell/shared_style_index) | Obtiene el índice de estilo compartido de la celda en el grupo de estilos.|
| [formula](/cells/python-net/es/aspose.cells/cell/formula) | Obtiene o establece una fórmula de [`Cell`](/cells/python-net/es/aspose.cells/cell).|
| [formula_local](/cells/python-net/es/aspose.cells/cell/formula_local) | Obtenga la fórmula con formato regional de la celda.|
| [r1c1_formula](/cells/python-net/es/aspose.cells/cell/r1c1_formula) | Obtiene o establece una fórmula F1C1 de [`Cell`](/cells/python-net/es/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/es/aspose.cells/cell/contains_external_link) | Indica si esta celda contiene un enlace externo.<br/> Sólo se aplica cuando la celda es una celda de fórmula.|
| [is_array_header](/cells/python-net/es/aspose.cells/cell/is_array_header) | Indica que la fórmula de la celda es una fórmula de matriz.<br/> y es la primera celda de la matriz.|
| [is_dynamic_array_formula](/cells/python-net/es/aspose.cells/cell/is_dynamic_array_formula) | Indica si la fórmula de la celda es una fórmula de matriz dinámica (verdadero) o una fórmula de matriz heredada (falso).|
| [is_array_formula](/cells/python-net/es/aspose.cells/cell/is_array_formula) | Indica si la fórmula de celda es una fórmula de matriz.|
| [is_in_array](/cells/python-net/es/aspose.cells/cell/is_in_array) | Indica si la fórmula de celda es una fórmula de matriz.|
| [is_shared_formula](/cells/python-net/es/aspose.cells/cell/is_shared_formula) | Indica si la fórmula de la celda es parte de una fórmula compartida.|
| [is_table_formula](/cells/python-net/es/aspose.cells/cell/is_table_formula) | Indica si esta celda es parte de la fórmula de la tabla.|
| [is_in_table](/cells/python-net/es/aspose.cells/cell/is_in_table) | Indica si esta celda es parte de la fórmula de la tabla.|
| [value](/cells/python-net/es/aspose.cells/cell/value) | Obtiene/establece el valor contenido en esta celda.|
| [is_style_set](/cells/python-net/es/aspose.cells/cell/is_style_set) | Indica si el estilo de la celda está definido. Si devuelve "falso", significa que la celda tiene un formato predeterminado.|
| [is_merged](/cells/python-net/es/aspose.cells/cell/is_merged) | Comprueba si una celda es parte de un rango fusionado o no.|
| [comment](/cells/python-net/es/aspose.cells/cell/comment) |Obtiene el comentario de esta celda.|
| [html_string](/cells/python-net/es/aspose.cells/cell/html_string) | Obtiene y establece la cadena html que contiene datos y algunos formatos en esta celda.|
| [is_check_box_style](/cells/python-net/es/aspose.cells/cell/is_check_box_style) | Indica si se debe configurar esta celda como casilla de verificación.|
| [embedded_image](/cells/python-net/es/aspose.cells/cell/embedded_image) | Obtiene y establece la imagen incrustada en la celda.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/es/aspose.cells/cell/put_value/#bool) | Coloca un valor booleano en la celda.|
| [`put_value(self, int_value)`](/cells/python-net/es/aspose.cells/cell/put_value/#int) | Coloca un valor entero en la celda.|
| [`put_value(self, double_value)`](/cells/python-net/es/aspose.cells/cell/put_value/#float) | Coloca un valor doble en la celda.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/es/aspose.cells/cell/put_value/#str-bool-bool) | Coloca un valor en la celda, si corresponde, el valor se convertirá a otro tipo de datos y se restablecerá el formato de número de la celda.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/es/aspose.cells/cell/put_value/#str-bool) | Coloca un valor de cadena en la celda y convierte el valor a otro tipo de datos si corresponde.|
| [`put_value(self, string_value)`](/cells/python-net/es/aspose.cells/cell/put_value/#str) | Coloca un valor de cadena en la celda.|
| [`put_value(self, date_time)`](/cells/python-net/es/aspose.cells/cell/put_value/#datetime) | Coloca un valor de fecha y hora en la celda.|
| [`put_value(self, object_value)`](/cells/python-net/es/aspose.cells/cell/put_value/#any) | Coloca un valor de objeto en la celda.|
| [`get_display_style(self)`](/cells/python-net/es/aspose.cells/cell/get_display_style/#) | Obtiene el estilo de visualización de esta celda.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/es/aspose.cells/cell/get_display_style/#bool) | Obtiene el estilo de visualización de esta celda.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/es/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Obtiene el estilo de visualización de esta celda.|
| [`get_style(self)`](/cells/python-net/es/aspose.cells/cell/get_style/#) | Obtiene el estilo de celda.|
| [`get_style(self, check_borders)`](/cells/python-net/es/aspose.cells/cell/get_style/#bool) | Si checkBorders es verdadero, verifica si los bordes de otras celdas afectarán el estilo de esta celda.|
| [`set_style(self, style)`](/cells/python-net/es/aspose.cells/cell/set_style/#aspose.cells.style) | Establece el estilo de celda.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/es/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Aplicar la propiedad de estilo modificada a la celda.|
| [`set_style(self, style, flag)`](/cells/python-net/es/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Aplicar el estilo de celda basado en banderas.|
| [`set_formula(self, formula, value)`](/cells/python-net/es/aspose.cells/cell/set_formula/#str-any) | Establezca la fórmula y el valor (resultado calculado) de la fórmula.|
| [`set_formula(self, formula, options)`](/cells/python-net/es/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Establezca la fórmula y el valor (resultado calculado) de la fórmula.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/es/aspose.cells/cell/set_formula/#str-bool-bool-any) | Establezca la fórmula y el valor de la fórmula.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/es/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Establezca la fórmula y el valor (resultado calculado) de la fórmula.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Establece una fórmula de matriz en un rango de celdas.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int) | Establece una fórmula de matriz (fórmula de matriz heredada ingresada mediante CTRL+MAYÚS+ENTRAR en MS Excel) en un rango de celdas.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Establece una fórmula de matriz en un rango de celdas.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Establece una fórmula de matriz en un rango de celdas.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Establece una fórmula en un rango de celdas.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int) | Establece fórmulas compartidas en un rango de celdas.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Establece fórmulas compartidas en un rango de celdas.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Establece fórmulas compartidas en un rango de celdas.|
| [`get_leafs(self)`](/cells/python-net/es/aspose.cells/cell/get_leafs/#) | Obtenga todas las celdas que hacen referencia a esta celda directamente y que deben actualizarse cuando se modifica esta celda.|
| [`get_leafs(self, recursive)`](/cells/python-net/es/aspose.cells/cell/get_leafs/#bool) | Obtenga todas las celdas que se actualizarán cuando se modifique esta celda.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/es/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Establece una fórmula de matriz dinámica y hace que la fórmula se extienda a las celdas vecinas si es posible.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/es/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Establece una fórmula de matriz dinámica y hace que la fórmula se extienda a las celdas vecinas si es posible.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/es/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Establece una fórmula de matriz dinámica y hace que la fórmula se extienda a las celdas vecinas si es posible.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Cree una tabla de datos de dos variables para el rango dado a partir de esta celda.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Cree una tabla de datos de una variable para el rango dado a partir de esta celda.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Cree una tabla de datos de dos variables para el rango dado a partir de esta celda.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Cree una tabla de datos de una variable para el rango dado a partir de esta celda.|
| [`get_characters(self)`](/cells/python-net/es/aspose.cells/cell/get_characters/#) | Devuelve todos los objetos de Personajes<br/> que representa un rango de caracteres dentro del texto de la celda.|
| [`get_characters(self, flag)`](/cells/python-net/es/aspose.cells/cell/get_characters/#bool) | Devuelve todos los objetos de Personajes<br/> que representa un rango de caracteres dentro del texto de la celda.|
| [`calculate(self, options)`](/cells/python-net/es/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Calcula la fórmula de la celda.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/es/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Obtiene el valor de la cadena mediante una estrategia formateada específica.|
| [`get_width_of_value(self)`](/cells/python-net/es/aspose.cells/cell/get_width_of_value/#) | Obtiene el ancho del valor en unidades de píxeles.|
| [`get_height_of_value(self)`](/cells/python-net/es/aspose.cells/cell/get_height_of_value/#) | Obtiene la altura del valor en unidades de píxeles.|
| [`get_format_conditions(self)`](/cells/python-net/es/aspose.cells/cell/get_format_conditions/#) | Obtiene las condiciones de formato que se aplican a esta celda.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells/cell/get_formula/#bool-bool) | Obtenga la fórmula de esta celda.|
| [`get_precedents(self)`](/cells/python-net/es/aspose.cells/cell/get_precedents/#) | Obtiene todas las referencias que aparecen en la fórmula de esta celda.|
| [`get_dependents(self, is_all)`](/cells/python-net/es/aspose.cells/cell/get_dependents/#bool) | Obtenga todas las celdas cuya fórmula haga referencia a esta celda directamente.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/es/aspose.cells/cell/get_precedents_in_calculation/#) | Obtiene todos los precedentes (referencias a las celdas en el libro actual) utilizados por la fórmula de esta celda al calcularla.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation/#bool) | Obtiene todas las celdas cuyo resultado calculado depende de esta celda.|
| [`get_array_range(self)`](/cells/python-net/es/aspose.cells/cell/get_array_range/#) | Obtiene el rango de la matriz si la fórmula de la celda es una fórmula de matriz.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/es/aspose.cells/cell/remove_array_formula/#bool) | Eliminar la fórmula de matriz.|
| [`copy(self, cell)`](/cells/python-net/es/aspose.cells/cell/copy/#aspose.cells.cell) | Copia datos de una celda de origen.|
| [`characters(self, start_index, length)`](/cells/python-net/es/aspose.cells/cell/characters/#int-int) | Devuelve un objeto Caracteres que representa un rango de caracteres dentro del texto de la celda.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/es/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Reemplazar el texto de la celda con opciones.|
| [`insert_text(self, index, text)`](/cells/python-net/es/aspose.cells/cell/insert_text/#int-str) | Insertar algunos caracteres en la celda.<br/> Si la celda tiene un formato enriquecido, este método podría mantener el formato original.|
| [`is_rich_text(self)`](/cells/python-net/es/aspose.cells/cell/is_rich_text/#) |Indica si el valor de la cadena de esta celda es un texto con formato enriquecido.|
| [`set_characters(self, characters)`](/cells/python-net/es/aspose.cells/cell/set_characters/#list) | Establece el formato de texto enriquecido de la celda.|
| [`get_merged_range(self)`](/cells/python-net/es/aspose.cells/cell/get_merged_range/#) | Devuelve un objeto [`Range`](/cells/python-net/es/aspose.cells/range) que representa un rango fusionado.|
| [`get_html_string(self, html5)`](/cells/python-net/es/aspose.cells/cell/get_html_string/#bool) | Obtiene la cadena html que contiene datos y algunos formatos en esta celda.|
| [`to_json(self)`](/cells/python-net/es/aspose.cells/cell/to_json/#) | Convierte los datos de la estructura [`Cell`](/cells/python-net/es/aspose.cells/cell) en JSON.|
| [`equals(self, cell)`](/cells/python-net/es/aspose.cells/cell/equals/#aspose.cells.cell) | Comprueba si este objeto hace referencia a la misma celda que otro objeto de celda.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/es/aspose.cells/cell/get_conditional_formatting_result/#) | Obtenga el resultado del formato condicional.|
| [`get_validation(self)`](/cells/python-net/es/aspose.cells/cell/get_validation/#) | Obtiene la validación aplicada a esta celda.|
| [`get_validation_value(self)`](/cells/python-net/es/aspose.cells/cell/get_validation_value/#) | Obtiene el valor de validación que se aplicó a esta celda.|
| [`get_table(self)`](/cells/python-net/es/aspose.cells/cell/get_table/#) | Obtiene la tabla que contiene esta celda.|
| [`get_rich_value(self)`](/cells/python-net/es/aspose.cells/cell/get_rich_value/#) | Obtiene un rico valor de la celda.|



###  Ejemplo

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
