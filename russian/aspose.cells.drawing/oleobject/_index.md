---
title: OleObject класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 380
url: /ru/aspose.cells.drawing/oleobject/
is_root: false
---
##  OleObject класс
Представляет число OleObject на рабочем листе.



**Наследование:** [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject) → 
[`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)



Тип OleObject предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [macro_name](/cells/python-net/ru/aspose.cells.drawing/oleobject/macro_name) | Получает и задает имя макроса.|
| [is_equation](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_equation) | Указывает, содержит ли форма только уравнение.|
| [is_smart_art](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_smart_art) | Указывает, является ли фигура интеллектуальным искусством.|
| [z_order_position](/cells/python-net/ru/aspose.cells.drawing/oleobject/z_order_position) | Возвращает положение фигуры в z-порядке.|
| [name](/cells/python-net/ru/aspose.cells.drawing/oleobject/name) | Получает и задает имя фигуры.|
| [alternative_text](/cells/python-net/ru/aspose.cells.drawing/oleobject/alternative_text) | Возвращает или задает описательную (альтернативную) текстовую строку объекта [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape).|
| [title](/cells/python-net/ru/aspose.cells.drawing/oleobject/title) | Задает заголовок (подпись) текущего объекта формы.|
| [line_format](/cells/python-net/ru/aspose.cells.drawing/oleobject/line_format) | Возвращает объект MsoLineFormat, содержащий свойства форматирования линии для указанной фигуры.|
| [fill_format](/cells/python-net/ru/aspose.cells.drawing/oleobject/fill_format) | Возвращает объект MsoFillFormat, содержащий свойства форматирования заливки для указанной фигуры.|
| [line](/cells/python-net/ru/aspose.cells.drawing/oleobject/line) | Получает стиль линии|
| [fill](/cells/python-net/ru/aspose.cells.drawing/oleobject/fill) | Возвращает объект [`Shape.fill_format`](/cells/python-net/ru/aspose.cells.drawing/shape#fill_format), содержащий свойства форматирования заливки для указанной фигуры.|
| [shadow_effect](/cells/python-net/ru/aspose.cells.drawing/oleobject/shadow_effect) | Представляет объект [`ShadowEffect`](/cells/python-net/ru/aspose.cells.drawing/shadoweffect), который задает эффект тени для элемента или фигуры диаграммы.|
| [reflection](/cells/python-net/ru/aspose.cells.drawing/oleobject/reflection) |Представляет объект [`ReflectionEffect`](/cells/python-net/ru/aspose.cells.drawing/reflectioneffect), который задает эффект отражения для элемента или фигуры диаграммы.|
| [glow](/cells/python-net/ru/aspose.cells.drawing/oleobject/glow) | Представляет объект [`GlowEffect`](/cells/python-net/ru/aspose.cells.drawing/gloweffect), который задает эффект свечения для элемента или фигуры диаграммы.|
| [soft_edges](/cells/python-net/ru/aspose.cells.drawing/oleobject/soft_edges) | Получает и задает радиус размытия, применяемый к краям, в точках.|
| [three_d_format](/cells/python-net/ru/aspose.cells.drawing/oleobject/three_d_format) | Получает и задает 3D-формат фигуры.|
| [format_picture](/cells/python-net/ru/aspose.cells.drawing/oleobject/format_picture) | Получает и задает параметры формата изображения.|
| [is_hidden](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_hidden) | Указывает, виден ли объект.|
| [is_lock_aspect_ratio](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_lock_aspect_ratio) | True означает, что соотношение сторон фигуры зафиксировано.|
| [is_aspect_ratio_locked](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_aspect_ratio_locked) | True означает, что соотношение сторон фигуры зафиксировано.|
| [rotation_angle](/cells/python-net/ru/aspose.cells.drawing/oleobject/rotation_angle) | Получает и задает поворот фигуры.|
| [hyperlink](/cells/python-net/ru/aspose.cells.drawing/oleobject/hyperlink) | Получает гиперссылку формы.|
| [id](/cells/python-net/ru/aspose.cells.drawing/oleobject/id) | Получает идентификатор этой формы.|
| [spid](/cells/python-net/ru/aspose.cells.drawing/oleobject/spid) | Указывает необязательный строковый идентификатор, который приложение может использовать для идентификации конкретной фигуры.|
| [spt](/cells/python-net/ru/aspose.cells.drawing/oleobject/spt) | Указывает необязательное число, которое приложение может использовать для связи конкретной фигуры с определенным типом фигуры.|
| [worksheet](/cells/python-net/ru/aspose.cells.drawing/oleobject/worksheet) | Получает объект [`Shape.worksheet`](/cells/python-net/ru/aspose.cells.drawing/shape#worksheet), содержащий эту форму.|
| [is_group](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_group) | Указывает, является ли данная фигура групповой фигурой.|
| [is_in_group](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_in_group) | Указывает, сгруппирована ли фигура.|
| [is_word_art](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_word_art) |Указывает, является ли данная форма произведением искусства.|
| [text_effect](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_effect) | Возвращает объект TextEffectFormat, содержащий свойства форматирования текста для указанной фигуры.<br/> Применяется к объектам Shape, представляющим WordArt.|
| [is_locked](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_locked) | True означает, что объект не может быть изменен, если лист защищен.<br/> Обратите внимание, что это значение имеет смысл только в том случае, если рабочий лист или объекты на нем защищены.|
| [is_printable](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_printable) | Указывает, можно ли распечатать объект.<br/> Если False, эта форма не будет напечатана при печати.|
| [mso_drawing_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/mso_drawing_type) | Получает тип чертежа.|
| [auto_shape_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/auto_shape_type) | Получает и задает тип автоматической фигуры.|
| [anchor_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/anchor_type) | Получает и задает тип заполнителя якоря формы.|
| [placement](/cells/python-net/ru/aspose.cells.drawing/oleobject/placement) | Представляет собой способ присоединения объекта рисунка к ячейкам под ним.<br/> Свойство управляет размещением объекта на рабочем листе.|
| [upper_left_row](/cells/python-net/ru/aspose.cells.drawing/oleobject/upper_left_row) | Представляет индекс верхней строки.|
| [upper_delta_y](/cells/python-net/ru/aspose.cells.drawing/oleobject/upper_delta_y) | Возвращает или задает вертикальное смещение фигуры от ее верхней левой угловой строки.|
| [upper_left_column](/cells/python-net/ru/aspose.cells.drawing/oleobject/upper_left_column) | Представляет индекс столбца в левом верхнем углу.|
| [upper_delta_x](/cells/python-net/ru/aspose.cells.drawing/oleobject/upper_delta_x) |Возвращает или задает горизонтальное смещение фигуры от ее верхнего левого углового столбца.|
| [lower_right_row](/cells/python-net/ru/aspose.cells.drawing/oleobject/lower_right_row) | Представляет индекс строки в нижнем правом углу.|
| [lower_delta_y](/cells/python-net/ru/aspose.cells.drawing/oleobject/lower_delta_y) | Возвращает или задает вертикальное смещение фигуры от ее нижнего правого угла.|
| [lower_right_column](/cells/python-net/ru/aspose.cells.drawing/oleobject/lower_right_column) | Представляет индекс столбца в правом нижнем углу.|
| [lower_delta_x](/cells/python-net/ru/aspose.cells.drawing/oleobject/lower_delta_x) | Возвращает или задает горизонтальное смещение фигуры от ее нижнего правого углового столбца.|
| [right](/cells/python-net/ru/aspose.cells.drawing/oleobject/right) | Представляет ширину горизонтального смещения фигуры от ее нижнего правого углового столбца в пикселях.|
| [bottom](/cells/python-net/ru/aspose.cells.drawing/oleobject/bottom) | Представляет ширину вертикального смещения фигуры от ее нижнего нижнего угла в пикселях.|
| [width](/cells/python-net/ru/aspose.cells.drawing/oleobject/width) | Представляет ширину фигуры в пикселях.|
| [width_inch](/cells/python-net/ru/aspose.cells.drawing/oleobject/width_inch) | Представляет ширину фигуры в дюймах.|
| [width_pt](/cells/python-net/ru/aspose.cells.drawing/oleobject/width_pt) | Представляет ширину фигуры в точках.|
| [width_cm](/cells/python-net/ru/aspose.cells.drawing/oleobject/width_cm) | Представляет ширину фигуры в сантиметрах.|
| [height](/cells/python-net/ru/aspose.cells.drawing/oleobject/height) | Представляет высоту фигуры в пикселях.|
| [height_inch](/cells/python-net/ru/aspose.cells.drawing/oleobject/height_inch) | Представляет высоту фигуры в дюймах.|
| [height_pt](/cells/python-net/ru/aspose.cells.drawing/oleobject/height_pt) |Представляет высоту фигуры в точках.|
| [height_cm](/cells/python-net/ru/aspose.cells.drawing/oleobject/height_cm) | Представляет высоту фигуры в сантиметрах.|
| [left](/cells/python-net/ru/aspose.cells.drawing/oleobject/left) | Представляет горизонтальное смещение фигуры относительно ее левого столбца в пикселях.|
| [left_inch](/cells/python-net/ru/aspose.cells.drawing/oleobject/left_inch) | Представляет собой горизонтальное смещение фигуры относительно ее левого столбца в дюймах.|
| [left_cm](/cells/python-net/ru/aspose.cells.drawing/oleobject/left_cm) | Представляет собой горизонтальное смещение фигуры относительно ее левого столбца в сантиметрах.|
| [top](/cells/python-net/ru/aspose.cells.drawing/oleobject/top) | Представляет собой вертикальное смещение фигуры относительно ее верхней строки в пикселях.|
| [top_inch](/cells/python-net/ru/aspose.cells.drawing/oleobject/top_inch) | Представляет собой вертикальное смещение фигуры от ее верхней строки в дюймах.|
| [top_cm](/cells/python-net/ru/aspose.cells.drawing/oleobject/top_cm) | Представляет собой вертикальное смещение фигуры относительно ее верхней строки, в сантиметрах.|
| [top_to_corner](/cells/python-net/ru/aspose.cells.drawing/oleobject/top_to_corner) | Возвращает и задает вертикальное смещение фигуры от верхней границы листа в пикселях.|
| [left_to_corner](/cells/python-net/ru/aspose.cells.drawing/oleobject/left_to_corner) | Получает и задает горизонтальное смещение фигуры от левой границы рабочего листа.|
| [x](/cells/python-net/ru/aspose.cells.drawing/oleobject/x) | Возвращает и задает горизонтальное смещение фигуры от левой границы листа в пикселях.|
| [y](/cells/python-net/ru/aspose.cells.drawing/oleobject/y) |Возвращает и задает вертикальное смещение фигуры от верхней границы листа в пикселях.|
| [width_scale](/cells/python-net/ru/aspose.cells.drawing/oleobject/width_scale) | Получает и задает масштаб ширины в процентах от исходной ширины изображения.<br/> Если фигура не является изображением, свойство WidthScale возвращает только 100;|
| [height_scale](/cells/python-net/ru/aspose.cells.drawing/oleobject/height_scale) | Возвращает и задает масштаб высоты в процентах от исходной высоты изображения.<br/> Если фигура не является рисунком, свойство HeightScale возвращает только 100;|
| [top_in_shape](/cells/python-net/ru/aspose.cells.drawing/oleobject/top_in_shape) | Представляет собой вертикальное смещение фигуры от верхней границы родительской фигуры,<br/> в единице 1/4000 высоты родительской формы.|
| [left_in_shape](/cells/python-net/ru/aspose.cells.drawing/oleobject/left_in_shape) | Представляет собой горизонтальное смещение фигуры от левой границы родительской фигуры,<br/> в единице 1/4000 ширины родительской формы.|
| [width_in_shape](/cells/python-net/ru/aspose.cells.drawing/oleobject/width_in_shape) | Представляет ширину фигуры в единицах, равных 1/4000 родительской фигуры.|
| [height_in_shape](/cells/python-net/ru/aspose.cells.drawing/oleobject/height_in_shape) | Представляет собой вертикальное смещение фигуры от верхней границы родительской фигуры в единицах, равных 1/4000 высоты родительской фигуры.|
| [group](/cells/python-net/ru/aspose.cells.drawing/oleobject/group) | Получает групповую фигуру, содержащую данную фигуру.|
| [type](/cells/python-net/ru/aspose.cells.drawing/oleobject/type) |Получает тип автоматической фигуры.|
| [has_line](/cells/python-net/ru/aspose.cells.drawing/oleobject/has_line) | Возвращает и задает видимую границу линии фигуры.|
| [is_filled](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_filled) | Указывает, виден ли формат заполнения.|
| [is_flipped_horizontally](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_flipped_horizontally) | Получает и задает, перевернута ли фигура по горизонтали.|
| [is_flipped_vertically](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_flipped_vertically) | Получает и задает, перевернута ли фигура вертикально.|
| [actual_lower_right_row](/cells/python-net/ru/aspose.cells.drawing/oleobject/actual_lower_right_row) | Возьмите реальный нижний ряд.|
| [relative_to_original_picture_size](/cells/python-net/ru/aspose.cells.drawing/oleobject/relative_to_original_picture_size) | Указывает, соотносится ли форма с исходным размером изображения.|
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing/oleobject/linked_cell) | Возвращает или задает диапазон рабочего листа, связанный со значением элемента управления.|
| [input_range](/cells/python-net/ru/aspose.cells.drawing/oleobject/input_range) | Возвращает или задает диапазон рабочего листа, используемый для заполнения указанного поля со списком.|
| [text_shape_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_shape_type) | Получает и задает предустановленный тип формы текста.|
| [text_body](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_body) | Получает и задает настройки текста фигуры.|
| [font](/cells/python-net/ru/aspose.cells.drawing/oleobject/font) | Представляет шрифт формы.|
| [text_options](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_options) | Представляет текстовые параметры фигуры.|
| [text](/cells/python-net/ru/aspose.cells.drawing/oleobject/text) | Получает и задает текст этой фигуры.|
| [is_rich_text](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_rich_text) | Является ли текст форматированным текстом.|
| [html_text](/cells/python-net/ru/aspose.cells.drawing/oleobject/html_text) | Получает и задает HTML-строку, содержащую данные и некоторые форматы в этом текстовом поле.|
| [text_vertical_overflow](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_vertical_overflow) | Получает и задает тип вертикального переполнения текста для фигуры, содержащей текст.|
| [text_horizontal_overflow](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_horizontal_overflow) |Получает и задает тип горизонтального переполнения текста для фигуры, содержащей текст.|
| [is_text_wrapped](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_text_wrapped) | Получает и задает тип обтекания текстом фигуры, содержащей текст.|
| [text_orientation_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_orientation_type) | Получает и задает тип ориентации текста фигуры.|
| [text_horizontal_alignment](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_horizontal_alignment) | Получает и задает тип горизонтального выравнивания текста фигуры.|
| [text_vertical_alignment](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_vertical_alignment) | Получает и задает тип вертикального выравнивания текста фигуры.|
| [text_direction](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_direction) | Получает/задает направление потока текста для этого объекта.|
| [text_box_options](/cells/python-net/ru/aspose.cells.drawing/oleobject/text_box_options) | Получает текстовую информацию в форме|
| [control_data](/cells/python-net/ru/aspose.cells.drawing/oleobject/control_data) | Получает данные управления.|
| [active_x_control](/cells/python-net/ru/aspose.cells.drawing/oleobject/active_x_control) | Получает элемент управления ActiveX.|
| [paths](/cells/python-net/ru/aspose.cells.drawing/oleobject/paths) | Получает пути произвольной геометрической формы.|
| [create_id](/cells/python-net/ru/aspose.cells.drawing/oleobject/create_id) | Получает и задает идентификатор создания для этой формы.|
| [is_decorative](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_decorative) | Указывает, является ли объект декоративным.|
| [is_auto_size](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_auto_size) | True указывает, что размер OLE-объекта будет автоматически изменен в соответствии с размером снимка встроенного содержимого.<br/> когда активируется старый объект.|
| [is_link](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_link) | Возвращает true, если OleObject ссылается на файл.|
| [display_as_icon](/cells/python-net/ru/aspose.cells.drawing/oleobject/display_as_icon) | True, если указанный объект отображается как значок<br/> и изображение не будет автоматически изменено.|
| [image_data](/cells/python-net/ru/aspose.cells.drawing/oleobject/image_data) | Представляет изображение объекта OLE в виде массива байтов.|
| [object_data](/cells/python-net/ru/aspose.cells.drawing/oleobject/object_data) | Представляет встроенные данные OLE-объекта в виде массива байтов.|
| [full_object_bin](/cells/python-net/ru/aspose.cells.drawing/oleobject/full_object_bin) | Получает полные встроенные двоичные данные OLE-объекта в файле шаблона.|
| [image_source_full_name](/cells/python-net/ru/aspose.cells.drawing/oleobject/image_source_full_name) |Возвращает или задает путь и имя исходного файла для связанного изображения.|
| [prog_id](/cells/python-net/ru/aspose.cells.drawing/oleobject/prog_id) | Получает или задает ProgID объекта OLE.|
| [file_format_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/file_format_type) | Получает и задает тип файла данных встроенного OLE-объекта|
| [object_source_full_name](/cells/python-net/ru/aspose.cells.drawing/oleobject/object_source_full_name) | Возвращает полное имя исходного файла для связанного объекта OLE.|
| [label](/cells/python-net/ru/aspose.cells.drawing/oleobject/label) | Получает и задает отображаемую метку связанного OLE-объекта.|
| [source_full_name](/cells/python-net/ru/aspose.cells.drawing/oleobject/source_full_name) | Возвращает полное имя исходного файла для связанного объекта OLE.|
| [auto_update](/cells/python-net/ru/aspose.cells.drawing/oleobject/auto_update) | Указывает, будет ли ссылка на OleObject обновляться автоматически или нет.|
| [auto_load](/cells/python-net/ru/aspose.cells.drawing/oleobject/auto_load) | Указывает, будет ли вызываться хост-приложение для загрузки встроенного объекта<br/> данные объекта автоматически при открытии родительской книги.|
| [class_identifier](/cells/python-net/ru/aspose.cells.drawing/oleobject/class_identifier) | Получает и задает идентификатор класса внедренного объекта.<br/> Это означает, какое приложение открывает встроенный файл.|
| [image_type](/cells/python-net/ru/aspose.cells.drawing/oleobject/image_type) | Получает формат изображения объекта OLE.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`to_image(self, stream, image_type)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/to_image/#io.rawiobase-aspose.cells.drawing.imagetype) | Создает изображение фигуры и сохраняет его в потоке в указанном формате.|
| [`to_image(self, image_file, options)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Сохраняет форму в файле.|
| [`to_image(self, stream, options)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Сохраняет форму в потоке.|
| [`set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/set_embedded_object/#bool-bytes-str-bool-str) | Устанавливает данные встроенного объекта.|
| [`set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/set_embedded_object/#bool-bytes-str-bool-str-bool) | Устанавливает данные встроенного объекта.|
| [`get_result_of_smart_art(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_result_of_smart_art/#) | Преобразование интеллектуального искусства в сгруппированные фигуры.|
| [`to_front_or_back(self, orders)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/to_front_or_back/#int) | Выводит фигуру на передний план или отодвигает её на задний план.|
| [`get_locked_property(self, type)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_locked_property/#aspose.cells.drawing.shapelocktype) | Получает значение заблокированного свойства.|
| [`set_locked_property(self, type, value)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/set_locked_property/#aspose.cells.drawing.shapelocktype-bool) | Установить заблокированное свойство.|
| [`add_hyperlink(self, address)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/add_hyperlink/#str) | Добавляет гиперссылку к форме.|
| [`remove_hyperlink(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/remove_hyperlink/#) | Удаляет гиперссылку формы.|
| [`move_to_range(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/move_to_range/#int-int-int-int) | Перемещает фигуру в указанный диапазон.|
| [`align_top_right_corner(self, top_row, right_column)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/align_top_right_corner/#int-int) | Перемещает картинку в правый верхний угол.|
| [`get_connection_points(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_connection_points/#) | Получить точки подключения|
| [`get_linked_cell(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_linked_cell/#bool-bool) | Возвращает диапазон, связанный со значением элемента управления.|
| [`set_linked_cell(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/set_linked_cell/#str-bool-bool) | Устанавливает диапазон, связанный со значением элемента управления.|
| [`get_input_range(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_input_range/#bool-bool) | Возвращает диапазон, используемый для заполнения элемента управления.|
| [`set_input_range(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/set_input_range/#str-bool-bool) | Задает диапазон, используемый для заполнения элемента управления.|
| [`update_selected_value(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/update_selected_value/#) | Обновить выбранное значение значением связанной ячейки.|
| [`calculate_text_size(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/calculate_text_size/#) | Пересчитать текстовую область|
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Форматирует некоторые символы с помощью настроек шрифта.|
| [`characters(self, start_index, length)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/characters/#int-int) |Возвращает объект Characters, представляющий диапазон символов в тексте.|
| [`get_characters(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_characters/#) | Возвращает все объекты Characters<br/>который представляет собой диапазон символов в тексте.|
| [`get_rich_formattings(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_rich_formattings/#) | Возвращает все объекты Characters<br/>который представляет собой диапазон символов в тексте.|
| [`remove_active_x_control(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/remove_active_x_control/#) | Удалить элемент управления ActiveX.|
| [`is_same_setting(self, obj)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/is_same_setting/#any) | Возвращает, одинакова ли форма.|
| [`get_actual_box(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/get_actual_box/#) | Получить фактическое положение и размер фигуры (после применения поворота, отражения и т. д.)|
| [`fit_to_text_size(self)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/fit_to_text_size/#) | Пересчитать текстовую область, подходящую для отображения всего текстового содержимого.|
| [`set_native_source_full_name(self, source_full_name)`](/cells/python-net/ru/aspose.cells.drawing/oleobject/set_native_source_full_name/#str) | Задает полное имя исходного файла с путем к нему.|



###  Пример

```python
from aspose.cells import Workbook
import bytearray

# Instantiate a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Define a string variable to store the image path.
ImageUrl = "school.jpg"
# Get the picture into the streams.
fs = open(ImageUrl, "rb")
# Define a byte array.
imageData = bytearray(utils.filesize(fs))
# Obtain the picture into the array of bytes from streams.
fs.readinto(imageData)
# Close the stream.
fs.close()
# Get an excel file path in a variable.
path = "Book1.xls"
# Get the file into the streams.
fs = open(path, "rb")
# Define an array of bytes.
objectData = bytearray(utils.filesize(fs))
# Store the file from streams.
fs.readinto(objectData)
# Close the stream.
fs.close()
# Add an Ole object into the worksheet with the image
# shown in MS Excel.
sheet.ole_objects.add(14, 3, 200, 220, imageData)
# Set embedded ole object data.
sheet.ole_objects[0].object_data = objectData
# Save the excel file
workbook.save(r"oleobjects.xls")

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`GlowEffect`](/cells/python-net/ru/aspose.cells.drawing/gloweffect)
* класс [`OleObject`](/cells/python-net/ru/aspose.cells.drawing/oleobject)
* класс [`ReflectionEffect`](/cells/python-net/ru/aspose.cells.drawing/reflectioneffect)
* класс [`ShadowEffect`](/cells/python-net/ru/aspose.cells.drawing/shadoweffect)
* класс [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)
