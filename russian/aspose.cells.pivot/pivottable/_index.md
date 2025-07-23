---
title: PivotTable класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 230
url: /ru/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable класс
Краткое описание для PivotTable.



Тип PivotTable предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Указывает, совместима ли сводная таблица с Excel2003 при обновлении сводной таблицы,<br/>Если true, строка должна быть меньше или равна 255 символам, поэтому, если строка больше 255 символов,<br/>она будет усечена. Если false, строка не будет иметь вышеупомянутого ограничения.<br/> Значение по умолчанию — true.|
| [refreshed_by_who](/cells/python-net/ru/aspose.cells.pivot/pivottable/refreshed_by_who) | Получает имя последнего пользователя, обновившего эту сводную таблицу.|
| [refresh_date](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_date) | Возвращает дату и время последнего обновления сводной таблицы.|
| [pivot_table_style_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_table_style_name) | Получает и задает имя стиля сводной таблицы.|
| [pivot_table_style_type](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_table_style_type) | Получает и задает стиль встроенной сводной таблицы.|
| [column_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_fields) | Возвращает объект PivotFields, которые в данный момент отображаются как поля столбцов.|
| [row_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_fields) | Возвращает объект PivotFields, которые в данный момент отображаются как поля строк.|
| [page_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/page_fields) | Возвращает объект PivotFields, которые в данный момент отображаются как поля страницы.|
| [data_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_fields) | Получает объект PivotField, представляющий все поля данных в сводной таблице.<br/>Только для чтения. Инициализация будет выполнена только в том случае, если в DataPiovtFiels есть два или более полей данных.<br/> Используется только для добавления поля DataPivotField в область строк/столбцов сводной таблицы. По умолчанию поле находится в области строк.|
| [data_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_field) |Получает объект [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield), представляющий все поля данных в сводной таблице.<br/>Только для чтения.<br/>Он будет создан только в том случае, если в области данных есть два или более полей данных.<br/> По умолчанию он находится в области строк. Вы можете перетащить его в область строк/столбцов с помощью метода PivotTable.AddFieldToArea().|
| [base_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/base_fields) | Возвращает все базовые поля сводной таблицы.|
| [pivot_filters](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_filters) | Возвращает все фильтры полей сводной таблицы.|
| [column_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_range) | Возвращает объект CellArea, представляющий диапазон<br/> содержащий область столбцов в отчете сводной таблицы. Только для чтения.|
| [row_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_range) | Возвращает объект CellArea, представляющий диапазон<br/> содержащий область строк в отчете сводной таблицы. Только для чтения.|
| [data_body_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_body_range) | Возвращает объект [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea), представляющий диапазон, содержащий область данных.<br/> в списке между строкой заголовка и строкой вставки. Только для чтения.|
| [table_range1](/cells/python-net/ru/aspose.cells.pivot/pivottable/table_range1) | Возвращает объект CellArea, представляющий диапазон, содержащий весь отчет сводной таблицы,<br/> но не включает поля страницы. Только для чтения.|
| [table_range2](/cells/python-net/ru/aspose.cells.pivot/pivottable/table_range2) | Возвращает объект CellArea, представляющий диапазон, содержащий весь отчет сводной таблицы,<br/> Включает поля страницы. Только для чтения.|
| [is_grid_drop_zones](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Указывает, отображает ли отчет сводной таблицы классический макет сводной таблицы.<br/> (позволяет перетаскивать поля в сетке)|
| [show_column_grand_totals](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_column_grand_totals) |Указывает, следует ли показывать общие итоги для столбцов данной сводной таблицы.|
| [show_row_grand_totals](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_row_grand_totals) | Указывает, следует ли показывать общие итоги для строк сводной таблицы.|
| [column_grand](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_grand) | Указывает, отображает ли отчет сводной таблицы общие итоги по столбцам.|
| [row_grand](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_grand) | Указывает, следует ли показывать общие итоги для строк этой сводной таблицы.|
| [display_null_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/display_null_string) | Указывает, отображает ли отчет сводной таблицы пользовательскую строку, если значение равно NULL.|
| [null_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/null_string) | Получает строку, отображаемую в ячейках, содержащих нулевые значения.<br/> когда свойство DisplayNullString имеет значение true. Значение по умолчанию — пустая строка.|
| [display_error_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/display_error_string) | Указывает, отображает ли отчет сводной таблицы пользовательскую строку в ячейках, содержащих ошибки.|
| [data_field_header_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_field_header_name) | Возвращает и задает имя заголовка поля области значений в сводной таблице.|
| [error_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/error_string) | Получает строку, отображаемую в ячейках, содержащих ошибки.<br/> когда свойство DisplayErrorString имеет значение true. Значение по умолчанию — пустая строка.|
| [is_auto_format](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_auto_format) | Указывает, форматируется ли отчет сводной таблицы автоматически.<br/>Флажок «Автоформат таблицы» в опции сводной таблицы Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/ru/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Указывает, будет ли автоматически подбираться ширина столбца при обновлении|
| [auto_format_type](/cells/python-net/ru/aspose.cells.pivot/pivottable/auto_format_type) | Получает и задает тип автоматического форматирования сводной таблицы.|
| [has_blank_rows](/cells/python-net/ru/aspose.cells.pivot/pivottable/has_blank_rows) | Указывает, следует ли добавлять пустые строки.<br/> Это свойство применяется только к типам автоматического форматирования сводных таблиц, которым необходимо добавлять пустые строки.|
| [merge_labels](/cells/python-net/ru/aspose.cells.pivot/pivottable/merge_labels) | True, если метки элементов внешней строки, столбца, промежуточных итогов и общих итогов указанного отчета сводной таблицы используют объединенные ячейки.|
| [preserve_formatting](/cells/python-net/ru/aspose.cells.pivot/pivottable/preserve_formatting) | Указывает, сохраняется ли форматирование при обновлении или пересчете сводной таблицы.|
| [show_drill](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_drill) | Возвращает и задает, отображать ли кнопки «развернуть/свернуть».|
| [enable_drilldown](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_drilldown) | Проверяет, включена ли детализация.|
| [enable_field_dialog](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_field_dialog) | Указывает, доступно ли диалоговое окно «Поле сводной таблицы»<br/> когда пользователь дважды щелкает поле сводной таблицы.|
| [enable_field_list](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_field_list) | Указывает, доступен ли список полей сводной таблицы в представлении Excel.|
| [enable_wizard](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_wizard) | Указывает, доступен ли мастер сводных таблиц.|
| [subtotal_hidden_page_items](/cells/python-net/ru/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |Указывает, скрыты ли элементы полей страницы в отчете сводной таблицы.<br/>включены в промежуточные итоги по строкам и столбцам, итоги по блокам и общие итоги.<br/> Значение по умолчанию — Ложь.|
| [grand_total_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/grand_total_name) | Возвращает метку, которая отображается в заголовке столбца или строки общего итога.<br/> Значением по умолчанию является строка «Общий итог».|
| [manual_update](/cells/python-net/ru/aspose.cells.pivot/pivottable/manual_update) | Указывает, пересчитывается ли отчет сводной таблицы только по запросу пользователя.|
| [is_multiple_field_filters](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Задает логическое значение, указывающее, могут ли поля сводной таблицы иметь несколько фильтров.|
| [allow_multiple_filters_per_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | Задает логическое значение, указывающее, могут ли поля сводной таблицы иметь несколько фильтров.|
| [missing_items_limit](/cells/python-net/ru/aspose.cells.pivot/pivottable/missing_items_limit) | Задает логическое значение, указывающее, могут ли поля сводной таблицы иметь несколько фильтров.|
| [enable_data_value_editing](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_data_value_editing) | Задает логическое значение, указывающее, разрешено ли пользователю редактировать ячейки в области данных сводной таблицы.<br/> Включить редактирование ячеек в области значений|
| [show_data_tips](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_data_tips) | Задает логическое значение, указывающее, следует ли отображать подсказки для ячеек данных сводной таблицы.|
| [show_member_property_tips](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_member_property_tips) | Задает логическое значение, указывающее, следует ли исключать информацию о свойствах элемента из подсказок сводной таблицы.|
| [show_values_row](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_values_row) | Указывает, отображать ли строку значений.|
| [show_empty_col](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_empty_col) | Указывает, следует ли включать пустые столбцы в таблицу.|
| [show_empty_row](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_empty_row) |Указывает, следует ли включать пустые строки в таблицу.|
| [field_list_sort_ascending](/cells/python-net/ru/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Указывает, сортируются ли поля сводной таблицы в порядке, отличном от порядка по умолчанию в списке полей.|
| [print_drill](/cells/python-net/ru/aspose.cells.pivot/pivottable/print_drill) | Задает логическое значение, указывающее, следует ли печатать индикаторы сверления.<br/> печатать кнопки «развернуть/свернуть» при отображении на сводной таблице.|
| [alt_text_title](/cells/python-net/ru/aspose.cells.pivot/pivottable/alt_text_title) | Получает и задает заголовок альтернативного текста.|
| [alt_text_description](/cells/python-net/ru/aspose.cells.pivot/pivottable/alt_text_description) | Получает описание альтернативного текста.|
| [name](/cells/python-net/ru/aspose.cells.pivot/pivottable/name) | Получает имя сводной таблицы|
| [column_header_caption](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_header_caption) | Получает заголовок столбца сводной таблицы.|
| [indent](/cells/python-net/ru/aspose.cells.pivot/pivottable/indent) | Задает шаг отступа для компактной оси и может использоваться для установки макета отчета в компактную форму.|
| [row_header_caption](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_header_caption) | Получает заголовок строки сводной таблицы.|
| [show_row_header_caption](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_row_header_caption) | Указывает, отображается ли заголовок строки в отчете сводной таблицы.<br/> Указывает, отображать ли заголовки полей и раскрывающиеся списки фильтров.|
| [custom_list_sort](/cells/python-net/ru/aspose.cells.pivot/pivottable/custom_list_sort) | Указывает, следует ли учитывать встроенный пользовательский список при сортировке данных.|
| [pivot_format_conditions](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_format_conditions) | Получает условия форматирования сводной таблицы.|
| [conditional_formats](/cells/python-net/ru/aspose.cells.pivot/pivottable/conditional_formats) | Получает условные форматы сводной таблицы.|
| [page_field_order](/cells/python-net/ru/aspose.cells.pivot/pivottable/page_field_order) |Возвращает и задает порядок, в котором поля страницы добавляются в макет отчета сводной таблицы.|
| [page_field_wrap_count](/cells/python-net/ru/aspose.cells.pivot/pivottable/page_field_wrap_count) | Возвращает количество полей страницы в каждом столбце или строке отчета сводной таблицы.|
| [tag](/cells/python-net/ru/aspose.cells.pivot/pivottable/tag) | Получает строку, сохраненную в отчете сводной таблицы.|
| [save_data](/cells/python-net/ru/aspose.cells.pivot/pivottable/save_data) | Указывает, сохраняются ли данные для отчета сводной таблицы вместе с рабочей книгой.|
| [refresh_data_on_opening_file](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Указывает, обновлять ли данные при открытии файла.|
| [refresh_data_flag](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data_flag) | Указывает, происходит ли обновление данных.|
| [source_type](/cells/python-net/ru/aspose.cells.pivot/pivottable/source_type) | Получает тип источника данных сводной таблицы.|
| [external_connection_data_source](/cells/python-net/ru/aspose.cells.pivot/pivottable/external_connection_data_source) | Получает внешний источник данных соединения.|
| [data_source](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_source) | Получает и задает источник данных сводной таблицы.|
| [pivot_formats](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_formats) | Получает коллекцию форматов, примененных к сводной таблице.|
| [item_print_titles](/cells/python-net/ru/aspose.cells.pivot/pivottable/item_print_titles) | Указывает, следует ли повторять имена PivotItem в верхней части каждой распечатанной страницы.|
| [repeat_items_on_each_printed_page](/cells/python-net/ru/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | Указывает, повторяются ли заголовки элементов сводки в области строк на каждой печатной странице для полей сводки в табличной форме.|
| [print_titles](/cells/python-net/ru/aspose.cells.pivot/pivottable/print_titles) | Указывает, задаются ли заголовки для печати на рабочем листе на основе<br/> В отчёте сводной таблицы. Значение по умолчанию — false.|
| [display_immediate_items](/cells/python-net/ru/aspose.cells.pivot/pivottable/display_immediate_items) |Указывает, видны ли элементы в строках и столбцах.<br/> Когда область данных сводной таблицы пуста. Значение по умолчанию — true.|
| [is_selected](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_selected) | Указывает, выбрана ли данная сводная таблица.|
| [show_pivot_style_row_header](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Указывает, следует ли применять стиль к заголовку строки в сводной таблице.|
| [show_pivot_style_column_header](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Указывает, следует ли применять стиль к заголовку столбца в сводной таблице.|
| [show_pivot_style_row_stripes](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Указывает, применяется ли форматирование полос строк.|
| [show_pivot_style_column_stripes](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Указывает, применяется ли к столбцу форматирование полос.|
| [show_pivot_style_last_column](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Указывает, применяется ли форматирование столбца.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | Удаляет поле из определенной области полей|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | Удаляет поле из определенной области полей|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Удалить поле из определенной области полей|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | Добавляет поле в определенную область.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | Добавляет поле в определенную область.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Добавляет поле в определенную область.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Добавляет вычисляемое поле к сводному полю.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Добавляет вычисляемое поле в сводное поле и перетаскивает его в область данных.|
| [`move(self, row, column)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/move/#int-int) | Перемещает сводную таблицу в другое место на листе.|
| [`move(self, dest_cell_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/move/#str) | Перемещает сводную таблицу в другое место на листе.|
| [`move_to(self, row, column)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/move_to/#int-int) | Перемещает сводную таблицу в другое место на листе.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/move_to/#str) | Перемещает сводную таблицу в другое место на листе.|
| [`get_source(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_source/#) | Получить исходные данные сводной таблицы.|
| [`get_source(self, is_original)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_source/#bool) | Получить исходные данные сводной таблицы.|
| [`refresh_data(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data/#) |Обновляет данные и настройки сводной таблицы из ее источника данных.|
| [`refresh_data(self, option)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | Обновляет данные и настройки сводной таблицы из ее источника данных с параметрами.|
| [`calculate_data(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/calculate_data/#) | Рассчитывает данные сводной таблицы по ячейкам.|
| [`calculate_data(self, option)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | Расчет сводных таблиц с параметрами|
| [`format(self, pivot_area, style)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | Форматирует выбранную область сводной таблицы.|
| [`format(self, ca, style)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | Форматирует выбранную область сводной таблицы.|
| [`format(self, row, column, style)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | Отформатируйте ячейку в области сводной таблицы.|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Устанавливает автоматическую группировку полей по сводной таблице.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | Устанавливает автоматическую группировку полей по сводной таблице.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Устанавливает ручную группировку полей по сводной таблице.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | Устанавливает ручную группировку полей по сводной таблице.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | Устанавливает ручную группировку полей по сводной таблице.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | Устанавливает ручную группировку полей по сводной таблице.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_ungroup/#int) | Разгруппировать наборы по сводной таблице|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | Разгруппировать наборы по сводной таблице|
| [`copy_style(self, pivot_table)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | Копирует именованный стиль из другой сводной таблицы.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | Показывать все страницы фильтров отчета в соответствии с PivotField, PivotField должен располагаться в PageFields.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Показывать все страницы фильтров отчета в соответствии с именем PivotField, PivotField должен располагаться в PageFields.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Показать все страницы фильтра отчета в соответствии с индексом позиции в PageFields|
| [`get_fields(self, field_type)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | Получает конкретный список полей сводки по региону.|
| [`fields(self, field_type)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | Получает конкретные поля по типу поля.|
| [`get_source_data_connections(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_source_data_connections/#) |Получает внешние источники данных соединения.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | Получает имя подключений к внешнему источнику данных.|
| [`change_data_source(self, source)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/change_data_source/#list) | Задайте исходные данные сводной таблицы.|
| [`clear_data(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/clear_data/#) | Очистить данные и форматирование сводной таблицы|
| [`calculate_range(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/calculate_range/#) | Вычисляет диапазон сводной таблицы.|
| [`format_all(self, style)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | Форматировать все ячейки в области сводной таблицы|
| [`format_row(self, row, style)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | Отформатируйте данные строки в области сводной таблицы.|
| [`select_area(self, ca)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | Выберите область представления сводной таблицы.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | Отобразить подробную информацию об одном элементе в области данных в новой таблице.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | Получает горизонтальные разрывы страниц этой сводной таблицы.|
| [`get_horizontal_breaks(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Получает список индексов строк сводной таблицы горизонтальных разрывов страниц.|
| [`show_in_compact_form(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Размещает сводную таблицу в компактном виде.|
| [`show_in_outline_form(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Макетирует сводную таблицу в виде структуры.|
| [`show_in_tabular_form(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Макетирует сводную таблицу в табличной форме.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Получает объект [`Cell`](/cells/python-net/ru/aspose.cells/cell) по отображаемому имени PivotField.|
| [`get_children(self)`](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_children/#) | Получает дочерние сводные таблицы, которые используют данные этой сводной таблицы в качестве источника данных.|



###  Пример

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
* класс [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea)
* класс [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield)
