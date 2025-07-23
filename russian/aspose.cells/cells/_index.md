---
title: Cells класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 160
url: /ru/aspose.cells/cells/
is_root: false
---
##  Cells класс
Инкапсулирует коллекцию объектов, соответствующих ячейке, например, [`Cell`](/cells/python-net/ru/aspose.cells/cell), [`Row`](/cells/python-net/ru/aspose.cells/row) и т. д.



Тип Cells предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [ods_cell_fields](/cells/python-net/ru/aspose.cells/cells/ods_cell_fields) | Получает список полей ods.|
| [count](/cells/python-net/ru/aspose.cells/cells/count) | Получает общее количество созданных экземпляров Cell объектов.|
| [count_large](/cells/python-net/ru/aspose.cells/cells/count_large) | Получает общее количество созданных экземпляров Cell объектов.|
| [rows](/cells/python-net/ru/aspose.cells/cells/rows) | Получает коллекцию из [`Row`](/cells/python-net/ru/aspose.cells/row) объектов, представляющих отдельные строки на этом листе.|
| [merged_cells](/cells/python-net/ru/aspose.cells/cells/merged_cells) | Получает коллекцию объединенных ячеек.|
| [multi_thread_reading](/cells/python-net/ru/aspose.cells/cells/multi_thread_reading) | Возвращает или задает, должна ли модель данных ячеек поддерживать многопоточное чтение.<br/> Значение этого свойства по умолчанию — false.|
| [memory_setting](/cells/python-net/ru/aspose.cells/cells/memory_setting) | Возвращает или задает параметр использования памяти для этих ячеек.|
| [style](/cells/python-net/ru/aspose.cells/cells/style) | Получает и задает стиль рабочего листа по умолчанию.|
| [is_default_column_hidden](/cells/python-net/ru/aspose.cells/cells/is_default_column_hidden) |  |
| [standard_width_inch](/cells/python-net/ru/aspose.cells/cells/standard_width_inch) | Возвращает или задает ширину столбца по умолчанию на листе (в дюймах).|
| [standard_width_pixels](/cells/python-net/ru/aspose.cells/cells/standard_width_pixels) |Возвращает или задает ширину столбца по умолчанию на листе (в пикселях).|
| [standard_width](/cells/python-net/ru/aspose.cells/cells/standard_width) | Возвращает или задает ширину столбца по умолчанию на листе (в символах).|
| [standard_height](/cells/python-net/ru/aspose.cells/cells/standard_height) | Возвращает или задает высоту строки по умолчанию на этом листе (в пунктах).|
| [standard_height_pixels](/cells/python-net/ru/aspose.cells/cells/standard_height_pixels) | Возвращает или задает высоту строки по умолчанию на этом листе (в пикселях).|
| [standard_height_inch](/cells/python-net/ru/aspose.cells/cells/standard_height_inch) | Возвращает или задает высоту строки по умолчанию на этом листе в дюймах.|
| [preserve_string](/cells/python-net/ru/aspose.cells/cells/preserve_string) | Возвращает или задает значение, указывающее, сохраняются ли все значения рабочего листа в виде строк.<br/> Значение по умолчанию — false.|
| [min_row](/cells/python-net/ru/aspose.cells/cells/min_row) | Минимальный индекс строки ячейки, содержащей данные или стиль.|
| [max_row](/cells/python-net/ru/aspose.cells/cells/max_row) | Максимальный индекс строки ячейки, содержащей данные или стиль.|
| [min_column](/cells/python-net/ru/aspose.cells/cells/min_column) | Минимальный индекс столбца тех ячеек, которые были созданы в коллекции (не включает столбец<br/> где стиль определен для всего столбца, но в нем не создана ни одна ячейка).|
| [max_column](/cells/python-net/ru/aspose.cells/cells/max_column) | Максимальный индекс столбца тех ячеек, которые были созданы в коллекции (не включает столбец<br/> где стиль определен для всего столбца, но в нем не создана ни одна ячейка).|
| [min_data_row](/cells/python-net/ru/aspose.cells/cells/min_data_row) |Минимальный индекс строки ячейки, содержащей данные.|
| [max_data_row](/cells/python-net/ru/aspose.cells/cells/max_data_row) | Максимальный индекс строки ячейки, содержащей данные.|
| [min_data_column](/cells/python-net/ru/aspose.cells/cells/min_data_column) | Минимальный индекс столбца ячейки, содержащей данные.|
| [max_data_column](/cells/python-net/ru/aspose.cells/cells/max_data_column) | Максимальный индекс столбца ячейки, содержащей данные.|
| [is_default_row_height_matched](/cells/python-net/ru/aspose.cells/cells/is_default_row_height_matched) | Указывает, что высота строки и высота шрифта по умолчанию совпадают.|
| [is_default_row_hidden](/cells/python-net/ru/aspose.cells/cells/is_default_row_hidden) | Указывает, скрыта ли строка по умолчанию.|
| [columns](/cells/python-net/ru/aspose.cells/cells/columns) | Получает коллекцию из [`Column`](/cells/python-net/ru/aspose.cells/column) объектов, представляющих отдельные столбцы на этом листе.|
| [ranges](/cells/python-net/ru/aspose.cells/cells/ranges) | Получает коллекцию из [`Range`](/cells/python-net/ru/aspose.cells/range) объектов, созданных во время выполнения.|
| [last_cell](/cells/python-net/ru/aspose.cells/cells/last_cell) | Получает последнюю ячейку на этом листе.|
| [max_display_range](/cells/python-net/ru/aspose.cells/cells/max_display_range) | Получает максимальный диапазон, включающий данные, объединенные ячейки и фигуры.|
| [first_cell](/cells/python-net/ru/aspose.cells/cells/first_cell) | Получает первую ячейку на этом листе.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`create_range(self, upper_left_cell, lower_right_cell)`](/cells/python-net/ru/aspose.cells/cells/create_range/#str-str) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из диапазона ячеек.|
| [`create_range(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/ru/aspose.cells/cells/create_range/#int-int-int-int) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из диапазона ячеек.|
| [`create_range(self, address)`](/cells/python-net/ru/aspose.cells/cells/create_range/#str) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из адреса диапазона.|
| [`create_range(self, first_index, number, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/create_range/#int-int-bool) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из строк ячеек или столбцов ячеек.|
| [`get(self, row, column)`](/cells/python-net/ru/aspose.cells/cells/get/#int-int) | Добавьте API for Python через .Net.since this[int row, int column] не поддерживается|
| [`get(self, cell_name)`](/cells/python-net/ru/aspose.cells/cells/get/#str) |Добавьте API for Python через .Net.since this[string cellName] не поддерживается|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/import_object_array/#list-int-int-bool) | Импортирует массив данных на рабочий лист.|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical, skip)`](/cells/python-net/ru/aspose.cells/cells/import_object_array/#list-int-int-bool-int) | Импортирует массив данных на рабочий лист.|
| [`import_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/import_array/#list-int-int-bool) | Импортирует массив строк на рабочий лист.|
| [`import_array(self, int_array, first_row, first_column, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/import_array/#list-int-int-bool) | Импортирует массив целых чисел на рабочий лист.|
| [`import_array(self, double_array, first_row, first_column, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/import_array/#list-int-int-bool) | Импортирует массив чисел двойной точности на рабочий лист.|
| [`import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/ru/aspose.cells/cells/import_csv/#str-str-bool-int-int) | Импортируйте файл CSV в ячейки.|
| [`import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/ru/aspose.cells/cells/import_csv/#io.rawiobase-str-bool-int-int) | Импортируйте файл CSV в ячейки.|
| [`import_csv(self, file_name, options, first_row, first_column)`](/cells/python-net/ru/aspose.cells/cells/import_csv/#str-aspose.cells.txtloadoptions-int-int) | Импортируйте файл CSV в ячейки.|
| [`import_csv(self, stream, options, first_row, first_column)`](/cells/python-net/ru/aspose.cells/cells/import_csv/#io.rawiobase-aspose.cells.txtloadoptions-int-int) | Импортируйте файл CSV в ячейки.|
| [`merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/ru/aspose.cells/cells/merge/#int-int-int-int) | Объединяет указанный диапазон ячеек в одну ячейку.|
| [`merge(self, first_row, first_column, total_rows, total_columns, merge_conflict)`](/cells/python-net/ru/aspose.cells/cells/merge/#int-int-int-int-bool) | Объединяет указанный диапазон ячеек в одну ячейку.|
| [`merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)`](/cells/python-net/ru/aspose.cells/cells/merge/#int-int-int-int-bool-bool) | Объединяет указанный диапазон ячеек в одну ячейку.|
| [`get_row_height(self, row, is_original, unit_type)`](/cells/python-net/ru/aspose.cells/cells/get_row_height/#int-bool-aspose.cells.cellsunittype) | Получает высоту строки.|
| [`get_row_height(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_row_height/#int) | Получает высоту указанной строки в точках.|
| [`get_column_width(self, column, is_original, unit_type)`](/cells/python-net/ru/aspose.cells/cells/get_column_width/#int-bool-aspose.cells.cellsunittype) | Получает ширину столбца.|
| [`get_column_width(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_column_width/#int) | Получает ширину (в символах) указанного столбца в обычном режиме просмотра.|
| [`get_column_width_pixel(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_column_width_pixel/#int) | Получает ширину указанного столбца в обычном режиме просмотра в пикселях.|
| [`get_column_width_pixel(self, column, original)`](/cells/python-net/ru/aspose.cells/cells/get_column_width_pixel/#int-bool) | Получает ширину указанного столбца в обычном режиме просмотра в пикселях.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number, paste_options)`](/cells/python-net/ru/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-aspose.cells.pasteoptions) | Копирует данные и форматы целого столбца.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number)`](/cells/python-net/ru/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int) | Копирует данные и форматы целого столбца.|
| [`copy_columns(self, source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)`](/cells/python-net/ru/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-int) | Копирует данные и форматы всех столбцов.|
| [`copy_rows(self, source_cells, source_row_index, destination_row_index, row_number)`](/cells/python-net/ru/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int) | Копирует данные и форматы некоторых целых строк.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options)`](/cells/python-net/ru/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions) | Копирует данные и форматы некоторых целых строк.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)`](/cells/python-net/ru/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions-aspose.cells.pasteoptions) | Копирует данные и форматы некоторых целых строк.|
| [`group_columns(self, first_index, last_index)`](/cells/python-net/ru/aspose.cells/cells/group_columns/#int-int) | Группирует столбцы.|
| [`group_columns(self, first_index, last_index, is_hidden)`](/cells/python-net/ru/aspose.cells/cells/group_columns/#int-int-bool) | Группирует столбцы.|
| [`ungroup_rows(self, first_index, last_index, is_all)`](/cells/python-net/ru/aspose.cells/cells/ungroup_rows/#int-int-bool) | Разгруппировывает строки.|
| [`ungroup_rows(self, first_index, last_index)`](/cells/python-net/ru/aspose.cells/cells/ungroup_rows/#int-int) | Разгруппировывает строки.|
| [`group_rows(self, first_index, last_index, is_hidden)`](/cells/python-net/ru/aspose.cells/cells/group_rows/#int-int-bool) | Группирует строки.|
| [`group_rows(self, first_index, last_index)`](/cells/python-net/ru/aspose.cells/cells/group_rows/#int-int) | Группирует строки.|
| [`delete_column(self, column_index, update_reference)`](/cells/python-net/ru/aspose.cells/cells/delete_column/#int-bool) | Удаляет столбец.|
| [`delete_column(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/delete_column/#int) | Удаляет столбец.|
| [`delete_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/ru/aspose.cells/cells/delete_columns/#int-int-bool) | Удаляет несколько столбцов.|
| [`delete_columns(self, column_index, total_columns, options)`](/cells/python-net/ru/aspose.cells/cells/delete_columns/#int-int-aspose.cells.deleteoptions) | Удаляет несколько столбцов.|
| [`delete_row(self, row_index)`](/cells/python-net/ru/aspose.cells/cells/delete_row/#int) | Удаляет строку.|
| [`delete_row(self, row_index, update_reference)`](/cells/python-net/ru/aspose.cells/cells/delete_row/#int-bool) | Удаляет строку.|
| [`delete_rows(self, row_index, total_rows)`](/cells/python-net/ru/aspose.cells/cells/delete_rows/#int-int) |Удаляет несколько строк.|
| [`delete_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/ru/aspose.cells/cells/delete_rows/#int-int-bool) | Удаляет несколько строк на листе.|
| [`delete_rows(self, row_index, total_rows, options)`](/cells/python-net/ru/aspose.cells/cells/delete_rows/#int-int-aspose.cells.deleteoptions) | Удаляет несколько строк на листе.|
| [`delete_blank_columns(self)`](/cells/python-net/ru/aspose.cells/cells/delete_blank_columns/#) | Удалите все пустые столбцы, не содержащие данных.|
| [`delete_blank_columns(self, options)`](/cells/python-net/ru/aspose.cells/cells/delete_blank_columns/#aspose.cells.deleteoptions) | Удалите все пустые столбцы, не содержащие данных.|
| [`delete_blank_rows(self)`](/cells/python-net/ru/aspose.cells/cells/delete_blank_rows/#) | Удалите все пустые строки, не содержащие никаких данных или других объектов.|
| [`delete_blank_rows(self, options)`](/cells/python-net/ru/aspose.cells/cells/delete_blank_rows/#aspose.cells.deleteoptions) | Удалите все пустые строки, которые не содержат никаких данных или специальных объектов, таких как видимые комментарии, сводная таблица.|
| [`insert_columns(self, column_index, total_columns)`](/cells/python-net/ru/aspose.cells/cells/insert_columns/#int-int) | Вставляет несколько столбцов в рабочий лист.|
| [`insert_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/ru/aspose.cells/cells/insert_columns/#int-int-bool) | Вставляет несколько столбцов в рабочий лист.|
| [`insert_columns(self, column_index, total_columns, options)`](/cells/python-net/ru/aspose.cells/cells/insert_columns/#int-int-aspose.cells.insertoptions) | Вставляет несколько столбцов в рабочий лист.|
| [`insert_column(self, column_index, update_reference)`](/cells/python-net/ru/aspose.cells/cells/insert_column/#int-bool) | Вставляет новый столбец в рабочий лист.|
| [`insert_column(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/insert_column/#int) | Вставляет новый столбец в рабочий лист.|
| [`insert_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/ru/aspose.cells/cells/insert_rows/#int-int-bool) | Вставляет несколько строк в рабочий лист.|
| [`insert_rows(self, row_index, total_rows, options)`](/cells/python-net/ru/aspose.cells/cells/insert_rows/#int-int-aspose.cells.insertoptions) | Вставляет несколько строк в рабочий лист.|
| [`insert_rows(self, row_index, total_rows)`](/cells/python-net/ru/aspose.cells/cells/insert_rows/#int-int) | Вставляет несколько строк в рабочий лист.|
| [`clear_range(self, range)`](/cells/python-net/ru/aspose.cells/cells/clear_range/#aspose.cells.cellarea) | Очищает содержимое и форматирование диапазона.|
| [`clear_range(self, start_row, start_column, end_row, end_column)`](/cells/python-net/ru/aspose.cells/cells/clear_range/#int-int-int-int) | Очищает содержимое и форматирование диапазона.|
| [`clear_contents(self, range)`](/cells/python-net/ru/aspose.cells/cells/clear_contents/#aspose.cells.cellarea) | Очищает содержимое диапазона.|
| [`clear_contents(self, start_row, start_column, end_row, end_column)`](/cells/python-net/ru/aspose.cells/cells/clear_contents/#int-int-int-int) | Очищает содержимое диапазона.|
| [`clear_formats(self, range)`](/cells/python-net/ru/aspose.cells/cells/clear_formats/#aspose.cells.cellarea) | Очищает форматирование диапазона.|
| [`clear_formats(self, start_row, start_column, end_row, end_column)`](/cells/python-net/ru/aspose.cells/cells/clear_formats/#int-int-int-int) | Очищает форматирование диапазона.|
| [`find(self, what, previous_cell)`](/cells/python-net/ru/aspose.cells/cells/find/#any-aspose.cells.cell) | Находит ячейку, содержащую входной объект.|
| [`find(self, what, previous_cell, find_options)`](/cells/python-net/ru/aspose.cells/cells/find/#any-aspose.cells.cell-aspose.cells.findoptions) | Находит ячейку, содержащую входной объект.|
| [`end_cell_in_row(self, row_index)`](/cells/python-net/ru/aspose.cells/cells/end_cell_in_row/#int) | Получает последнюю ячейку в этой строке.|
| [`end_cell_in_row(self, start_row, end_row, start_column, end_column)`](/cells/python-net/ru/aspose.cells/cells/end_cell_in_row/#int-int-int-int) | Получает последнюю ячейку с максимальным индексом строки в этом диапазоне.|
| [`end_cell_in_column(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/end_cell_in_column/#int) | Получает последнюю ячейку в этом столбце.|
| [`end_cell_in_column(self, start_row, end_row, start_column, end_column)`](/cells/python-net/ru/aspose.cells/cells/end_cell_in_column/#int-int-int-int) | Получает последнюю ячейку с максимальным индексом столбца в данном диапазоне.|
| [`insert_range(self, area, shift_number, shift_type, update_reference)`](/cells/python-net/ru/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype-bool) | Вставляет диапазон ячеек и сдвигает ячейки в соответствии с параметром сдвига.|
| [`insert_range(self, area, shift_type)`](/cells/python-net/ru/aspose.cells/cells/insert_range/#aspose.cells.cellarea-aspose.cells.shifttype) | Вставляет диапазон ячеек и сдвигает ячейки в соответствии с параметром сдвига.|
| [`insert_range(self, area, shift_number, shift_type)`](/cells/python-net/ru/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype) | Вставляет диапазон ячеек и сдвигает ячейки в соответствии с параметром сдвига.|
| [`subtotal(self, ca, group_by, function, total_list)`](/cells/python-net/ru/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list) | Создает промежуточные итоги для диапазона.|
| [`subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data)`](/cells/python-net/ru/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list-bool-bool-bool) | Создает промежуточные итоги для диапазона.|
| [`remove_duplicates(self)`](/cells/python-net/ru/aspose.cells/cells/remove_duplicates/#) |Удаляет дублирующиеся строки на листе.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column)`](/cells/python-net/ru/aspose.cells/cells/remove_duplicates/#int-int-int-int) | Удаляет повторяющиеся значения в диапазоне.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets)`](/cells/python-net/ru/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) | Удаляет дублирующиеся данные диапазона.|
| [`get_cell_display_style(self, row, column)`](/cells/python-net/ru/aspose.cells/cells/get_cell_display_style/#int-int) | Получить стиль отображения заданной ячейки.|
| [`get_cell_display_style(self, row, column, adjacent_borders)`](/cells/python-net/ru/aspose.cells/cells/get_cell_display_style/#int-int-aspose.cells.bordertype) | Получить стиль отображения заданной ячейки.|
| [`get_row_enumerator(self)`](/cells/python-net/ru/aspose.cells/cells/get_row_enumerator/#) | Получает перечислитель строк.|
| [`get_merged_areas(self)`](/cells/python-net/ru/aspose.cells/cells/get_merged_areas/#) | Получает все объединенные ячейки.|
| [`get_cell(self, row, column)`](/cells/python-net/ru/aspose.cells/cells/get_cell/#int-int) | Возвращает элемент [`Cell`](/cells/python-net/ru/aspose.cells/cell) или значение NULL по указанному индексу строки ячейки и индексу столбца.|
| [`get_row(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_row/#int) | Получает элемент [`Row`](/cells/python-net/ru/aspose.cells/row) по указанному индексу строки ячейки.|
| [`check_cell(self, row, column)`](/cells/python-net/ru/aspose.cells/cells/check_cell/#int-int) | Возвращает элемент [`Cell`](/cells/python-net/ru/aspose.cells/cell) или значение NULL по указанному индексу строки ячейки и индексу столбца.|
| [`check_row(self, row)`](/cells/python-net/ru/aspose.cells/cells/check_row/#int) | Получает элемент [`Row`](/cells/python-net/ru/aspose.cells/row) или значение NULL по указанному индексу строки ячейки.|
| [`check_column(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/check_column/#int) | Получает элемент [`Column`](/cells/python-net/ru/aspose.cells/column) или значение NULL по указанному индексу столбца.|
| [`is_row_hidden(self, row_index)`](/cells/python-net/ru/aspose.cells/cells/is_row_hidden/#int) | Проверяет, скрыта ли строка по указанному индексу.|
| [`is_column_hidden(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/is_column_hidden/#int) | Проверяет, скрыт ли столбец по заданному индексу.|
| [`add_range(self, range_object)`](/cells/python-net/ru/aspose.cells/cells/add_range/#aspose.cells.range) | Добавляет ссылку на объект диапазона к ячейкам|
| [`clear(self)`](/cells/python-net/ru/aspose.cells/cells/clear/#) | Удаляет все данные с листа.|
| [`import_array_list(self, array_list, first_row, first_column, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/import_array_list/#list-int-int-bool) | Импортирует массив данных на рабочий лист.|
| [`import_formula_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/ru/aspose.cells/cells/import_formula_array/#list-int-int-bool) | Импортирует массив формул на рабочий лист.|
| [`text_to_columns(self, row, column, total_rows, options)`](/cells/python-net/ru/aspose.cells/cells/text_to_columns/#int-int-int-aspose.cells.txtloadoptions) | Разделяет содержимое указанного столбца на несколько столбцов.|
| [`un_merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/ru/aspose.cells/cells/un_merge/#int-int-int-int) | Разделяет указанный диапазон объединенных ячеек.|
| [`clear_merged_cells(self)`](/cells/python-net/ru/aspose.cells/cells/clear_merged_cells/#) | Очищает все объединенные диапазоны.|
| [`hide_row(self, row)`](/cells/python-net/ru/aspose.cells/cells/hide_row/#int) |Скрывает строку.|
| [`unhide_row(self, row, height)`](/cells/python-net/ru/aspose.cells/cells/unhide_row/#int-float) | Отображает строку.|
| [`hide_rows(self, row, total_rows)`](/cells/python-net/ru/aspose.cells/cells/hide_rows/#int-int) | Скрывает несколько строк.|
| [`unhide_rows(self, row, total_rows, height)`](/cells/python-net/ru/aspose.cells/cells/unhide_rows/#int-int-float) | Показывает скрытые строки.|
| [`set_row_height_pixel(self, row, pixels)`](/cells/python-net/ru/aspose.cells/cells/set_row_height_pixel/#int-int) | Задает высоту строки в пикселях.|
| [`set_row_height_inch(self, row, inches)`](/cells/python-net/ru/aspose.cells/cells/set_row_height_inch/#int-float) | Задает высоту строки в дюймах.|
| [`set_row_height(self, row, height)`](/cells/python-net/ru/aspose.cells/cells/set_row_height/#int-float) | Устанавливает высоту указанной строки.|
| [`get_row_original_height_point(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_row_original_height_point/#int) | Получает высоту исходной строки в пунктах, если строка скрыта.|
| [`get_column_original_width_point(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_column_original_width_point/#int) | Получает высоту исходного столбца в пунктах, если столбец скрыт.|
| [`hide_column(self, column)`](/cells/python-net/ru/aspose.cells/cells/hide_column/#int) | Скрывает столбец.|
| [`unhide_column(self, column, width)`](/cells/python-net/ru/aspose.cells/cells/unhide_column/#int-float) | Отображает столбец|
| [`hide_columns(self, column, total_columns)`](/cells/python-net/ru/aspose.cells/cells/hide_columns/#int-int) | Скрыть несколько столбцов.|
| [`unhide_columns(self, column, total_columns, width)`](/cells/python-net/ru/aspose.cells/cells/unhide_columns/#int-int-float) | Показать несколько столбцов.|
| [`get_view_row_height(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_view_row_height/#int) | Получает высоту указанной строки.|
| [`get_row_height_inch(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_row_height_inch/#int) | Получает высоту указанной строки в дюймах.|
| [`get_view_row_height_inch(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_view_row_height_inch/#int) | Получает высоту указанной строки в дюймах.|
| [`get_row_height_pixel(self, row)`](/cells/python-net/ru/aspose.cells/cells/get_row_height_pixel/#int) | Получает высоту указанной строки в пикселях.|
| [`set_column_width_pixel(self, column, pixels)`](/cells/python-net/ru/aspose.cells/cells/set_column_width_pixel/#int-int) | Задает ширину столбца в пикселях в обычном режиме просмотра.|
| [`set_column_width_inch(self, column, inches)`](/cells/python-net/ru/aspose.cells/cells/set_column_width_inch/#int-float) | Задает ширину столбца в дюймах в обычном режиме просмотра.|
| [`set_column_width(self, column, width)`](/cells/python-net/ru/aspose.cells/cells/set_column_width/#int-float) | Устанавливает ширину указанного столбца в обычном режиме просмотра.|
| [`get_column_width_inch(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_column_width_inch/#int) | Возвращает ширину указанного столбца в обычном режиме просмотра в дюймах.|
| [`get_view_column_width_pixel(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_view_column_width_pixel/#int) | Получите ширину в разных типах представления.|
| [`set_view_column_width_pixel(self, column, pixels)`](/cells/python-net/ru/aspose.cells/cells/set_view_column_width_pixel/#int-int) |Устанавливает ширину столбца в разных представлениях.|
| [`get_last_data_row(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_last_data_row/#int) | Возвращает индекс последней строки ячейки, содержащей данные в указанном столбце.|
| [`get_first_data_row(self, column)`](/cells/python-net/ru/aspose.cells/cells/get_first_data_row/#int) | Возвращает индекс первой строки ячейки, содержащей данные в указанном столбце.|
| [`apply_column_style(self, column, style, flag)`](/cells/python-net/ru/aspose.cells/cells/apply_column_style/#int-aspose.cells.style-aspose.cells.styleflag) | Применяет форматирование ко всему столбцу.|
| [`apply_row_style(self, row, style, flag)`](/cells/python-net/ru/aspose.cells/cells/apply_row_style/#int-aspose.cells.style-aspose.cells.styleflag) | Применяет форматирование ко всей строке.|
| [`apply_style(self, style, flag)`](/cells/python-net/ru/aspose.cells/cells/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Применяет форматы ко всему рабочему листу.|
| [`copy_column(self, source_cells, source_column_index, destination_column_index)`](/cells/python-net/ru/aspose.cells/cells/copy_column/#aspose.cells.cells-int-int) | Копирует данные и форматы целого столбца.|
| [`copy_row(self, source_cells, source_row_index, destination_row_index)`](/cells/python-net/ru/aspose.cells/cells/copy_row/#aspose.cells.cells-int-int) | Копирует данные и форматы целой строки.|
| [`get_grouped_row_outline_level(self, row_index)`](/cells/python-net/ru/aspose.cells/cells/get_grouped_row_outline_level/#int) | Возвращает уровень структуры строки (отсчитывается от нуля).|
| [`get_grouped_column_outline_level(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/get_grouped_column_outline_level/#int) | Возвращает уровень структуры столбца (отсчитывается от нуля).|
| [`get_max_grouped_column_outline_level(self)`](/cells/python-net/ru/aspose.cells/cells/get_max_grouped_column_outline_level/#) | Получает максимальный уровень структуры сгруппированных столбцов (начиная с нуля).|
| [`get_max_grouped_row_outline_level(self)`](/cells/python-net/ru/aspose.cells/cells/get_max_grouped_row_outline_level/#) | Возвращает максимальный уровень структуры сгруппированных строк (начиная с нуля).|
| [`show_group_detail(self, is_vertical, index)`](/cells/python-net/ru/aspose.cells/cells/show_group_detail/#bool-int) | Разворачивает сгруппированные строки/столбцы.|
| [`hide_group_detail(self, is_vertical, index)`](/cells/python-net/ru/aspose.cells/cells/hide_group_detail/#bool-int) | Сворачивает сгруппированные строки/столбцы.|
| [`ungroup_columns(self, first_index, last_index)`](/cells/python-net/ru/aspose.cells/cells/ungroup_columns/#int-int) | Разгруппировать столбцы.|
| [`is_deleting_range_enabled(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/ru/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) | Проверьте, можно ли удалить диапазон.|
| [`is_blank_column(self, column_index)`](/cells/python-net/ru/aspose.cells/cells/is_blank_column/#int) | Проверяет, является ли заданный столбец пустым (не содержит никаких данных).|
| [`insert_row(self, row_index)`](/cells/python-net/ru/aspose.cells/cells/insert_row/#int) | Вставляет новую строку в рабочий лист.|
| [`link_to_xml_map(self, map_name, row, column, path)`](/cells/python-net/ru/aspose.cells/cells/link_to_xml_map/#str-int-int-str) | Ссылка на XML-карту.|
| [`move_range(self, source_area, dest_row, dest_column)`](/cells/python-net/ru/aspose.cells/cells/move_range/#aspose.cells.cellarea-int-int) | Перемещает диапазон.|
| [`insert_cut_cells(self, cut_range, row, column, shift_type)`](/cells/python-net/ru/aspose.cells/cells/insert_cut_cells/#aspose.cells.range-int-int-aspose.cells.shifttype) | Вставьте диапазон резки.|
| [`delete_range(self, start_row, start_column, end_row, end_column, shift_type)`](/cells/python-net/ru/aspose.cells/cells/delete_range/#int-int-int-int-aspose.cells.shifttype) |Удаляет диапазон ячеек и сдвигает ячейки в соответствии с параметром сдвига.|
| [`retrieve_subtotal_setting(self, ca)`](/cells/python-net/ru/aspose.cells/cells/retrieve_subtotal_setting/#aspose.cells.cellarea) | Извлекает настройки промежуточных итогов диапазона.|
| [`remove_formulas(self)`](/cells/python-net/ru/aspose.cells/cells/remove_formulas/#) | Удаляет все формулы и заменяет значением формулы.|
| [`convert_string_to_numeric_value(self)`](/cells/python-net/ru/aspose.cells/cells/convert_string_to_numeric_value/#) | Преобразует все строковые данные на листе в числовые значения, если это возможно.|
| [`get_dependents(self, is_all, row, column)`](/cells/python-net/ru/aspose.cells/cells/get_dependents/#bool-int-int) | Получить все ячейки, ссылающиеся на определенную ячейку.|
| [`get_dependents_in_calculation(self, row, column, recursive)`](/cells/python-net/ru/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) | Получает все ячейки, вычисленный результат которых зависит от определенной ячейки.|
| [`get_cells_with_place_in_cell_picture(self)`](/cells/python-net/ru/aspose.cells/cells/get_cells_with_place_in_cell_picture/#) | Получает все ячейки, содержащие встроенное изображение.|
| [`get_cell_style(self, row, column)`](/cells/python-net/ru/aspose.cells/cells/get_cell_style/#int-int) | Получить стиль заданной ячейки.|



###  Примечания



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
* класс [`Column`](/cells/python-net/ru/aspose.cells/column)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
* класс [`Row`](/cells/python-net/ru/aspose.cells/row)
