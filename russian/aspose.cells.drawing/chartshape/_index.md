---
title: ChartShape класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 80
url: /ru/aspose.cells.drawing/chartshape/
is_root: false
---
##  ChartShape класс
Представляет форму диаграммы.
Свойства и методы объекта ChartObject управляют внешним видом и размером встроенной диаграммы на листе.



**Наследование:** [`ChartShape`](/cells/python-net/aspose.cells.drawing/chartshape) → 
[`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)



Тип ChartShape предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [macro_name](/cells/python-net/ru/aspose.cells.drawing/chartshape/macro_name) | Получает и задает имя макроса.|
| [is_equation](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_equation) | Указывает, содержит ли фигура только уравнение.|
| [is_smart_art](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_smart_art) | Указывает, является ли фигура интеллектуальным искусством.|
| [z_order_position](/cells/python-net/ru/aspose.cells.drawing/chartshape/z_order_position) | Возвращает положение фигуры в z-порядке.|
| [name](/cells/python-net/ru/aspose.cells.drawing/chartshape/name) | Получает и задает имя фигуры.|
| [alternative_text](/cells/python-net/ru/aspose.cells.drawing/chartshape/alternative_text) | Возвращает или задает описательную (альтернативную) текстовую строку объекта [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape).|
| [title](/cells/python-net/ru/aspose.cells.drawing/chartshape/title) | Указывает заголовок (заголовок) текущего объекта фигуры.|
| [line_format](/cells/python-net/ru/aspose.cells.drawing/chartshape/line_format) |Возвращает объект MsoLineFormat, содержащий свойства форматирования строк для указанной фигуры.|
| [fill_format](/cells/python-net/ru/aspose.cells.drawing/chartshape/fill_format) | Возвращает объект MsoFillFormat, содержащий свойства форматирования заливки для указанной фигуры.|
| [line](/cells/python-net/ru/aspose.cells.drawing/chartshape/line) | Получает стиль линии|
| [fill](/cells/python-net/ru/aspose.cells.drawing/chartshape/fill) | Возвращает объект [`Shape.fill_format`](/cells/python-net/ru/aspose.cells.drawing/shape#fill_format), содержащий свойства форматирования заливки для указанной фигуры.|
| [shadow_effect](/cells/python-net/ru/aspose.cells.drawing/chartshape/shadow_effect) | Представляет объект [`ShadowEffect`](/cells/python-net/ru/aspose.cells.drawing/shadoweffect), задающий эффект тени для элемента или фигуры диаграммы.|
| [reflection](/cells/python-net/ru/aspose.cells.drawing/chartshape/reflection) | Представляет объект [`ReflectionEffect`](/cells/python-net/ru/aspose.cells.drawing/reflectioneffect), задающий эффект отражения для элемента или фигуры диаграммы.|
| [glow](/cells/python-net/ru/aspose.cells.drawing/chartshape/glow) | Представляет объект [`GlowEffect`](/cells/python-net/ru/aspose.cells.drawing/gloweffect), который задает эффект свечения для элемента или фигуры диаграммы.|
| [soft_edges](/cells/python-net/ru/aspose.cells.drawing/chartshape/soft_edges) | Получает и задает радиус размытия, применяемый к краям, в точках.|
| [three_d_format](/cells/python-net/ru/aspose.cells.drawing/chartshape/three_d_format) | Получает и устанавливает 3D-формат фигуры.|
| [text_frame](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_frame) | Возвращает объект TextFrame, содержащий свойства выравнивания и привязки для указанной фигуры.|
| [format_picture](/cells/python-net/ru/aspose.cells.drawing/chartshape/format_picture) | Получает и задает параметры формата изображения.|
| [is_hidden](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_hidden) | Указывает, виден ли объект.|
| [is_lock_aspect_ratio](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_lock_aspect_ratio) |True означает, что изменение соотношения сторон запрещено.|
| [rotation_angle](/cells/python-net/ru/aspose.cells.drawing/chartshape/rotation_angle) | Получает и задает вращение фигуры.|
| [hyperlink](/cells/python-net/ru/aspose.cells.drawing/chartshape/hyperlink) | Получает гиперссылку фигуры.|
| [id](/cells/python-net/ru/aspose.cells.drawing/chartshape/id) | Получает идентификатор этой фигуры.|
| [spid](/cells/python-net/ru/aspose.cells.drawing/chartshape/spid) | Указывает необязательную строку, которую приложение может использовать для идентификации конкретной фигуры.|
| [spt](/cells/python-net/ru/aspose.cells.drawing/chartshape/spt) | Указывает необязательный номер, который приложение может использовать для связи конкретной фигуры с определенным типом фигуры.|
| [worksheet](/cells/python-net/ru/aspose.cells.drawing/chartshape/worksheet) | Получает объект [`Shape.worksheet`](/cells/python-net/ru/aspose.cells.drawing/shape#worksheet), содержащий эту фигуру.|
| [is_group](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_group) | Указывает, является ли фигура группой.|
| [is_in_group](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_in_group) | Указывает, сгруппирована ли фигура.|
| [is_word_art](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_word_art) | Указывает, является ли эта фигура художественным текстом.|
| [text_effect](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_effect) | Возвращает объект TextEffectFormat, содержащий свойства форматирования текстового эффекта для указанной фигуры.<br/> Применяется к объектам Shape, представляющим WordArt.|
| [is_locked](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_locked) | True, если объект заблокирован, False, если объект можно изменить, когда лист защищен.|
| [is_printable](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_printable) | True, если объект можно распечатать|
| [mso_drawing_type](/cells/python-net/ru/aspose.cells.drawing/chartshape/mso_drawing_type) | Получает тип чертежа MSO.|
| [auto_shape_type](/cells/python-net/ru/aspose.cells.drawing/chartshape/auto_shape_type) | Получает и задает тип автоматической фигуры.|
| [anchor_type](/cells/python-net/ru/aspose.cells.drawing/chartshape/anchor_type) |Получает и задает заполнитель привязки формы.|
| [placement](/cells/python-net/ru/aspose.cells.drawing/chartshape/placement) | Представляет способ прикрепления объекта рисования к ячейкам под ним.<br/> Свойство управляет размещением объекта на листе.|
| [upper_left_row](/cells/python-net/ru/aspose.cells.drawing/chartshape/upper_left_row) | Представляет индекс строки в верхнем левом углу.|
| [upper_delta_y](/cells/python-net/ru/aspose.cells.drawing/chartshape/upper_delta_y) | Получает или задает вертикальное смещение фигуры от ее верхнего левого угла.|
| [upper_left_column](/cells/python-net/ru/aspose.cells.drawing/chartshape/upper_left_column) | Представляет индекс столбца в верхнем левом углу.|
| [upper_delta_x](/cells/python-net/ru/aspose.cells.drawing/chartshape/upper_delta_x) | Получает или задает горизонтальное смещение фигуры от ее верхнего левого углового столбца.|
| [lower_right_row](/cells/python-net/ru/aspose.cells.drawing/chartshape/lower_right_row) | Представляет индекс строки в правом нижнем углу.|
| [lower_delta_y](/cells/python-net/ru/aspose.cells.drawing/chartshape/lower_delta_y) | Получает или задает вертикальное смещение фигуры от ее нижнего правого угла.|
| [lower_right_column](/cells/python-net/ru/aspose.cells.drawing/chartshape/lower_right_column) | Представляет индекс столбца в правом нижнем углу.|
| [lower_delta_x](/cells/python-net/ru/aspose.cells.drawing/chartshape/lower_delta_x) | Получает или задает горизонтальное смещение фигуры от ее нижнего правого углового столбца.|
| [right](/cells/python-net/ru/aspose.cells.drawing/chartshape/right) | Представляет ширину горизонтального смещения фигуры от ее нижнего правого углового столбца в пикселях.|
| [bottom](/cells/python-net/ru/aspose.cells.drawing/chartshape/bottom) | Представляет ширину вертикального смещения фигуры от нижнего нижнего угла строки в пикселях.|
| [width](/cells/python-net/ru/aspose.cells.drawing/chartshape/width) |Представляет ширину фигуры в пикселях.|
| [width_inch](/cells/python-net/ru/aspose.cells.drawing/chartshape/width_inch) | Представляет ширину фигуры в дюймах.|
| [width_pt](/cells/python-net/ru/aspose.cells.drawing/chartshape/width_pt) | Представляет ширину фигуры в точках.|
| [width_cm](/cells/python-net/ru/aspose.cells.drawing/chartshape/width_cm) | Представляет ширину фигуры в сантиметрах.|
| [height](/cells/python-net/ru/aspose.cells.drawing/chartshape/height) | Представляет высоту фигуры в пикселях.|
| [height_inch](/cells/python-net/ru/aspose.cells.drawing/chartshape/height_inch) | Представляет высоту фигуры в дюймах.|
| [height_pt](/cells/python-net/ru/aspose.cells.drawing/chartshape/height_pt) | Представляет высоту фигуры в точках.|
| [height_cm](/cells/python-net/ru/aspose.cells.drawing/chartshape/height_cm) | Представляет высоту фигуры в сантиметрах.|
| [left](/cells/python-net/ru/aspose.cells.drawing/chartshape/left) | Представляет горизонтальное смещение фигуры от ее левого столбца в пикселях.|
| [left_inch](/cells/python-net/ru/aspose.cells.drawing/chartshape/left_inch) | Представляет горизонтальное смещение фигуры от ее левого столбца в дюймах.|
| [left_cm](/cells/python-net/ru/aspose.cells.drawing/chartshape/left_cm) | Представляет горизонтальное смещение фигуры от ее левого столбца в сантиметрах.|
| [top](/cells/python-net/ru/aspose.cells.drawing/chartshape/top) | Представляет вертикальное смещение фигуры от ее верхнего ряда в пикселях.|
| [top_inch](/cells/python-net/ru/aspose.cells.drawing/chartshape/top_inch) | Представляет вертикальное смещение фигуры от ее верхнего ряда в дюймах.|
| [top_cm](/cells/python-net/ru/aspose.cells.drawing/chartshape/top_cm) |Представляет вертикальное смещение фигуры от ее верхнего ряда в сантиметрах.|
| [top_to_corner](/cells/python-net/ru/aspose.cells.drawing/chartshape/top_to_corner) | Получает и задает вертикальное смещение фигуры от верхней границы листа в пикселях.|
| [left_to_corner](/cells/python-net/ru/aspose.cells.drawing/chartshape/left_to_corner) | Получает и задает горизонтальное смещение фигуры от левой границы листа.|
| [x](/cells/python-net/ru/aspose.cells.drawing/chartshape/x) | Получает и задает горизонтальное смещение фигуры от левой границы листа в пикселях.|
| [y](/cells/python-net/ru/aspose.cells.drawing/chartshape/y) | Получает и задает вертикальное смещение фигуры от верхней границы листа в пикселях.|
| [width_scale](/cells/python-net/ru/aspose.cells.drawing/chartshape/width_scale) | Получает и задает масштаб ширины в процентах от ширины исходного изображения.<br/> Если фигура не является изображением, свойство WidthScale возвращает только 100;|
| [height_scale](/cells/python-net/ru/aspose.cells.drawing/chartshape/height_scale) | Получает и задает шкалу высоты в процентах от высоты исходного изображения.<br/> Если фигура не является изображением, свойство HeightScale возвращает только 100;|
| [top_in_shape](/cells/python-net/ru/aspose.cells.drawing/chartshape/top_in_shape) | Представляет вертикальное смещение фигуры от верхней границы родительской фигуры.<br/> в единице 1/4000 высоты родительской фигуры.|
| [left_in_shape](/cells/python-net/ru/aspose.cells.drawing/chartshape/left_in_shape) |Представляет горизонтальное смещение фигуры от левой границы родительской фигуры.<br/> в единице 1/4000 ширины родительской фигуры.|
| [width_in_shape](/cells/python-net/ru/aspose.cells.drawing/chartshape/width_in_shape) | Представляет ширину фигуры в единицах 1/4000 родительской фигуры.|
| [height_in_shape](/cells/python-net/ru/aspose.cells.drawing/chartshape/height_in_shape) | Представляет вертикальное смещение фигуры от верхней границы родительской фигуры в единицах 1/4000 высоты родительской фигуры.|
| [group](/cells/python-net/ru/aspose.cells.drawing/chartshape/group) | Получает фигуру группы, содержащую эту фигуру.|
| [type](/cells/python-net/ru/aspose.cells.drawing/chartshape/type) | Получает тип автоматической фигуры.|
| [has_line](/cells/python-net/ru/aspose.cells.drawing/chartshape/has_line) | Получает и задает видимую линию границы фигуры.|
| [is_filled](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_filled) | Указывает, виден ли формат заливки.|
| [is_flipped_horizontally](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_flipped_horizontally) | Получает и устанавливает, отражается ли фигура по горизонтали.|
| [is_flipped_vertically](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_flipped_vertically) | Получает и устанавливает, переворачивается ли фигура по вертикали.|
| [actual_lower_right_row](/cells/python-net/ru/aspose.cells.drawing/chartshape/actual_lower_right_row) | Получите фактическую нижнюю строку.|
| [connection_points](/cells/python-net/ru/aspose.cells.drawing/chartshape/connection_points) | Получите точки подключения|
| [relative_to_original_picture_size](/cells/python-net/ru/aspose.cells.drawing/chartshape/relative_to_original_picture_size) | Указывает, соответствует ли форма исходному размеру изображения.|
| [linked_cell](/cells/python-net/ru/aspose.cells.drawing/chartshape/linked_cell) | Получает или задает диапазон листа, связанный со значением элемента управления.|
| [input_range](/cells/python-net/ru/aspose.cells.drawing/chartshape/input_range) | Получает или задает диапазон листа, используемый для заполнения указанного поля со списком.|
| [text_shape_type](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_shape_type) |Получает и задает заданный тип фигуры текста.|
| [text_body](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_body) | Получает и задает настройку текста фигуры.|
| [font](/cells/python-net/ru/aspose.cells.drawing/chartshape/font) | Представляет шрифт фигуры.|
| [text_options](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_options) | Представляет параметры текста фигуры.|
| [text](/cells/python-net/ru/aspose.cells.drawing/chartshape/text) | Представляет строку в этом объекте TextBox.|
| [is_rich_text](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_rich_text) | Является ли текст форматированным текстом.|
| [html_text](/cells/python-net/ru/aspose.cells.drawing/chartshape/html_text) | Получает и задает строку HTML, содержащую данные и некоторые форматы в этом текстовом поле.|
| [text_vertical_overflow](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_vertical_overflow) | Получает и задает тип вертикального переполнения текста для фигуры, содержащей текст.|
| [text_horizontal_overflow](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_horizontal_overflow) | Получает и задает тип горизонтального переполнения текста для фигуры, содержащей текст.|
| [is_text_wrapped](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_text_wrapped) | Получает и задает тип переноса текста для фигуры, содержащей текст.|
| [text_orientation_type](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_orientation_type) | Получает и задает тип ориентации текста фигуры.|
| [text_horizontal_alignment](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_horizontal_alignment) | Получает и задает тип горизонтального выравнивания текста фигуры.|
| [text_vertical_alignment](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_vertical_alignment) | Получает и задает тип вертикального выравнивания текста фигуры.|
| [text_direction](/cells/python-net/ru/aspose.cells.drawing/chartshape/text_direction) | Получает/задает направление потока текста для этого объекта.|
| [control_data](/cells/python-net/ru/aspose.cells.drawing/chartshape/control_data) | Получает данные управления.|
| [active_x_control](/cells/python-net/ru/aspose.cells.drawing/chartshape/active_x_control) | Получает элемент управления ActiveX.|
| [paths](/cells/python-net/ru/aspose.cells.drawing/chartshape/paths) |Получает пути пользовательской геометрической фигуры.|
| [geometry](/cells/python-net/ru/aspose.cells.drawing/chartshape/geometry) | Получает геометрию|
| [create_id](/cells/python-net/ru/aspose.cells.drawing/chartshape/create_id) | Получает и устанавливает идентификатор для этой фигуры.|
| [chart](/cells/python-net/ru/aspose.cells.drawing/chartshape/chart) | Возвращает объект Chart, представляющий диаграмму, содержащуюся в объекте.|


###  Методы
| Метод| Описание|
| :- | :- |
| [to_image](/cells/python-net/ru/aspose.cells.drawing/chartshape/to_image/#io.RawIOBase-aspose.cells.drawing.ImageType) | Создает изображение фигуры и сохраняет его в поток в указанном формате.|
| [to_image](/cells/python-net/ru/aspose.cells.drawing/chartshape/to_image/#str-aspose.cells.rendering.ImageOrPrintOptions) | Сохраняет форму в файл.|
| [to_image](/cells/python-net/ru/aspose.cells.drawing/chartshape/to_image/#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions) | Сохраняет форму в поток.|
| [format_characters](/cells/python-net/ru/aspose.cells.drawing/chartshape/format_characters/#int-int-aspose.cells.Font-aspose.cells.StyleFlag) | Форматирует некоторые символы с помощью настройки шрифта.|
| [format_characters](/cells/python-net/ru/aspose.cells.drawing/chartshape/format_characters/#int-int-aspose.cells.Font) | Форматирует некоторые символы с помощью настройки шрифта.|
| [get_result_of_smart_art](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_result_of_smart_art/#) | Преобразование смарт-арта в сгруппированные фигуры.|
| [to_front_or_back](/cells/python-net/ru/aspose.cells.drawing/chartshape/to_front_or_back/#int) | Перемещает фигуру на передний план или отодвигает ее назад.|
| [get_locked_property](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_locked_property/#aspose.cells.drawing.ShapeLockType) | Получает значение заблокированного свойства.|
| [set_locked_property](/cells/python-net/ru/aspose.cells.drawing/chartshape/set_locked_property/#aspose.cells.drawing.ShapeLockType-bool) | Установите заблокированное свойство.|
| [add_hyperlink](/cells/python-net/ru/aspose.cells.drawing/chartshape/add_hyperlink/#str) | Добавляет гиперссылку на фигуру.|
| [remove_hyperlink](/cells/python-net/ru/aspose.cells.drawing/chartshape/remove_hyperlink/#) | Удалите гиперссылку фигуры.|
| [move_to_range](/cells/python-net/ru/aspose.cells.drawing/chartshape/move_to_range/#int-int-int-int) | Перемещает фигуру в указанный диапазон.|
| [align_top_right_corner](/cells/python-net/ru/aspose.cells.drawing/chartshape/align_top_right_corner/#int-int) |Перемещает изображение в правый верхний угол.|
| [get_connection_points](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_connection_points/#) | Получите точки подключения|
| [get_linked_cell](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_linked_cell/#bool-bool) | Получает диапазон, связанный со значением элемента управления.|
| [set_linked_cell](/cells/python-net/ru/aspose.cells.drawing/chartshape/set_linked_cell/#str-bool-bool) | Устанавливает диапазон, связанный со значением элемента управления.|
| [get_input_range](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_input_range/#bool-bool) | Получает диапазон, используемый для заполнения элемента управления.|
| [set_input_range](/cells/python-net/ru/aspose.cells.drawing/chartshape/set_input_range/#str-bool-bool) | Устанавливает диапазон, используемый для заполнения элемента управления.|
| [update_selected_value](/cells/python-net/ru/aspose.cells.drawing/chartshape/update_selected_value/#) | Обновите выбранное значение значением связанной ячейки.|
| [calculate_text_size](/cells/python-net/ru/aspose.cells.drawing/chartshape/calculate_text_size/#) | Пересчитать текстовую область|
| [characters](/cells/python-net/ru/aspose.cells.drawing/chartshape/characters/#int-int) | Возвращает объект символов, представляющий диапазон символов в тексте.|
| [get_characters](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_characters/#) | Возвращает все объекты символов<br/> который представляет собой диапазон символов в тексте.|
| [get_rich_formattings](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_rich_formattings/#) | Возвращает все объекты символов<br/> который представляет собой диапазон символов в тексте.|
| [remove_active_x_control](/cells/python-net/ru/aspose.cells.drawing/chartshape/remove_active_x_control/#) | Удалить элемент ActiveX.|
| [is_same_setting](/cells/python-net/ru/aspose.cells.drawing/chartshape/is_same_setting/#any) | Возвращает, одинакова ли форма.|
| [get_actual_box](/cells/python-net/ru/aspose.cells.drawing/chartshape/get_actual_box/#) | Получите фактическое положение и размер фигуры (после применения поворота, переворота и т. д.).|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.PIE_EXPLODED, 5, 0, 25, 10)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
# Show Data Labels
chart.n_series[0].data_labels.show_value = True
# Getting Chart Shape
chartShape = chart.chart_object
# Set Lower Right Column
chartShape.lower_right_column = 10
# Set LowerDeltaX
chartShape.lower_delta_x = 1024
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`ChartShape`](/cells/python-net/ru/aspose.cells.drawing/chartshape)
* класс [`GlowEffect`](/cells/python-net/ru/aspose.cells.drawing/gloweffect)
* класс [`ReflectionEffect`](/cells/python-net/ru/aspose.cells.drawing/reflectioneffect)
* класс [`ShadowEffect`](/cells/python-net/ru/aspose.cells.drawing/shadoweffect)
* класс [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)
