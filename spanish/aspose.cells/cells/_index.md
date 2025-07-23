---
title: Cells clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 160
url: /es/aspose.cells/cells/
is_root: false
---
##  Cells clase
Encapsula una colección de objetos relevantes de la celda, como [`Cell`](/cells/python-net/es/aspose.cells/cell), [`Row`](/cells/python-net/es/aspose.cells/row), ...etc.



El tipo Cells expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [ods_cell_fields](/cells/python-net/es/aspose.cells/cells/ods_cell_fields) | Obtiene la lista de campos de ods.|
| [count](/cells/python-net/es/aspose.cells/cells/count) | Obtiene el recuento total de Cell objetos instanciados.|
| [count_large](/cells/python-net/es/aspose.cells/cells/count_large) | Obtiene el recuento total de Cell objetos instanciados.|
| [rows](/cells/python-net/es/aspose.cells/cells/rows) | Obtiene la colección de [`Row`](/cells/python-net/es/aspose.cells/row) objetos que representan las filas individuales en esta hoja de cálculo.|
| [merged_cells](/cells/python-net/es/aspose.cells/cells/merged_cells) | Obtiene la colección de celdas fusionadas.|
| [multi_thread_reading](/cells/python-net/es/aspose.cells/cells/multi_thread_reading) | Obtiene o establece si el modelo de datos de celdas debe admitir la lectura de múltiples subprocesos.<br/> El valor predeterminado de esta propiedad es falso.|
| [memory_setting](/cells/python-net/es/aspose.cells/cells/memory_setting) | Obtiene o establece la opción de uso de memoria para estas celdas.|
| [style](/cells/python-net/es/aspose.cells/cells/style) | Obtiene y establece el estilo predeterminado de la hoja de cálculo.|
| [is_default_column_hidden](/cells/python-net/es/aspose.cells/cells/is_default_column_hidden) |  |
| [standard_width_inch](/cells/python-net/es/aspose.cells/cells/standard_width_inch) | Obtiene o establece el ancho de columna predeterminado en la hoja de cálculo, en unidades de pulgadas.|
| [standard_width_pixels](/cells/python-net/es/aspose.cells/cells/standard_width_pixels) |Obtiene o establece el ancho de columna predeterminado en la hoja de cálculo, en unidades de píxeles.|
| [standard_width](/cells/python-net/es/aspose.cells/cells/standard_width) | Obtiene o establece el ancho de columna predeterminado en la hoja de cálculo, en unidades de caracteres.|
| [standard_height](/cells/python-net/es/aspose.cells/cells/standard_height) | Obtiene o establece la altura de fila predeterminada en esta hoja de cálculo, en unidades de puntos.|
| [standard_height_pixels](/cells/python-net/es/aspose.cells/cells/standard_height_pixels) | Obtiene o establece la altura de fila predeterminada en esta hoja de cálculo, en unidades de píxeles.|
| [standard_height_inch](/cells/python-net/es/aspose.cells/cells/standard_height_inch) | Obtiene o establece la altura de fila predeterminada en esta hoja de cálculo, en unidades de pulgadas.|
| [preserve_string](/cells/python-net/es/aspose.cells/cells/preserve_string) | Obtiene o establece un valor que indica si todos los valores de la hoja de cálculo se conservan como cadenas.<br/> El valor predeterminado es falso.|
| [min_row](/cells/python-net/es/aspose.cells/cells/min_row) | Índice de fila mínimo de la celda que contiene datos o estilo.|
| [max_row](/cells/python-net/es/aspose.cells/cells/max_row) | Índice de fila máximo de la celda que contiene datos o estilo.|
| [min_column](/cells/python-net/es/aspose.cells/cells/min_column) | Índice mínimo de columna de aquellas celdas que han sido instanciadas en la colección (no incluye la columna<br/> donde el estilo está definido para toda la columna pero no se ha creado ninguna celda en ella).|
| [max_column](/cells/python-net/es/aspose.cells/cells/max_column) | Índice de columna máximo de aquellas celdas que se han instanciado en la colección (no incluye la columna<br/> donde el estilo está definido para toda la columna pero no se ha creado ninguna celda en ella).|
| [min_data_row](/cells/python-net/es/aspose.cells/cells/min_data_row) |Índice de fila mínimo de la celda que contiene datos.|
| [max_data_row](/cells/python-net/es/aspose.cells/cells/max_data_row) | Índice de fila máximo de la celda que contiene datos.|
| [min_data_column](/cells/python-net/es/aspose.cells/cells/min_data_column) | Índice mínimo de columna de la celda que contiene datos.|
| [max_data_column](/cells/python-net/es/aspose.cells/cells/max_data_column) | Índice máximo de columna de la celda que contiene datos.|
| [is_default_row_height_matched](/cells/python-net/es/aspose.cells/cells/is_default_row_height_matched) | Indica que la altura de fila y la altura de fuente predeterminada coinciden|
| [is_default_row_hidden](/cells/python-net/es/aspose.cells/cells/is_default_row_hidden) | Indica si la fila está oculta de forma predeterminada.|
| [columns](/cells/python-net/es/aspose.cells/cells/columns) | Obtiene la colección de [`Column`](/cells/python-net/es/aspose.cells/column) objetos que representan las columnas individuales en esta hoja de cálculo.|
| [ranges](/cells/python-net/es/aspose.cells/cells/ranges) | Obtiene la colección de [`Range`](/cells/python-net/es/aspose.cells/range) objetos creados en tiempo de ejecución.|
| [last_cell](/cells/python-net/es/aspose.cells/cells/last_cell) | Obtiene la última celda de esta hoja de cálculo.|
| [max_display_range](/cells/python-net/es/aspose.cells/cells/max_display_range) | Obtiene el rango máximo que incluye datos, celdas fusionadas y formas.|
| [first_cell](/cells/python-net/es/aspose.cells/cells/first_cell) | Obtiene la primera celda de esta hoja de cálculo.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`create_range(self, upper_left_cell, lower_right_cell)`](/cells/python-net/es/aspose.cells/cells/create_range/#str-str) | Crea un objeto [`Range`](/cells/python-net/es/aspose.cells/range) a partir de un rango de celdas.|
| [`create_range(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/es/aspose.cells/cells/create_range/#int-int-int-int) | Crea un objeto [`Range`](/cells/python-net/es/aspose.cells/range) a partir de un rango de celdas.|
| [`create_range(self, address)`](/cells/python-net/es/aspose.cells/cells/create_range/#str) | Crea un objeto [`Range`](/cells/python-net/es/aspose.cells/range) a partir de una dirección del rango.|
| [`create_range(self, first_index, number, is_vertical)`](/cells/python-net/es/aspose.cells/cells/create_range/#int-int-bool) | Crea un objeto [`Range`](/cells/python-net/es/aspose.cells/range) a partir de filas de celdas o columnas de celdas.|
| [`get(self, row, column)`](/cells/python-net/es/aspose.cells/cells/get/#int-int) | Agregue API for Python a través de .Net.ya que esto [int fila, int columna] no es compatible|
| [`get(self, cell_name)`](/cells/python-net/es/aspose.cells/cells/get/#str) |Agregue API for Python a través de .Net.ya que esta [cadena cellName] no es compatible|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical)`](/cells/python-net/es/aspose.cells/cells/import_object_array/#list-int-int-bool) | Importa una matriz de datos a una hoja de cálculo.|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical, skip)`](/cells/python-net/es/aspose.cells/cells/import_object_array/#list-int-int-bool-int) | Importa una matriz de datos a una hoja de cálculo.|
| [`import_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/es/aspose.cells/cells/import_array/#list-int-int-bool) | Importa una matriz de cadenas a una hoja de cálculo.|
| [`import_array(self, int_array, first_row, first_column, is_vertical)`](/cells/python-net/es/aspose.cells/cells/import_array/#list-int-int-bool) | Importa una matriz de números enteros a una hoja de cálculo.|
| [`import_array(self, double_array, first_row, first_column, is_vertical)`](/cells/python-net/es/aspose.cells/cells/import_array/#list-int-int-bool) | Importa una matriz de dobles a una hoja de cálculo.|
| [`import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/es/aspose.cells/cells/import_csv/#str-str-bool-int-int) | Importar un archivo CSV a las celdas.|
| [`import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/es/aspose.cells/cells/import_csv/#io.rawiobase-str-bool-int-int) | Importar un archivo CSV a las celdas.|
| [`import_csv(self, file_name, options, first_row, first_column)`](/cells/python-net/es/aspose.cells/cells/import_csv/#str-aspose.cells.txtloadoptions-int-int) | Importar un archivo CSV a las celdas.|
| [`import_csv(self, stream, options, first_row, first_column)`](/cells/python-net/es/aspose.cells/cells/import_csv/#io.rawiobase-aspose.cells.txtloadoptions-int-int) | Importar un archivo CSV a las celdas.|
| [`merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/es/aspose.cells/cells/merge/#int-int-int-int) | Fusiona un rango específico de celdas en una sola celda.|
| [`merge(self, first_row, first_column, total_rows, total_columns, merge_conflict)`](/cells/python-net/es/aspose.cells/cells/merge/#int-int-int-int-bool) | Fusiona un rango específico de celdas en una sola celda.|
| [`merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)`](/cells/python-net/es/aspose.cells/cells/merge/#int-int-int-int-bool-bool) | Fusiona un rango específico de celdas en una sola celda.|
| [`get_row_height(self, row, is_original, unit_type)`](/cells/python-net/es/aspose.cells/cells/get_row_height/#int-bool-aspose.cells.cellsunittype) | Obtiene la altura de la fila.|
| [`get_row_height(self, row)`](/cells/python-net/es/aspose.cells/cells/get_row_height/#int) | Obtiene la altura de una fila especificada, en unidades de puntos.|
| [`get_column_width(self, column, is_original, unit_type)`](/cells/python-net/es/aspose.cells/cells/get_column_width/#int-bool-aspose.cells.cellsunittype) | Obtiene el ancho de la columna.|
| [`get_column_width(self, column)`](/cells/python-net/es/aspose.cells/cells/get_column_width/#int) | Obtiene el ancho (en unidad de caracteres) de la columna especificada en la vista normal|
| [`get_column_width_pixel(self, column)`](/cells/python-net/es/aspose.cells/cells/get_column_width_pixel/#int) | Obtiene el ancho de la columna especificada en la vista normal, en unidades de píxeles.|
| [`get_column_width_pixel(self, column, original)`](/cells/python-net/es/aspose.cells/cells/get_column_width_pixel/#int-bool) | Obtiene el ancho de la columna especificada en la vista normal, en unidades de píxeles.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number, paste_options)`](/cells/python-net/es/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-aspose.cells.pasteoptions) | Copia datos y formatos de una columna completa.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number)`](/cells/python-net/es/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int) | Copia datos y formatos de una columna completa.|
| [`copy_columns(self, source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)`](/cells/python-net/es/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-int) | Copia datos y formatos de todas las columnas.|
| [`copy_rows(self, source_cells, source_row_index, destination_row_index, row_number)`](/cells/python-net/es/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int) | Copia datos y formatos de algunas filas enteras.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options)`](/cells/python-net/es/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions) | Copia datos y formatos de algunas filas enteras.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)`](/cells/python-net/es/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions-aspose.cells.pasteoptions) | Copia datos y formatos de algunas filas enteras.|
| [`group_columns(self, first_index, last_index)`](/cells/python-net/es/aspose.cells/cells/group_columns/#int-int) | Agrupa columnas.|
| [`group_columns(self, first_index, last_index, is_hidden)`](/cells/python-net/es/aspose.cells/cells/group_columns/#int-int-bool) | Agrupa columnas.|
| [`ungroup_rows(self, first_index, last_index, is_all)`](/cells/python-net/es/aspose.cells/cells/ungroup_rows/#int-int-bool) | Desagrupa filas.|
| [`ungroup_rows(self, first_index, last_index)`](/cells/python-net/es/aspose.cells/cells/ungroup_rows/#int-int) | Desagrupa filas.|
| [`group_rows(self, first_index, last_index, is_hidden)`](/cells/python-net/es/aspose.cells/cells/group_rows/#int-int-bool) | Agrupa filas.|
| [`group_rows(self, first_index, last_index)`](/cells/python-net/es/aspose.cells/cells/group_rows/#int-int) | Agrupa filas.|
| [`delete_column(self, column_index, update_reference)`](/cells/python-net/es/aspose.cells/cells/delete_column/#int-bool) | Elimina una columna.|
| [`delete_column(self, column_index)`](/cells/python-net/es/aspose.cells/cells/delete_column/#int) | Elimina una columna.|
| [`delete_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/es/aspose.cells/cells/delete_columns/#int-int-bool) | Elimina varias columnas.|
| [`delete_columns(self, column_index, total_columns, options)`](/cells/python-net/es/aspose.cells/cells/delete_columns/#int-int-aspose.cells.deleteoptions) | Elimina varias columnas.|
| [`delete_row(self, row_index)`](/cells/python-net/es/aspose.cells/cells/delete_row/#int) | Elimina una fila.|
| [`delete_row(self, row_index, update_reference)`](/cells/python-net/es/aspose.cells/cells/delete_row/#int-bool) | Elimina una fila.|
| [`delete_rows(self, row_index, total_rows)`](/cells/python-net/es/aspose.cells/cells/delete_rows/#int-int) |Elimina varias filas.|
| [`delete_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/es/aspose.cells/cells/delete_rows/#int-int-bool) | Elimina varias filas en la hoja de cálculo.|
| [`delete_rows(self, row_index, total_rows, options)`](/cells/python-net/es/aspose.cells/cells/delete_rows/#int-int-aspose.cells.deleteoptions) | Elimina varias filas en la hoja de cálculo.|
| [`delete_blank_columns(self)`](/cells/python-net/es/aspose.cells/cells/delete_blank_columns/#) | Eliminar todas las columnas en blanco que no contengan datos.|
| [`delete_blank_columns(self, options)`](/cells/python-net/es/aspose.cells/cells/delete_blank_columns/#aspose.cells.deleteoptions) | Eliminar todas las columnas en blanco que no contengan datos.|
| [`delete_blank_rows(self)`](/cells/python-net/es/aspose.cells/cells/delete_blank_rows/#) | Elimina todas las filas en blanco que no contengan datos ni ningún otro objeto.|
| [`delete_blank_rows(self, options)`](/cells/python-net/es/aspose.cells/cells/delete_blank_rows/#aspose.cells.deleteoptions) | Elimine todas las filas en blanco que no contengan datos o algunos objetos especiales, como comentarios visibles o tablas dinámicas.|
| [`insert_columns(self, column_index, total_columns)`](/cells/python-net/es/aspose.cells/cells/insert_columns/#int-int) | Inserta algunas columnas en la hoja de cálculo.|
| [`insert_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/es/aspose.cells/cells/insert_columns/#int-int-bool) | Inserta algunas columnas en la hoja de cálculo.|
| [`insert_columns(self, column_index, total_columns, options)`](/cells/python-net/es/aspose.cells/cells/insert_columns/#int-int-aspose.cells.insertoptions) | Inserta algunas columnas en la hoja de cálculo.|
| [`insert_column(self, column_index, update_reference)`](/cells/python-net/es/aspose.cells/cells/insert_column/#int-bool) | Inserta una nueva columna en la hoja de cálculo.|
| [`insert_column(self, column_index)`](/cells/python-net/es/aspose.cells/cells/insert_column/#int) | Inserta una nueva columna en la hoja de cálculo.|
| [`insert_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/es/aspose.cells/cells/insert_rows/#int-int-bool) | Inserta varias filas en la hoja de cálculo.|
| [`insert_rows(self, row_index, total_rows, options)`](/cells/python-net/es/aspose.cells/cells/insert_rows/#int-int-aspose.cells.insertoptions) | Inserta varias filas en la hoja de cálculo.|
| [`insert_rows(self, row_index, total_rows)`](/cells/python-net/es/aspose.cells/cells/insert_rows/#int-int) | Inserta varias filas en la hoja de cálculo.|
| [`clear_range(self, range)`](/cells/python-net/es/aspose.cells/cells/clear_range/#aspose.cells.cellarea) | Borra el contenido y el formato de un rango.|
| [`clear_range(self, start_row, start_column, end_row, end_column)`](/cells/python-net/es/aspose.cells/cells/clear_range/#int-int-int-int) | Borra el contenido y el formato de un rango.|
| [`clear_contents(self, range)`](/cells/python-net/es/aspose.cells/cells/clear_contents/#aspose.cells.cellarea) | Borra el contenido de un rango.|
| [`clear_contents(self, start_row, start_column, end_row, end_column)`](/cells/python-net/es/aspose.cells/cells/clear_contents/#int-int-int-int) | Borra el contenido de un rango.|
| [`clear_formats(self, range)`](/cells/python-net/es/aspose.cells/cells/clear_formats/#aspose.cells.cellarea) | Borra el formato de un rango.|
| [`clear_formats(self, start_row, start_column, end_row, end_column)`](/cells/python-net/es/aspose.cells/cells/clear_formats/#int-int-int-int) | Borra el formato de un rango.|
| [`find(self, what, previous_cell)`](/cells/python-net/es/aspose.cells/cells/find/#any-aspose.cells.cell) | Encuentra la celda que contiene el objeto de entrada.|
| [`find(self, what, previous_cell, find_options)`](/cells/python-net/es/aspose.cells/cells/find/#any-aspose.cells.cell-aspose.cells.findoptions) | Encuentra la celda que contiene el objeto de entrada.|
| [`end_cell_in_row(self, row_index)`](/cells/python-net/es/aspose.cells/cells/end_cell_in_row/#int) | Obtiene la última celda de esta fila.|
| [`end_cell_in_row(self, start_row, end_row, start_column, end_column)`](/cells/python-net/es/aspose.cells/cells/end_cell_in_row/#int-int-int-int) | Obtiene la última celda con el índice de fila máximo en este rango.|
| [`end_cell_in_column(self, column_index)`](/cells/python-net/es/aspose.cells/cells/end_cell_in_column/#int) | Obtiene la última celda de esta columna.|
| [`end_cell_in_column(self, start_row, end_row, start_column, end_column)`](/cells/python-net/es/aspose.cells/cells/end_cell_in_column/#int-int-int-int) | Obtiene la última celda con el índice de columna máximo en este rango.|
| [`insert_range(self, area, shift_number, shift_type, update_reference)`](/cells/python-net/es/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype-bool) | Inserta un rango de celdas y desplaza las celdas según la opción de desplazamiento.|
| [`insert_range(self, area, shift_type)`](/cells/python-net/es/aspose.cells/cells/insert_range/#aspose.cells.cellarea-aspose.cells.shifttype) | Inserta un rango de celdas y desplaza las celdas según la opción de desplazamiento.|
| [`insert_range(self, area, shift_number, shift_type)`](/cells/python-net/es/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype) | Inserta un rango de celdas y desplaza las celdas según la opción de desplazamiento.|
| [`subtotal(self, ca, group_by, function, total_list)`](/cells/python-net/es/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list) | Crea subtotales para el rango.|
| [`subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data)`](/cells/python-net/es/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list-bool-bool-bool) | Crea subtotales para el rango.|
| [`remove_duplicates(self)`](/cells/python-net/es/aspose.cells/cells/remove_duplicates/#) |Elimina filas duplicadas en la hoja.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column)`](/cells/python-net/es/aspose.cells/cells/remove_duplicates/#int-int-int-int) | Elimina valores duplicados en el rango.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets)`](/cells/python-net/es/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) | Elimina datos duplicados del rango.|
| [`get_cell_display_style(self, row, column)`](/cells/python-net/es/aspose.cells/cells/get_cell_display_style/#int-int) | Obtener el estilo de visualización de la celda dada.|
| [`get_cell_display_style(self, row, column, adjacent_borders)`](/cells/python-net/es/aspose.cells/cells/get_cell_display_style/#int-int-aspose.cells.bordertype) | Obtener el estilo de visualización de la celda dada.|
| [`get_row_enumerator(self)`](/cells/python-net/es/aspose.cells/cells/get_row_enumerator/#) | Obtiene el enumerador de filas.|
| [`get_merged_areas(self)`](/cells/python-net/es/aspose.cells/cells/get_merged_areas/#) | Obtiene todas las celdas fusionadas.|
| [`get_cell(self, row, column)`](/cells/python-net/es/aspose.cells/cells/get_cell/#int-int) | Obtiene el elemento [`Cell`](/cells/python-net/es/aspose.cells/cell) o nulo en el índice de fila de celda y el índice de columna especificados.|
| [`get_row(self, row)`](/cells/python-net/es/aspose.cells/cells/get_row/#int) | Obtiene el elemento [`Row`](/cells/python-net/es/aspose.cells/row) en el índice de fila de celda especificado.|
| [`check_cell(self, row, column)`](/cells/python-net/es/aspose.cells/cells/check_cell/#int-int) | Obtiene el elemento [`Cell`](/cells/python-net/es/aspose.cells/cell) o nulo en el índice de fila de celda y el índice de columna especificados.|
| [`check_row(self, row)`](/cells/python-net/es/aspose.cells/cells/check_row/#int) | Obtiene el elemento [`Row`](/cells/python-net/es/aspose.cells/row) o nulo en el índice de fila de celda especificado.|
| [`check_column(self, column_index)`](/cells/python-net/es/aspose.cells/cells/check_column/#int) | Obtiene el elemento [`Column`](/cells/python-net/es/aspose.cells/column) o nulo en el índice de columna especificado.|
| [`is_row_hidden(self, row_index)`](/cells/python-net/es/aspose.cells/cells/is_row_hidden/#int) | Comprueba si una fila en el índice dado está oculta.|
| [`is_column_hidden(self, column_index)`](/cells/python-net/es/aspose.cells/cells/is_column_hidden/#int) | Comprueba si una columna en el índice dado está oculta.|
| [`add_range(self, range_object)`](/cells/python-net/es/aspose.cells/cells/add_range/#aspose.cells.range) | Agrega una referencia de objeto de rango a las celdas|
| [`clear(self)`](/cells/python-net/es/aspose.cells/cells/clear/#) | Borra todos los datos de la hoja de cálculo.|
| [`import_array_list(self, array_list, first_row, first_column, is_vertical)`](/cells/python-net/es/aspose.cells/cells/import_array_list/#list-int-int-bool) | Importa una lista de matrices de datos a una hoja de cálculo.|
| [`import_formula_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/es/aspose.cells/cells/import_formula_array/#list-int-int-bool) | Importa una matriz de fórmulas a una hoja de cálculo.|
| [`text_to_columns(self, row, column, total_rows, options)`](/cells/python-net/es/aspose.cells/cells/text_to_columns/#int-int-int-aspose.cells.txtloadoptions) | Divide el contenido de la columna especificada en varias columnas.|
| [`un_merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/es/aspose.cells/cells/un_merge/#int-int-int-int) | Desvincula un rango específico de celdas fusionadas.|
| [`clear_merged_cells(self)`](/cells/python-net/es/aspose.cells/cells/clear_merged_cells/#) | Borra todos los rangos fusionados.|
| [`hide_row(self, row)`](/cells/python-net/es/aspose.cells/cells/hide_row/#int) |Oculta una fila.|
| [`unhide_row(self, row, height)`](/cells/python-net/es/aspose.cells/cells/unhide_row/#int-float) | Muestra una fila.|
| [`hide_rows(self, row, total_rows)`](/cells/python-net/es/aspose.cells/cells/hide_rows/#int-int) | Oculta varias filas.|
| [`unhide_rows(self, row, total_rows, height)`](/cells/python-net/es/aspose.cells/cells/unhide_rows/#int-int-float) | Muestra las filas ocultas.|
| [`set_row_height_pixel(self, row, pixels)`](/cells/python-net/es/aspose.cells/cells/set_row_height_pixel/#int-int) | Establece la altura de la fila en unidades de píxeles.|
| [`set_row_height_inch(self, row, inches)`](/cells/python-net/es/aspose.cells/cells/set_row_height_inch/#int-float) | Establece la altura de la fila en unidades de pulgadas.|
| [`set_row_height(self, row, height)`](/cells/python-net/es/aspose.cells/cells/set_row_height/#int-float) | Establece la altura de la fila especificada.|
| [`get_row_original_height_point(self, row)`](/cells/python-net/es/aspose.cells/cells/get_row_original_height_point/#int) | Obtiene la altura de la fila original en unidades de puntos si la fila está oculta|
| [`get_column_original_width_point(self, column)`](/cells/python-net/es/aspose.cells/cells/get_column_original_width_point/#int) | Obtiene la altura de la columna original en unidades de puntos si la columna está oculta|
| [`hide_column(self, column)`](/cells/python-net/es/aspose.cells/cells/hide_column/#int) | Oculta una columna.|
| [`unhide_column(self, column, width)`](/cells/python-net/es/aspose.cells/cells/unhide_column/#int-float) | Muestra una columna|
| [`hide_columns(self, column, total_columns)`](/cells/python-net/es/aspose.cells/cells/hide_columns/#int-int) | Ocultar varias columnas.|
| [`unhide_columns(self, column, total_columns, width)`](/cells/python-net/es/aspose.cells/cells/unhide_columns/#int-int-float) | Mostrar varias columnas.|
| [`get_view_row_height(self, row)`](/cells/python-net/es/aspose.cells/cells/get_view_row_height/#int) | Obtiene la altura de una fila especificada.|
| [`get_row_height_inch(self, row)`](/cells/python-net/es/aspose.cells/cells/get_row_height_inch/#int) | Obtiene la altura de una fila especificada en unidades de pulgadas.|
| [`get_view_row_height_inch(self, row)`](/cells/python-net/es/aspose.cells/cells/get_view_row_height_inch/#int) | Obtiene la altura de una fila especificada en unidades de pulgadas.|
| [`get_row_height_pixel(self, row)`](/cells/python-net/es/aspose.cells/cells/get_row_height_pixel/#int) | Obtiene la altura de una fila especificada en unidades de píxeles.|
| [`set_column_width_pixel(self, column, pixels)`](/cells/python-net/es/aspose.cells/cells/set_column_width_pixel/#int-int) | Establece el ancho de la columna en unidades de píxeles en la vista normal.|
| [`set_column_width_inch(self, column, inches)`](/cells/python-net/es/aspose.cells/cells/set_column_width_inch/#int-float) | Establece el ancho de la columna en unidades de pulgadas en la vista normal.|
| [`set_column_width(self, column, width)`](/cells/python-net/es/aspose.cells/cells/set_column_width/#int-float) | Establece el ancho de la columna especificada en la vista normal.|
| [`get_column_width_inch(self, column)`](/cells/python-net/es/aspose.cells/cells/get_column_width_inch/#int) | Obtiene el ancho de la columna especificada en la vista normal, en unidades de pulgadas.|
| [`get_view_column_width_pixel(self, column)`](/cells/python-net/es/aspose.cells/cells/get_view_column_width_pixel/#int) | Obtenga el ancho en diferentes tipos de vista.|
| [`set_view_column_width_pixel(self, column, pixels)`](/cells/python-net/es/aspose.cells/cells/set_view_column_width_pixel/#int-int) |Establece el ancho de la columna en diferentes vistas.|
| [`get_last_data_row(self, column)`](/cells/python-net/es/aspose.cells/cells/get_last_data_row/#int) | Obtiene el índice de la última fila de la celda que contiene datos en la columna especificada.|
| [`get_first_data_row(self, column)`](/cells/python-net/es/aspose.cells/cells/get_first_data_row/#int) | Obtiene el índice de la primera fila de la celda que contiene datos en la columna especificada.|
| [`apply_column_style(self, column, style, flag)`](/cells/python-net/es/aspose.cells/cells/apply_column_style/#int-aspose.cells.style-aspose.cells.styleflag) | Aplica formatos para una columna completa.|
| [`apply_row_style(self, row, style, flag)`](/cells/python-net/es/aspose.cells/cells/apply_row_style/#int-aspose.cells.style-aspose.cells.styleflag) | Aplica formatos para una fila completa.|
| [`apply_style(self, style, flag)`](/cells/python-net/es/aspose.cells/cells/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Aplica formatos para toda una hoja de cálculo.|
| [`copy_column(self, source_cells, source_column_index, destination_column_index)`](/cells/python-net/es/aspose.cells/cells/copy_column/#aspose.cells.cells-int-int) | Copia datos y formatos de una columna completa.|
| [`copy_row(self, source_cells, source_row_index, destination_row_index)`](/cells/python-net/es/aspose.cells/cells/copy_row/#aspose.cells.cells-int-int) | Copia datos y formatos de una fila completa.|
| [`get_grouped_row_outline_level(self, row_index)`](/cells/python-net/es/aspose.cells/cells/get_grouped_row_outline_level/#int) | Obtiene el nivel de contorno (basado en cero) de la fila.|
| [`get_grouped_column_outline_level(self, column_index)`](/cells/python-net/es/aspose.cells/cells/get_grouped_column_outline_level/#int) | Obtiene el nivel de esquema (basado en cero) de la columna.|
| [`get_max_grouped_column_outline_level(self)`](/cells/python-net/es/aspose.cells/cells/get_max_grouped_column_outline_level/#) | Obtiene el nivel máximo de esquema de columna agrupada (basado en cero).|
| [`get_max_grouped_row_outline_level(self)`](/cells/python-net/es/aspose.cells/cells/get_max_grouped_row_outline_level/#) | Obtiene el nivel máximo de contorno de fila agrupada (basado en cero).|
| [`show_group_detail(self, is_vertical, index)`](/cells/python-net/es/aspose.cells/cells/show_group_detail/#bool-int) | Expande las filas/columnas agrupadas.|
| [`hide_group_detail(self, is_vertical, index)`](/cells/python-net/es/aspose.cells/cells/hide_group_detail/#bool-int) | Contrae las filas/columnas agrupadas.|
| [`ungroup_columns(self, first_index, last_index)`](/cells/python-net/es/aspose.cells/cells/ungroup_columns/#int-int) | Desagrupa columnas.|
| [`is_deleting_range_enabled(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/es/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) | Comprueba si se puede eliminar el rango.|
| [`is_blank_column(self, column_index)`](/cells/python-net/es/aspose.cells/cells/is_blank_column/#int) | Comprueba si la columna dada está en blanco (no contiene ningún dato).|
| [`insert_row(self, row_index)`](/cells/python-net/es/aspose.cells/cells/insert_row/#int) | Inserta una nueva fila en la hoja de cálculo.|
| [`link_to_xml_map(self, map_name, row, column, path)`](/cells/python-net/es/aspose.cells/cells/link_to_xml_map/#str-int-int-str) | Enlace a un mapa xml.|
| [`move_range(self, source_area, dest_row, dest_column)`](/cells/python-net/es/aspose.cells/cells/move_range/#aspose.cells.cellarea-int-int) | Mueve el rango.|
| [`insert_cut_cells(self, cut_range, row, column, shift_type)`](/cells/python-net/es/aspose.cells/cells/insert_cut_cells/#aspose.cells.range-int-int-aspose.cells.shifttype) | Insertar rango de corte.|
| [`delete_range(self, start_row, start_column, end_row, end_column, shift_type)`](/cells/python-net/es/aspose.cells/cells/delete_range/#int-int-int-int-aspose.cells.shifttype) |Elimina un rango de celdas y desplaza las celdas según la opción de desplazamiento.|
| [`retrieve_subtotal_setting(self, ca)`](/cells/python-net/es/aspose.cells/cells/retrieve_subtotal_setting/#aspose.cells.cellarea) | Recupera la configuración de subtotales del rango.|
| [`remove_formulas(self)`](/cells/python-net/es/aspose.cells/cells/remove_formulas/#) | Elimina todas las fórmulas y las reemplaza con el valor de la fórmula.|
| [`convert_string_to_numeric_value(self)`](/cells/python-net/es/aspose.cells/cells/convert_string_to_numeric_value/#) | Convierte todos los datos de cadena en la hoja de cálculo en valores numéricos si es posible.|
| [`get_dependents(self, is_all, row, column)`](/cells/python-net/es/aspose.cells/cells/get_dependents/#bool-int-int) | Obtener todas las celdas que hacen referencia a la celda específica.|
| [`get_dependents_in_calculation(self, row, column, recursive)`](/cells/python-net/es/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) | Obtiene todas las celdas cuyo resultado calculado depende de una celda específica.|
| [`get_cells_with_place_in_cell_picture(self)`](/cells/python-net/es/aspose.cells/cells/get_cells_with_place_in_cell_picture/#) | Obtiene todas las celdas que contienen una imagen incrustada.|
| [`get_cell_style(self, row, column)`](/cells/python-net/es/aspose.cells/cells/get_cell_style/#int-int) | Obtener el estilo de la celda dada.|



###  Observaciones



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
* clase [`Column`](/cells/python-net/es/aspose.cells/column)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
* clase [`Row`](/cells/python-net/es/aspose.cells/row)
