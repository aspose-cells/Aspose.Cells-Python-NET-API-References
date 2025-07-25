---
title: GroupShape класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 250
url: /ru/aspose.cells.drawing/groupshape/
is_root: false
---
##  GroupShape класс
Представляет собой групповую фигуру, содержащую отдельные фигуры.



**Наследование:** [`GroupShape`](/cells/python-net/aspose.cells.drawing/groupshape) → 
[`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)



Тип GroupShape предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [macro_name](/cells/python-net/ru/aspose.cells.drawing/groupshape/macro_name) | Получает и задает имя макроса.|
| [is_equation](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_equation) | Указывает, содержит ли форма только уравнение.|
| [is_smart_art](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_smart_art) | Указывает, является ли фигура интеллектуальным искусством.|
| [z_order_position](/cells/python-net/ru/aspose.cells.drawing/groupshape/z_order_position) | Возвращает положение фигуры в z-порядке.|
| [name](/cells/python-net/ru/aspose.cells.drawing/groupshape/name) | Получает и задает имя фигуры.|
| [alternative_text](/cells/python-net/ru/aspose.cells.drawing/groupshape/alternative_text) | Возвращает или задает описательную (альтернативную) текстовую строку объекта [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape).|
| [title](/cells/python-net/ru/aspose.cells.drawing/groupshape/title) | Задает заголовок (подпись) текущего объекта формы.|
| [line_format](/cells/python-net/ru/aspose.cells.drawing/groupshape/line_format) | Возвращает объект MsoLineFormat, содержащий свойства форматирования линии для указанной фигуры.|
| [fill_format](/cells/python-net/ru/aspose.cells.drawing/groupshape/fill_format) | Возвращает объект MsoFillFormat, содержащий свойства форматирования заливки для указанной фигуры.|
| [line](/cells/python-net/ru/aspose.cells.drawing/groupshape/line) | Получает стиль линии|
| [fill](/cells/python-net/ru/aspose.cells.drawing/groupshape/fill) | Возвращает объект [`Shape.fill_format`](/cells/python-net/ru/aspose.cells.drawing/shape#fill_format), содержащий свойства форматирования заливки для указанной фигуры.|
| [shadow_effect](/cells/python-net/ru/aspose.cells.drawing/groupshape/shadow_effect) | Представляет объект [`ShadowEffect`](/cells/python-net/ru/aspose.cells.drawing/shadoweffect), который задает эффект тени для элемента или фигуры диаграммы.|
| [reflection](/cells/python-net/ru/aspose.cells.drawing/groupshape/reflection) |Представляет объект [`ReflectionEffect`](/cells/python-net/ru/aspose.cells.drawing/reflectioneffect), который задает эффект отражения для элемента или фигуры диаграммы.|
| [glow](/cells/python-net/ru/aspose.cells.drawing/groupshape/glow) | Представляет объект [`GlowEffect`](/cells/python-net/ru/aspose.cells.drawing/gloweffect), который задает эффект свечения для элемента или фигуры диаграммы.|
| [soft_edges](/cells/python-net/ru/aspose.cells.drawing/groupshape/soft_edges) | Получает и задает радиус размытия, применяемый к краям, в точках.|
| [three_d_format](/cells/python-net/ru/aspose.cells.drawing/groupshape/three_d_format) | Получает и задает 3D-формат фигуры.|
| [format_picture](/cells/python-net/ru/aspose.cells.drawing/groupshape/format_picture) | Получает и задает параметры формата изображения.|
| [is_hidden](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_hidden) | Указывает, виден ли объект.|
| [is_lock_aspect_ratio](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_lock_aspect_ratio) | True означает, что соотношение сторон фигуры зафиксировано.|
| [is_aspect_ratio_locked](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_aspect_ratio_locked) | True означает, что соотношение сторон фигуры зафиксировано.|
| [rotation_angle](/cells/python-net/ru/aspose.cells.drawing/groupshape/rotation_angle) | Получает и задает поворот фигуры.|
| [hyperlink](/cells/python-net/ru/aspose.cells.drawing/groupshape/hyperlink) | Получает гиперссылку формы.|
| [id](/cells/python-net/ru/aspose.cells.drawing/groupshape/id) | Получает идентификатор этой формы.|
| [spid](/cells/python-net/ru/aspose.cells.drawing/groupshape/spid) | Указывает необязательный строковый идентификатор, который приложение может использовать для идентификации конкретной фигуры.|
| [spt](/cells/python-net/ru/aspose.cells.drawing/groupshape/spt) | Указывает необязательное число, которое приложение может использовать для связи конкретной фигуры с определенным типом фигуры.|
| [worksheet](/cells/python-net/ru/aspose.cells.drawing/groupshape/worksheet) | Получает объект [`Shape.worksheet`](/cells/python-net/ru/aspose.cells.drawing/shape#worksheet), содержащий эту форму.|
| [is_group](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_group) | Указывает, является ли данная фигура групповой фигурой.|
| [is_in_group](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_in_group) | Указывает, сгруппирована ли фигура.|
| [is_word_art](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_word_art) |Указывает, является ли данная форма произведением искусства.|
| [text_effect](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_effect) | Возвращает объект TextEffectFormat, содержащий свойства форматирования текста для указанной фигуры.<br/> Применяется к объектам Shape, представляющим WordArt.|
| [is_locked](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_locked) | True означает, что объект не может быть изменен, если лист защищен.<br/> Обратите внимание, что это значение имеет смысл только в том случае, если рабочий лист или объекты на нем защищены.|
| [is_printable](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_printable) | Указывает, можно ли распечатать объект.<br/> Если False, эта форма не будет напечатана при печати.|
| [mso_drawing_type](/cells/python-net/ru/aspose.cells.drawing/groupshape/mso_drawing_type) | Получает тип чертежа.|
| [auto_shape_type](/cells/python-net/ru/aspose.cells.drawing/groupshape/auto_shape_type) | Получает и задает тип автоматической фигуры.|
| [anchor_type](/cells/python-net/ru/aspose.cells.drawing/groupshape/anchor_type) | Получает и задает тип заполнителя якоря формы.|
| [placement](/cells/python-net/ru/aspose.cells.drawing/groupshape/placement) | Представляет собой способ присоединения объекта рисунка к ячейкам под ним.<br/> Свойство управляет размещением объекта на рабочем листе.|
| [upper_left_row](/cells/python-net/ru/aspose.cells.drawing/groupshape/upper_left_row) | Представляет индекс верхней строки.|
| [upper_delta_y](/cells/python-net/ru/aspose.cells.drawing/groupshape/upper_delta_y) | Возвращает или задает вертикальное смещение фигуры от ее верхней левой угловой строки.|
| [upper_left_column](/cells/python-net/ru/aspose.cells.drawing/groupshape/upper_left_column) | Представляет индекс столбца в левом верхнем углу.|
| [upper_delta_x](/cells/python-net/ru/aspose.cells.drawing/groupshape/upper_delta_x) |Возвращает или задает горизонтальное смещение фигуры от ее верхнего левого углового столбца.|
| [lower_right_row](/cells/python-net/ru/aspose.cells.drawing/groupshape/lower_right_row) | Представляет индекс строки в нижнем правом углу.|
| [lower_delta_y](/cells/python-net/ru/aspose.cells.drawing/groupshape/lower_delta_y) | Возвращает или задает вертикальное смещение фигуры от ее нижнего правого угла.|
| [lower_right_column](/cells/python-net/ru/aspose.cells.drawing/groupshape/lower_right_column) | Представляет индекс столбца в правом нижнем углу.|
| [lower_delta_x](/cells/python-net/ru/aspose.cells.drawing/groupshape/lower_delta_x) | Возвращает или задает горизонтальное смещение фигуры от ее нижнего правого углового столбца.|
| [right](/cells/python-net/ru/aspose.cells.drawing/groupshape/right) | Представляет ширину горизонтального смещения фигуры от ее нижнего правого углового столбца в пикселях.|
| [bottom](/cells/python-net/ru/aspose.cells.drawing/groupshape/bottom) | Представляет ширину вертикального смещения фигуры от ее нижнего нижнего угла в пикселях.|
| [width](/cells/python-net/ru/aspose.cells.drawing/groupshape/width) | Представляет ширину фигуры в пикселях.|
| [width_inch](/cells/python-net/ru/aspose.cells.drawing/groupshape/width_inch) | Представляет ширину фигуры в дюймах.|
| [width_pt](/cells/python-net/ru/aspose.cells.drawing/groupshape/width_pt) | Представляет ширину фигуры в точках.|
| [width_cm](/cells/python-net/ru/aspose.cells.drawing/groupshape/width_cm) | Представляет ширину фигуры в сантиметрах.|
| [height](/cells/python-net/ru/aspose.cells.drawing/groupshape/height) | Представляет высоту фигуры в пикселях.|
| [height_inch](/cells/python-net/ru/aspose.cells.drawing/groupshape/height_inch) | Представляет высоту фигуры в дюймах.|
| [height_pt](/cells/python-net/ru/aspose.cells.drawing/groupshape/height_pt) |Представляет высоту фигуры в точках.|
| [height_cm](/cells/python-net/ru/aspose.cells.drawing/groupshape/height_cm) | Представляет высоту фигуры в сантиметрах.|
| [left](/cells/python-net/ru/aspose.cells.drawing/groupshape/left) | Представляет горизонтальное смещение фигуры относительно ее левого столбца в пикселях.|
| [left_inch](/cells/python-net/ru/aspose.cells.drawing/groupshape/left_inch) | Представляет собой горизонтальное смещение фигуры относительно ее левого столбца в дюймах.|
| [left_cm](/cells/python-net/ru/aspose.cells.drawing/groupshape/left_cm) | Представляет собой горизонтальное смещение фигуры относительно ее левого столбца в сантиметрах.|
| [top](/cells/python-net/ru/aspose.cells.drawing/groupshape/top) | Представляет собой вертикальное смещение фигуры относительно ее верхней строки в пикселях.|
| [top_inch](/cells/python-net/ru/aspose.cells.drawing/groupshape/top_inch) | Представляет собой вертикальное смещение фигуры от ее верхней строки в дюймах.|
| [top_cm](/cells/python-net/ru/aspose.cells.drawing/groupshape/top_cm) | Представляет собой вертикальное смещение фигуры относительно ее верхней строки, в сантиметрах.|
| [top_to_corner](/cells/python-net/ru/aspose.cells.drawing/groupshape/top_to_corner) | Возвращает и задает вертикальное смещение фигуры от верхней границы листа в пикселях.|
| [left_to_corner](/cells/python-net/ru/aspose.cells.drawing/groupshape/left_to_corner) | Получает и задает горизонтальное смещение фигуры от левой границы рабочего листа.|
| [x](/cells/python-net/ru/aspose.cells.drawing/groupshape/x) | Возвращает и задает горизонтальное смещение фигуры от левой границы листа в пикселях.|
| [y](/cells/python-net/ru/aspose.cells.drawing/groupshape/y) |Возвращает и задает вертикальное смещение фигуры от верхней границы листа в пикселях.|
| [width_scale](/cells/python-net/ru/aspose.cells.drawing/groupshape/width_scale) | Получает и задает масштаб ширины в процентах от исходной ширины изображения.<br/> Если фигура не является изображением, свойство WidthScale возвращает только 100;|
| [height_scale](/cells/python-net/ru/aspose.cells.drawing/groupshape/height_scale) | Возвращает и задает масштаб высоты в процентах от исходной высоты изображения.<br/> Если фигура не является рисунком, свойство HeightScale возвращает только 100;|
| [top_in_shape](/cells/python-net/ru/aspose.cells.drawing/groupshape/top_in_shape) | Представляет собой вертикальное смещение фигуры от верхней границы родительской фигуры,<br/> в единице 1/4000 высоты родительской формы.|
| [left_in_shape](/cells/python-net/ru/aspose.cells.drawing/groupshape/left_in_shape) | Представляет собой горизонтальное смещение фигуры от левой границы родительской фигуры,<br/> в единице 1/4000 ширины родительской формы.|
| [width_in_shape](/cells/python-net/ru/aspose.cells.drawing/groupshape/width_in_shape) | Представляет ширину фигуры в единицах, равных 1/4000 родительской фигуры.|
| [height_in_shape](/cells/python-net/ru/aspose.cells.drawing/groupshape/height_in_shape) | Представляет собой вертикальное смещение фигуры от верхней границы родительской фигуры в единицах, равных 1/4000 высоты родительской фигуры.|
| [group](/cells/python-net/ru/aspose.cells.drawing/groupshape/group) | Получает групповую фигуру, содержащую данную фигуру.|
| [type](/cells/python-net/ru/aspose.cells.drawing/groupshape/type) |Получает тип автоматической фигуры.|
| [has_line](/cells/python-net/ru/aspose.cells.drawing/groupshape/has_line) | Возвращает и задает видимую границу линии фигуры.|
| [is_filled](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_filled) | Указывает, виден ли формат заполнения.|
| [is_flipped_horizontally](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_flipped_horizontally) | Получает и задает, перевернута ли фигура по горизонтали.|
| [is_flipped_vertically](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_flipped_vertically) | Получает и задает, перевернута ли фигура вертикально.|
| [actual_lower_right_row](/cells/python-net/ru/aspose.cells.drawing/groupshape/actual_lower_right_row) | Возьмите реальный нижний ряд.|
| [relative_to_original_picture_size](/cells/python-net/ru/aspose.cells.drawing/groupshape/relative_to_original_picture_size) | Указывает, соотносится ли форма с исходным размером изображения.|
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing/groupshape/linked_cell) | Возвращает или задает диапазон рабочего листа, связанный со значением элемента управления.|
| [input_range](/cells/python-net/ru/aspose.cells.drawing/groupshape/input_range) | Возвращает или задает диапазон рабочего листа, используемый для заполнения указанного поля со списком.|
| [text_shape_type](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_shape_type) | Получает и задает предустановленный тип формы текста.|
| [text_body](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_body) | Получает и задает настройки текста фигуры.|
| [font](/cells/python-net/ru/aspose.cells.drawing/groupshape/font) | Представляет шрифт формы.|
| [text_options](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_options) | Представляет текстовые параметры фигуры.|
| [text](/cells/python-net/ru/aspose.cells.drawing/groupshape/text) | Получает и задает текст этой фигуры.|
| [is_rich_text](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_rich_text) | Является ли текст форматированным текстом.|
| [html_text](/cells/python-net/ru/aspose.cells.drawing/groupshape/html_text) | Получает и задает HTML-строку, содержащую данные и некоторые форматы в этом текстовом поле.|
| [text_vertical_overflow](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_vertical_overflow) | Получает и задает тип вертикального переполнения текста для фигуры, содержащей текст.|
| [text_horizontal_overflow](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_horizontal_overflow) |Получает и задает тип горизонтального переполнения текста для фигуры, содержащей текст.|
| [is_text_wrapped](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_text_wrapped) | Получает и задает тип обтекания текстом фигуры, содержащей текст.|
| [text_orientation_type](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_orientation_type) | Получает и задает тип ориентации текста фигуры.|
| [text_horizontal_alignment](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_horizontal_alignment) | Получает и задает тип горизонтального выравнивания текста фигуры.|
| [text_vertical_alignment](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_vertical_alignment) | Получает и задает тип вертикального выравнивания текста фигуры.|
| [text_direction](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_direction) | Получает/задает направление потока текста для этого объекта.|
| [text_box_options](/cells/python-net/ru/aspose.cells.drawing/groupshape/text_box_options) | Получает текстовую информацию в форме|
| [control_data](/cells/python-net/ru/aspose.cells.drawing/groupshape/control_data) | Получает данные управления.|
| [active_x_control](/cells/python-net/ru/aspose.cells.drawing/groupshape/active_x_control) | Получает элемент управления ActiveX.|
| [paths](/cells/python-net/ru/aspose.cells.drawing/groupshape/paths) | Получает пути произвольной геометрической формы.|
| [create_id](/cells/python-net/ru/aspose.cells.drawing/groupshape/create_id) | Получает и задает идентификатор создания для этой формы.|
| [is_decorative](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_decorative) | Указывает, является ли объект декоративным.|



Получает дочернюю форму по индексу.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] | индекс формы ребенка.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`to_image(self, stream, image_type)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/to_image/#io.rawiobase-aspose.cells.drawing.imagetype) | Создает изображение фигуры и сохраняет его в потоке в указанном формате.|
| [`to_image(self, image_file, options)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Сохраняет форму в файле.|
| [`to_image(self, stream, options)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Сохраняет форму в потоке.|
| [`get_result_of_smart_art(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_result_of_smart_art/#) | Преобразование интеллектуального искусства в сгруппированные фигуры.|
| [`to_front_or_back(self, orders)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/to_front_or_back/#int) | Выводит фигуру на передний план или отодвигает её на задний план.|
| [`get_locked_property(self, type)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_locked_property/#aspose.cells.drawing.shapelocktype) | Получает значение заблокированного свойства.|
| [`set_locked_property(self, type, value)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/set_locked_property/#aspose.cells.drawing.shapelocktype-bool) | Установить заблокированное свойство.|
| [`add_hyperlink(self, address)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/add_hyperlink/#str) | Добавляет гиперссылку к форме.|
| [`remove_hyperlink(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/remove_hyperlink/#) | Удаляет гиперссылку формы.|
| [`move_to_range(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/move_to_range/#int-int-int-int) | Перемещает фигуру в указанный диапазон.|
| [`align_top_right_corner(self, top_row, right_column)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/align_top_right_corner/#int-int) | Перемещает картинку в правый верхний угол.|
| [`get_connection_points(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_connection_points/#) | Получить точки подключения|
| [`get_linked_cell(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_linked_cell/#bool-bool) | Возвращает диапазон, связанный со значением элемента управления.|
| [`set_linked_cell(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/set_linked_cell/#str-bool-bool) | Устанавливает диапазон, связанный со значением элемента управления.|
| [`get_input_range(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_input_range/#bool-bool) | Возвращает диапазон, используемый для заполнения элемента управления.|
| [`set_input_range(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/set_input_range/#str-bool-bool) | Задает диапазон, используемый для заполнения элемента управления.|
| [`update_selected_value(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/update_selected_value/#) | Обновить выбранное значение значением связанной ячейки.|
| [`calculate_text_size(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/calculate_text_size/#) | Пересчитать текстовую область|
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Форматирует некоторые символы с помощью настроек шрифта.|
| [`characters(self, start_index, length)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/characters/#int-int) |Возвращает объект Characters, представляющий диапазон символов в тексте.|
| [`get_characters(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_characters/#) | Возвращает все объекты Characters<br/>который представляет собой диапазон символов в тексте.|
| [`get_rich_formattings(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_rich_formattings/#) | Возвращает все объекты Characters<br/>который представляет собой диапазон символов в тексте.|
| [`remove_active_x_control(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/remove_active_x_control/#) | Удалить элемент управления ActiveX.|
| [`is_same_setting(self, obj)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/is_same_setting/#any) | Возвращает, одинакова ли форма.|
| [`get_actual_box(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_actual_box/#) | Получить фактическое положение и размер фигуры (после применения поворота, отражения и т. д.)|
| [`fit_to_text_size(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/fit_to_text_size/#) | Пересчитать текстовую область, подходящую для отображения всего текстового содержимого.|
| [`ungroup(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/ungroup/#) | Разгруппировывает элементы фигуры.|
| [`get_grouped_shapes(self)`](/cells/python-net/ru/aspose.cells.drawing/groupshape/get_grouped_shapes/#) | Получает фигуры, сгруппированные по этой форме.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.drawing import FillType, MsoLineDashStyle, MsoLineStyle, PlacementType
from aspose.pydrawing import Color

# Instantiate a new Workbook.
excelbook = Workbook()
# Add a group box to the first worksheet.
box = excelbook.worksheets[0].shapes.add_group_box(1, 0, 1, 0, 300, 250)
# Set the caption of the group box.
box.text = "Age Groups"
box.placement = PlacementType.FREE_FLOATING
# Make it 2-D box.
box.shadow = False
# Add a radio button.
radio1 = excelbook.worksheets[0].shapes.add_radio_button(3, 0, 2, 0, 30, 110)
# Set its text string.
radio1.text = "20-29"
# Set A1 cell as a linked cell for the radio button.
radio1.linked_cell = "A1"
# Make the radio button 3-D.
radio1.shadow = True
# Make the line format visible.
radio1.line.fill_type = FillType.SOLID
# Make the fill format visible.
radio1.fill.fill_type = FillType.SOLID
# Set the foreground color of the radio button.
radio1.fill.solid_fill.color = Color.light_green
# Set the line style of the radio button.
radio1.line.compound_type = MsoLineStyle.THICK_THIN
# Set the weight of the radio button.
radio1.line.weight = 4.0
# Set the line color of the radio button.
radio1.line.solid_fill.color = Color.blue
# Set the dash style of the radio button.
radio1.line.dash_style = MsoLineDashStyle.SOLID
# Add another radio button.
radio2 = excelbook.worksheets[0].shapes.add_radio_button(6, 0, 2, 0, 30, 110)
# Set its text string.
radio2.text = "30-39"
# Set A1 cell as a linked cell for the radio button.
radio2.linked_cell = "A1"
# Make the radio button 3-D.
radio2.shadow = True
# Make the line format visible.
radio2.line.fill_type = FillType.SOLID
# Make the fill format visible.
radio2.fill.fill_type = FillType.SOLID
# Set the foreground color of the radio button.
radio2.fill.solid_fill.color = Color.light_green
# Set the line style of the radio button.
radio2.line.compound_type = MsoLineStyle.THICK_THIN
# Set the weight of the radio button.
radio2.line.weight = 4.0
# Set the line color of the radio button.
radio2.line.solid_fill.color = Color.blue
# Set the dash style of the radio button.
radio2.line.dash_style = MsoLineDashStyle.SOLID
# Add another radio button.
radio3 = excelbook.worksheets[0].shapes.add_radio_button(9, 0, 2, 0, 30, 110)
# Set its text string.
radio3.text = "40-49"
# Set A1 cell as a linked cell for the radio button.
radio3.linked_cell = "A1"
# Make the radio button 3-D.
radio3.shadow = True
# Make the line format visible.
radio3.line.fill_type = FillType.SOLID
# Make the fill format visible.
radio3.fill.fill_type = FillType.SOLID
# Set the foreground color of the radio button.
radio3.fill.solid_fill.color = Color.light_green
# Set the line style of the radio button.
radio3.line.compound_type = MsoLineStyle.THICK_THIN
# Set the weight of the radio button.
radio3.line.weight = 4.0
# Set the line color of the radio button.
radio3.line.solid_fill.color = Color.blue
# Set the dash style of the radio button.
radio3.line.dash_style = MsoLineDashStyle.SOLID
# Get the shapes.
shapeobjects = [box, radio1, radio2, radio3]
# Group the shapes.
group = excelbook.worksheets[0].shapes.group(shapeobjects)
# Save the excel file.
excelbook.save("groupshapes.xls")

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`GlowEffect`](/cells/python-net/ru/aspose.cells.drawing/gloweffect)
* класс [`GroupShape`](/cells/python-net/ru/aspose.cells.drawing/groupshape)
* класс [`ReflectionEffect`](/cells/python-net/ru/aspose.cells.drawing/reflectioneffect)
* класс [`ShadowEffect`](/cells/python-net/ru/aspose.cells.drawing/shadoweffect)
* класс [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)
