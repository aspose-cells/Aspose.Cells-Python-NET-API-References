---
title: Cell clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells/cell/
is_root: false
---
##  Cell clase
Encapsula el objeto que representa una única celda del libro.



El tipo Cell expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [worksheet](/cells/python-net/es/aspose.cells/cell/worksheet) |Obtiene la hoja de trabajo principal.|
| [date_time_value](/cells/python-net/es/aspose.cells/cell/date_time_value) | Obtiene el valor de DateTime contenido en la celda.|
| [row](/cells/python-net/es/aspose.cells/cell/row) | Obtiene el número de fila (basado en cero) de la celda.|
| [column](/cells/python-net/es/aspose.cells/cell/column) | Obtiene el número de columna (basado en cero) de la celda.|
| [is_formula](/cells/python-net/es/aspose.cells/cell/is_formula) | Representa si la celda especificada contiene una fórmula.|
| [type](/cells/python-net/es/aspose.cells/cell/type) | Representa el tipo de valor de celda.|
| [name](/cells/python-net/es/aspose.cells/cell/name) | Obtiene el nombre de la celda.|
| [is_error_value](/cells/python-net/es/aspose.cells/cell/is_error_value) | Comprueba si el valor de esta celda es un error.|
| [is_numeric_value](/cells/python-net/es/aspose.cells/cell/is_numeric_value) | Indica si el valor de esta celda es numérico (int, double y datetime)|
| [string_value](/cells/python-net/es/aspose.cells/cell/string_value) | Obtiene el valor de cadena contenido en la celda. Si el tipo de esta celda es una cadena, devuelve el valor de la cadena.<br/>Para otros tipos de celda, se devolverá el valor de cadena formateado (formateado con el estilo especificado de esta celda).<br/>El valor de la celda formateada es el mismo que puede obtener de Excel al copiar una celda como texto (como<br/> copiar celda al editor de texto o exportar a csv).|
| [string_value_without_format](/cells/python-net/es/aspose.cells/cell/string_value_without_format) | Obtiene el valor de la celda como una cadena sin ningún formato.|
| [number_category_type](/cells/python-net/es/aspose.cells/cell/number_category_type) | Representa el tipo de categoría del formato de número de esta celda.|
| [display_string_value](/cells/python-net/es/aspose.cells/cell/display_string_value) | Obtiene el valor de cadena formateado de esta celda por el estilo de visualización de la celda.|
| [int_value](/cells/python-net/es/aspose.cells/cell/int_value) | Obtiene el valor entero contenido en la celda.|
| [double_value](/cells/python-net/es/aspose.cells/cell/double_value) | Obtiene el valor doble contenido en la celda.|
| [float_value](/cells/python-net/es/aspose.cells/cell/float_value) | Obtiene el valor flotante contenido en la celda.|
| [bool_value](/cells/python-net/es/aspose.cells/cell/bool_value) |Obtiene el valor booleano contenido en la celda.|
| [has_custom_style](/cells/python-net/es/aspose.cells/cell/has_custom_style) | Indica si esta celda tiene configuraciones de estilo personalizadas (diferentes a las heredadas por defecto)<br/> de la fila, columna o libro correspondiente).|
| [shared_style_index](/cells/python-net/es/aspose.cells/cell/shared_style_index) | Obtiene el índice de estilo compartido de la celda en el grupo de estilos.|
| [formula](/cells/python-net/es/aspose.cells/cell/formula) | Obtiene o establece una fórmula de [`Cell`](/cells/python-net/es/aspose.cells/cell).|
| [formula_local](/cells/python-net/es/aspose.cells/cell/formula_local) | Obtenga la fórmula con formato local de la celda.|
| [r1c1_formula](/cells/python-net/es/aspose.cells/cell/r1c1_formula) | Obtiene o establece una fórmula R1C1 de [`Cell`](/cells/python-net/es/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/es/aspose.cells/cell/contains_external_link) | Indica si esta celda contiene un enlace externo.<br/> Solo se aplica cuando la celda es una celda de fórmula.|
| [is_array_header](/cells/python-net/es/aspose.cells/cell/is_array_header) | Indica que la fórmula de la celda es una fórmula matricial.<br/> y es la primera celda de la matriz.|
| [is_dynamic_array_formula](/cells/python-net/es/aspose.cells/cell/is_dynamic_array_formula) | Indica si la fórmula de la celda es una fórmula de matriz dinámica (verdadero) o una fórmula de matriz heredada (falso).|
| [is_array_formula](/cells/python-net/es/aspose.cells/cell/is_array_formula) | Indica si la fórmula de la celda es una fórmula matricial.|
| [is_in_array](/cells/python-net/es/aspose.cells/cell/is_in_array) | Indica si la fórmula de la celda es una fórmula matricial.|
| [is_shared_formula](/cells/python-net/es/aspose.cells/cell/is_shared_formula) | Indica si la fórmula de la celda es parte de una fórmula compartida.|
| [is_table_formula](/cells/python-net/es/aspose.cells/cell/is_table_formula) | Indica si esta celda es parte de la fórmula de la tabla.|
| [is_in_table](/cells/python-net/es/aspose.cells/cell/is_in_table) | Indica si esta celda es parte de la fórmula de la tabla.|
| [value](/cells/python-net/es/aspose.cells/cell/value) | Obtiene/establece el valor contenido en esta celda.|
| [is_style_set](/cells/python-net/es/aspose.cells/cell/is_style_set) |Indica si el estilo de la celda está establecido. Si devuelve falso, significa que esta celda tiene un formato de celda predeterminado.|
| [is_merged](/cells/python-net/es/aspose.cells/cell/is_merged) | Comprueba si una celda es parte de un rango combinado o no.|
| [comment](/cells/python-net/es/aspose.cells/cell/comment) | Obtiene el comentario de esta celda.|
| [html_string](/cells/python-net/es/aspose.cells/cell/html_string) | Obtiene y establece la cadena html que contiene datos y algunos formatos en esta celda.|
| [embedded_image](/cells/python-net/es/aspose.cells/cell/embedded_image) | Obtiene y establece la imagen incrustada en la celda.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#bool) | Pone un valor booleano en la celda.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#int) | Pone un valor entero en la celda.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#float) | Pone un valor doble en la celda.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#str-bool-bool) | Coloca un valor en la celda; si corresponde, el valor se convertirá a otro tipo de datos y se restablecerá el formato del número de la celda.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#str-bool) | Coloca un valor de cadena en la celda y convierte el valor a otro tipo de datos, si corresponde.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#str) | Pone un valor de cadena en la celda.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#DateTime) | Pone un valor DateTime en la celda.|
| [put_value](/cells/python-net/es/aspose.cells/cell/put_value/#any) | Pone un valor de objeto en la celda.|
| [get_display_style](/cells/python-net/es/aspose.cells/cell/get_display_style/#) | Obtiene el estilo de visualización de la celda.<br/>Si esta celda también se ve afectada por otras configuraciones como formato condicional, objetos de lista, etc.,<br/>entonces el estilo de visualización puede ser diferente al de cell.GetStyle().|
| [get_display_style](/cells/python-net/es/aspose.cells/cell/get_display_style/#bool) | Obtiene el estilo de visualización de la celda.<br/> Si la celda tiene formato condicional, el estilo de visualización no es el mismo que el de cell.GetStyle().|
| [get_style](/cells/python-net/es/aspose.cells/cell/get_style/#) | Obtiene el estilo de celda.|
| [get_style](/cells/python-net/es/aspose.cells/cell/get_style/#bool) | Si checkBorders es verdadero, verifique si los bordes de otras celdas afectarán el estilo de esta celda.|
| [set_style](/cells/python-net/es/aspose.cells/cell/set_style/#aspose.cells.Style) | Establece el estilo de celda.|
| [set_style](/cells/python-net/es/aspose.cells/cell/set_style/#aspose.cells.Style-bool) | Aplique la propiedad modificada de estilo a la celda.|
| [set_style](/cells/python-net/es/aspose.cells/cell/set_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Aplicar el estilo de celda basado en banderas.|
| [set_formula](/cells/python-net/es/aspose.cells/cell/set_formula/#str-any) | Establezca la fórmula y el valor (resultado calculado) de la fórmula.|
| [set_formula](/cells/python-net/es/aspose.cells/cell/set_formula/#str-bool-bool-any) | Establezca la fórmula y el valor de la fórmula.|
| [set_formula](/cells/python-net/es/aspose.cells/cell/set_formula/#str-aspose.cells.FormulaParseOptions-any) | Establezca la fórmula y el valor (resultado calculado) de la fórmula.|
| [set_array_formula](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Establece una fórmula matricial para un rango de celdas.|
| [set_array_formula](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int) | Establece una fórmula matricial (fórmula matricial heredada ingresada mediante CTRL+MAYÚS+ENTRAR en ms excel) en un rango de celdas.|
| [set_array_formula](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Establece una fórmula matricial para un rango de celdas.|
| [set_array_formula](/cells/python-net/es/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Establece una fórmula matricial para un rango de celdas.|
| [set_shared_formula](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Establece una fórmula para un rango de celdas.|
| [set_shared_formula](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int) | Establece fórmulas compartidas para un rango de celdas.|
| [set_shared_formula](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Establece fórmulas compartidas para un rango de celdas.|
| [set_shared_formula](/cells/python-net/es/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Establece fórmulas compartidas para un rango de celdas.|
| [get_leafs](/cells/python-net/es/aspose.cells/cell/get_leafs/#) | Obtenga todas las celdas que hacen referencia a esta celda directamente y deben actualizarse cuando se modifica esta celda.|
| [get_leafs](/cells/python-net/es/aspose.cells/cell/get_leafs/#bool) | Obtenga todas las celdas que se actualizarán cuando se modifique esta celda.|
| [set_dynamic_array_formula](/cells/python-net/es/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-bool) |Establece una fórmula de matriz dinámica y, si es posible, hace que la fórmula se extienda a las celdas vecinas.|
| [set_dynamic_array_formula](/cells/python-net/es/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool) |Establece una fórmula de matriz dinámica y, si es posible, hace que la fórmula se extienda a las celdas vecinas.|
| [set_dynamic_array_formula](/cells/python-net/es/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions) |Establece una fórmula de matriz dinámica y, si es posible, hace que la fórmula se extienda a las celdas vecinas.|
| [set_table_formula](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Cree una tabla de datos de dos variables para un rango dado a partir de esta celda.|
| [set_table_formula](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Cree una tabla de datos de una variable para un rango determinado a partir de esta celda.|
| [set_table_formula](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Cree una tabla de datos de dos variables para un rango dado a partir de esta celda.|
| [set_table_formula](/cells/python-net/es/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Cree una tabla de datos de una variable para un rango determinado a partir de esta celda.|
| [get_characters](/cells/python-net/es/aspose.cells/cell/get_characters/#) | Devuelve todos los objetos de personajes.<br/> que representa un rango de caracteres dentro del texto de la celda.|
| [get_characters](/cells/python-net/es/aspose.cells/cell/get_characters/#bool) | Devuelve todos los objetos de personajes.<br/> que representa un rango de caracteres dentro del texto de la celda.|
| [calculate](/cells/python-net/es/aspose.cells/cell/calculate/#aspose.cells.CalculationOptions) | Calcula la fórmula de la celda.|
| [get_string_value](/cells/python-net/es/aspose.cells/cell/get_string_value/#aspose.cells.CellValueFormatStrategy) | Obtiene el valor de la cadena mediante una estrategia formateada específica.|
| [get_width_of_value](/cells/python-net/es/aspose.cells/cell/get_width_of_value/#) | Obtiene el ancho del valor en unidades de píxeles.|
| [get_height_of_value](/cells/python-net/es/aspose.cells/cell/get_height_of_value/#) | Obtiene la altura del valor en unidades de píxeles.|
| [get_format_conditions](/cells/python-net/es/aspose.cells/cell/get_format_conditions/#) | Obtiene las condiciones de formato que se aplican a esta celda.|
| [get_formula](/cells/python-net/es/aspose.cells/cell/get_formula/#bool-bool) | Obtén la fórmula de esta celda.|
| [get_precedents](/cells/python-net/es/aspose.cells/cell/get_precedents/#) | Obtiene todas las referencias que aparecen en la fórmula de esta celda.|
| [get_dependents](/cells/python-net/es/aspose.cells/cell/get_dependents/#bool) | Obtenga todas las celdas cuya fórmula haga referencia directamente a esta celda.|
| [get_precedents_in_calculation](/cells/python-net/es/aspose.cells/cell/get_precedents_in_calculation/#) | Obtiene todos los precedentes (referencias a celdas del libro actual) utilizados por la fórmula de esta celda mientras la calcula.|
| [get_dependents_in_calculation](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation/#bool) | Obtiene todas las celdas cuyo resultado calculado depende de esta celda.|
| [get_array_range](/cells/python-net/es/aspose.cells/cell/get_array_range/#) |Obtiene el rango de la matriz si la fórmula de la celda es una fórmula matricial.|
| [remove_array_formula](/cells/python-net/es/aspose.cells/cell/remove_array_formula/#bool) | Eliminar fórmula matricial.|
| [copy](/cells/python-net/es/aspose.cells/cell/copy/#aspose.cells.Cell) | Copia datos de una celda de origen.|
| [characters](/cells/python-net/es/aspose.cells/cell/characters/#int-int) | Devuelve un objeto Characters que representa un rango de caracteres dentro del texto de la celda.|
| [replace](/cells/python-net/es/aspose.cells/cell/replace/#str-str-aspose.cells.ReplaceOptions) | Reemplace el texto de la celda con opciones.|
| [insert_text](/cells/python-net/es/aspose.cells/cell/insert_text/#int-str) | Inserta algunos caracteres en la celda.<br/> Si la celda tiene formato enriquecido, este método podría mantener el formato original.|
| [is_rich_text](/cells/python-net/es/aspose.cells/cell/is_rich_text/#) | Indica si el valor de cadena de esta celda es un texto con formato enriquecido.|
| [set_characters](/cells/python-net/es/aspose.cells/cell/set_characters/#list) | Establece el formato de texto enriquecido de la celda.|
| [get_merged_range](/cells/python-net/es/aspose.cells/cell/get_merged_range/#) | Devuelve un objeto [`Range`](/cells/python-net/es/aspose.cells/range) que representa un rango combinado.|
| [get_html_string](/cells/python-net/es/aspose.cells/cell/get_html_string/#bool) | Obtiene la cadena HTML que contiene datos y algunos formatos en esta celda.|
| [to_json](/cells/python-net/es/aspose.cells/cell/to_json/#) | Convierta [`Cell`](/cells/python-net/es/aspose.cells/cell) en JSON datos de estructura.|
| [equals](/cells/python-net/es/aspose.cells/cell/equals/#aspose.cells.Cell) | Comprueba si este objeto hace referencia a la misma celda con otro objeto de celda.|
| [get_conditional_formatting_result](/cells/python-net/es/aspose.cells/cell/get_conditional_formatting_result/#) | Obtenga el resultado del formato condicional.|
| [get_validation](/cells/python-net/es/aspose.cells/cell/get_validation/#) | Obtiene la validación aplicada a esta celda.|
| [get_validation_value](/cells/python-net/es/aspose.cells/cell/get_validation_value/#) | Obtiene el valor de validación que se aplicó a esta celda.|
| [get_table](/cells/python-net/es/aspose.cells/cell/get_table/#) |Obtiene la tabla que contiene esta celda.|



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
