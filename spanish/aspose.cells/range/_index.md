---
title: Range clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1180
url: /es/aspose.cells/range/
is_root: false
---
##  Range clase
Encapsula el objeto que representa un rango de celdas dentro de una hoja de cálculo.



El tipo Range expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [current_region](/cells/python-net/es/aspose.cells/range/current_region) | Devuelve un objeto Range que representa la región actual.<br/> La región actual es un rango delimitado por cualquier combinación de filas y columnas en blanco.|
| [hyperlinks](/cells/python-net/es/aspose.cells/range/hyperlinks) | Obtiene todos los hipervínculos en el rango.|
| [row_count](/cells/python-net/es/aspose.cells/range/row_count) | Obtiene el recuento de filas en el rango.|
| [column_count](/cells/python-net/es/aspose.cells/range/column_count) | Obtiene el recuento de columnas en el rango.|
| [name](/cells/python-net/es/aspose.cells/range/name) | Obtiene o establece el nombre del rango.|
| [refers_to](/cells/python-net/es/aspose.cells/range/refers_to) | Obtiene el rango al que se refiere.|
| [address](/cells/python-net/es/aspose.cells/range/address) | Obtiene la dirección del rango.|
| [left](/cells/python-net/es/aspose.cells/range/left) | Obtiene la distancia, en puntos, desde el borde izquierdo de la columna A hasta el borde izquierdo del rango.|
| [top](/cells/python-net/es/aspose.cells/range/top) | Obtiene la distancia, en puntos, desde el borde superior de la fila 1 hasta el borde superior del rango.|
| [width](/cells/python-net/es/aspose.cells/range/width) | Obtiene el ancho de un rango en puntos.|
| [height](/cells/python-net/es/aspose.cells/range/height) | Obtiene el ancho de un rango en puntos.|
| [first_row](/cells/python-net/es/aspose.cells/range/first_row) | Obtiene el índice de la primera fila del rango.|
| [first_column](/cells/python-net/es/aspose.cells/range/first_column) | Obtiene el índice de la primera columna del rango.|
| [value](/cells/python-net/es/aspose.cells/range/value) | Obtiene y establece el valor del rango.|
| [column_width](/cells/python-net/es/aspose.cells/range/column_width) | Establece u obtiene el ancho de columna de este rango|
| [row_height](/cells/python-net/es/aspose.cells/range/row_height) | Establece u obtiene la altura de las filas en este rango|
| [entire_column](/cells/python-net/es/aspose.cells/range/entire_column) |Obtiene un objeto Range que representa la columna (o columnas) completa que contiene el rango especificado.|
| [entire_row](/cells/python-net/es/aspose.cells/range/entire_row) | Obtiene un objeto Range que representa la fila (o filas) completa que contiene el rango especificado.|
| [worksheet](/cells/python-net/es/aspose.cells/range/worksheet) | Obtiene el objeto [`Range.worksheet`](/cells/python-net/es/aspose.cells/range#worksheet) que contiene este rango.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/es/aspose.cells/range/auto_fill/#aspose.cells.range) | Rellene automáticamente el rango objetivo.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/es/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Rellene automáticamente el rango objetivo.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/es/aspose.cells/range/set_style/#aspose.cells.style-bool) | Aplicar el estilo de celda.|
| [`set_style(self, style)`](/cells/python-net/es/aspose.cells/range/set_style/#aspose.cells.style) | Establece el estilo del rango.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/es/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Establece los bordes del contorno alrededor de un rango de celdas con el mismo estilo y color de borde.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/es/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Establece los bordes del contorno alrededor de un rango de celdas con el mismo estilo y color de borde.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/es/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Establece límites de líneas alrededor de un rango de celdas.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/es/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Establece un borde de contorno alrededor de un rango de celdas.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/es/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Establece un borde de contorno alrededor de un rango de celdas.|
| [`copy(self, range, options)`](/cells/python-net/es/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Copiar el rango con opciones especiales de pegado.|
| [`copy(self, range)`](/cells/python-net/es/aspose.cells/range/copy/#aspose.cells.range) | Copia datos (incluidas fórmulas), formatos, objetos de dibujo, etc. de un rango de origen.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/es/aspose.cells/range/add_hyperlink/#str-str-str) | Agrega un hipervínculo a una celda específica o a un rango de celdas.|
| [`is_intersect(self, range)`](/cells/python-net/es/aspose.cells/range/is_intersect/#aspose.cells.range) | Indica si el rango es de intersección.|
| [`intersect(self, range)`](/cells/python-net/es/aspose.cells/range/intersect/#aspose.cells.range) | Devuelve un objeto [`Range`](/cells/python-net/es/aspose.cells/range) que representa la intersección rectangular de dos rangos.|
| [`union_rang(self, range)`](/cells/python-net/es/aspose.cells/range/union_rang/#aspose.cells.range) | Devuelve el resultado de la unión de dos rangos.|
| [`union_ranges(self, ranges)`](/cells/python-net/es/aspose.cells/range/union_ranges/#list) | Devuelve el resultado de la unión de dos rangos.|
| [`union(self, range)`](/cells/python-net/es/aspose.cells/range/union/#aspose.cells.range) | Devuelve la unión de dos rangos.|
| [`is_blank(self)`](/cells/python-net/es/aspose.cells/range/is_blank/#) | Indica si el rango contiene valores.|
| [`merge(self)`](/cells/python-net/es/aspose.cells/range/merge/#) |Combina un rango de celdas en una sola celda.|
| [`un_merge(self)`](/cells/python-net/es/aspose.cells/range/un_merge/#) | Desfusiona las celdas fusionadas de este rango.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/es/aspose.cells/range/put_value/#str-bool-bool) | Coloca un valor en el rango, si corresponde, el valor se convertirá a otro tipo de datos y se restablecerá el formato de número de la celda.|
| [`apply_style(self, style, flag)`](/cells/python-net/es/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Aplica formatos para toda una gama.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/es/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Situado dentro de los límites del rango.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/es/aspose.cells/range/move_to/#int-int) | Mueve el rango actual al rango de destino.|
| [`copy_data(self, range)`](/cells/python-net/es/aspose.cells/range/copy_data/#aspose.cells.range) | Copia datos de celdas (incluidas fórmulas) de un rango de origen.|
| [`copy_value(self, range)`](/cells/python-net/es/aspose.cells/range/copy_value/#aspose.cells.range) | Copia el valor de celda de un rango de origen.|
| [`copy_style(self, range)`](/cells/python-net/es/aspose.cells/range/copy_style/#aspose.cells.range) | Copia configuraciones de estilo desde un rango de origen.|
| [`transpose(self)`](/cells/python-net/es/aspose.cells/range/transpose/#) | Transponer (rotar) datos de filas a columnas o viceversa.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/es/aspose.cells/range/get/#int-int) | Agregar API for Python a través de .Net.ya que este [int, int] no es compatible|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/es/aspose.cells/range/get_cell_or_null/#int-int) | Obtiene el objeto [`Cell`](/cells/python-net/es/aspose.cells/cell) o nulo en este rango.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/es/aspose.cells/range/get_offset/#int-int) | Obtiene el rango [`Range`](/cells/python-net/es/aspose.cells/range) por desplazamiento.|
| [`to_image(self, options)`](/cells/python-net/es/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Convierte el rango en imagen.|
| [`to_json(self, options)`](/cells/python-net/es/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Convierte el rango al valor JSON.|
| [`to_html(self, save_options)`](/cells/python-net/es/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Convierte el rango a html.|
| [`clear(self)`](/cells/python-net/es/aspose.cells/range/clear/#) | Borra este rango.|
| [`clear_contents(self)`](/cells/python-net/es/aspose.cells/range/clear_contents/#) | Borra el contenido de este rango.|
| [`clear_formats(self)`](/cells/python-net/es/aspose.cells/range/clear_formats/#) | Borra los formatos de este rango.|
| [`clear_comments(self)`](/cells/python-net/es/aspose.cells/range/clear_comments/#) | Borra los comentarios de este rango.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/es/aspose.cells/range/clear_hyperlinks/#bool) | Sólo elimina hipervínculos.|



###  Observaciones

La clase Range denota una región de la hoja de cálculo de Excel.
Con esto, puedes formatear y establecer el valor del rango.
Y también puedes simplemente copiar un rango de Excel.

###  Ejemplo

El siguiente ejemplo muestra cómo crear un rango y establecer el valor del rango de Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
