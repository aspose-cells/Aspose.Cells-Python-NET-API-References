---
title: ShapeCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 510
url: /es/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection clase
Representa todas las formas en una hoja de cálculo/gráfico.



El tipo ShapeCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.drawing/shapecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Agregue una forma al gráfico. Todas las unidades son 1/4000 del área del gráfico.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Agregue una forma al gráfico. Todas las unidades son 1/4000 del área del gráfico.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Añade una forma al gráfico. Todas las unidades son porcentajes del área del gráfico.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Agregue una forma al gráfico. Todas las unidades son 1/4000 del área del gráfico.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Añade una imagen a la colección.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Añade una imagen a la colección.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/get/#str) | Obtiene el objeto [`Shape`](/cells/python-net/es/aspose.cells.drawing/shape) por el nombre de la forma.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Agrega y copia una forma a la hoja de cálculo.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Agrega una casilla de verificación a la hoja de cálculo.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Agrega un cuadro de texto a la hoja de cálculo.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Agregue un objeto de ecuación a la hoja de trabajo.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Agrega un Spinner a la hoja de trabajo.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Agrega una barra de desplazamiento a la hoja de cálculo.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Agrega un botón de opción a la hoja de cálculo.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Agrega un ListBox a la hoja de cálculo.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Agrega un ComboBox a la hoja de cálculo.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Agrega un GroupBox a la hoja de cálculo.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Agrega un botón a la hoja de cálculo.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Agrega una etiqueta a la hoja de trabajo.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Agrega una etiqueta al gráfico.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Agrega un cuadro de texto al gráfico.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Inserta un objeto WordArt en el gráfico|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Inserta un objeto WordArt.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Agrega WordArt preestablecido desde Excel 2007.|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Agrega una forma de rectángulo a la hoja de cálculo.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Agrega un óvalo a la hoja de cálculo.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Agrega una forma de línea a la hoja de cálculo.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Agrega una forma flotante libre a la hoja de cálculo. Solo se aplica para formas de línea/imagen.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Agrega un ArcShape a la hoja de cálculo.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Agrega una forma a la hoja de cálculo.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Agrega una autoforma a la hoja de cálculo.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Agrega una autoforma al gráfico.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Crea un control Activex.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | Agrega imagen SVG.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | Agrega imagen SVG.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Añade una imagen vinculada.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Añade una imagen vinculada.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Añade una imagen al gráfico.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Agrega un OleObject.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Copiar todos los comentarios en el rango.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Copiar formas del rango al rango de destino.|
| [`delete_in_range(self, ca)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Eliminar formas del rango.Las formas de comentario no se eliminarán.|
| [`delete_shape(self, shape)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Eliminar una forma. Si la forma está en el grupo o es una forma de comentario, no se eliminará.|
| [`group(self, group_items)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/group/#list) | Agrupa las formas.|
| [`ungroup(self, group)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Desagrupa los elementos de forma.|
| [`remove_a_shape(self, shape)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | Agregue API for Python a través de .Net. ya que este API no es compatible|
| [`update_selected_value(self)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/update_selected_value/#) | Actualiza el valor seleccionado por el valor de la celda vinculada o el rango de la forma.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Agrega una forma libre a la hoja de cálculo.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Agrega una línea de firma a la hoja de cálculo.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get ShapeCollection
shapes = workbook.worksheets[0].shapes
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing`](..)
* clase [`Shape`](/cells/python-net/es/aspose.cells.drawing/shape)
