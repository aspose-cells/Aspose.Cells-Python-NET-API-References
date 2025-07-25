---
title: ShapeCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 510
url: /ru/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection класс
Представляет все фигуры на рабочем листе/диаграмме.



Тип ShapeCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.drawing/shapecollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Добавьте фигуру на диаграмму. Единица измерения — 1/4000 площади диаграммы.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Добавьте фигуру на диаграмму. Единица измерения — 1/4000 площади диаграммы.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Добавьте фигуру на диаграмму. Все единицы измерения — проценты от площади диаграммы.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Добавьте фигуру на диаграмму. Единица измерения — 1/4000 площади диаграммы.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Добавляет картинку в коллекцию.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Добавляет картинку в коллекцию.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/get/#str) | Получает объект [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape) по имени формы.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Добавляет и копирует фигуру на рабочий лист.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Добавляет флажок на рабочий лист.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Добавляет текстовое поле на рабочий лист.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Добавьте объект уравнения на рабочий лист.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Добавляет счетчик на рабочий лист.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Добавляет полосу прокрутки на рабочий лист.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Добавляет RadioButton на рабочий лист.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Добавляет ListBox на рабочий лист.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Добавляет ComboBox на рабочий лист.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Добавляет GroupBox на рабочий лист.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Добавляет кнопку на рабочий лист.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Добавляет метку на рабочий лист.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Добавляет метку к диаграмме.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Добавляет текстовое поле к диаграмме.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Вставляет объект WordArt в диаграмму|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Вставляет объект WordArt.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Добавляет предустановленные элементы WordArt, начиная с Excel 2007.|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Добавляет RectangleShape на рабочий лист.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Добавляет овал на рабочий лист.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Добавляет LineShape на рабочий лист.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Добавляет на рабочий лист свободно перемещаемую фигуру. Применяется только к фигурам линии/изображения.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Добавляет ArcShape на рабочий лист.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Добавляет фигуру на рабочий лист.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Добавляет автофигуру на рабочий лист.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Добавляет автофигуру к диаграмме.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Создает элемент управления ActiveX.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | Добавляет изображение SVG.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | Добавляет изображение SVG.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Добавьте связанное изображение.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Добавьте связанное изображение.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Добавляет картинку на диаграмму.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Добавляет OleObject.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Скопировать все комментарии в диапазоне.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Копировать фигуры из указанного диапазона в целевой диапазон.|
| [`delete_in_range(self, ca)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Удалить фигуры в диапазоне. Фигуры комментариев не будут удалены.|
| [`delete_shape(self, shape)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Удалить фигуру. Если фигура входит в группу или является комментарием, она не будет удалена.|
| [`group(self, group_items)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/group/#list) | Сгруппируйте фигуры.|
| [`ungroup(self, group)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Разгруппировывает элементы фигуры.|
| [`remove_a_shape(self, shape)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | Добавьте API for Python через .Net., так как этот API не поддерживается.|
| [`update_selected_value(self)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/update_selected_value/#) | Обновить выбранное значение значением связанной ячейки или диапазона фигуры.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Добавляет на рабочий лист фигуру произвольной формы.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Добавляет строку подписи на рабочий лист.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)
