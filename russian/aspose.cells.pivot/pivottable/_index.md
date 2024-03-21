---
title: PivotTable класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 180
url: /ru/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable класс
Краткое описание для PivotTable.



Тип PivotTable предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Указывает, совместима ли сводная таблица с Excel2003 при обновлении сводной таблицы.<br/>если это правда, строка должна быть меньше или равна 255 символам, поэтому, если строка больше 255 символов,<br/>оно будет усечено. если false, строка не будет иметь вышеупомянутое ограничение.<br/> Значение по умолчанию верно.|
| [refreshed_by_who](/cells/python-net/ru/aspose.cells.pivot/pivottable/refreshed_by_who) | Получает имя пользователя, который последним обновил сводную таблицу.|
| [refresh_date](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_date) | Получает дату последнего обновления сводной таблицы.|
| [pivot_table_style_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_table_style_name) | Получает и задает имя стиля сводной таблицы.|
| [pivot_table_style_type](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_table_style_type) | Получает и задает встроенный стиль сводной таблицы.|
| [column_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_fields) | Возвращает объект PivotFields, который в данный момент отображается как поля столбцов.|
| [row_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_fields) | Возвращает объект PivotFields, который в данный момент отображается как поля строк.|
| [page_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/page_fields) | Возвращает объект PivotFields, который в данный момент отображается как поля страницы.|
| [data_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_fields) | Получает объект PivotField, представляющий все поля данных в сводной таблице.<br/>Только для чтения. Он будет инициализирован только при наличии двух или более полей данных в DataPiovtFiels.<br/> Он используется только для добавления DataPivotField в область строки/столбца сводной таблицы. По умолчанию находится в области строк.|
| [data_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_field) | Получает объект PivotField, представляющий все поля данных в сводной таблице.<br/>Только для чтения. Он будет инициализирован только при наличии двух или более полей данных в DataPiovtFiels.<br/> Он используется только для добавления DataPivotField в область строки/столбца сводной таблицы. По умолчанию находится в области строк.|
| [base_fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/base_fields) | Возвращает объект PivotFields, включающий все поля отчета сводной таблицы.|
| [pivot_filters](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_filters) | Возвращает объект PivotFilterCollection.|
| [column_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_range) |Возвращает объект CellArea, представляющий диапазон<br/> который содержит область столбца в отчете сводной таблицы. Только для чтения.|
| [row_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_range) |Возвращает объект CellArea, представляющий диапазон<br/> который содержит область строк в отчете сводной таблицы. Только для чтения.|
| [data_body_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_body_range) | Возвращает объект CellArea, представляющий диапазон, содержащий область данных.<br/> в списке между строкой заголовка и строкой вставки. Только для чтения.|
| [table_range1](/cells/python-net/ru/aspose.cells.pivot/pivottable/table_range1) | Возвращает объект CellArea, представляющий диапазон, содержащий весь отчет сводной таблицы.<br/> но не включает поля страницы. Только для чтения.|
| [table_range2](/cells/python-net/ru/aspose.cells.pivot/pivottable/table_range2) | Возвращает объект CellArea, представляющий диапазон, содержащий весь отчет сводной таблицы.<br/> включает поля страницы. Только для чтения.|
| [column_grand](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_grand) | Указывает, отображаются ли в отчете сводной таблицы общие итоги по столбцам.|
| [is_grid_drop_zones](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Указывает, отображает ли отчет сводной таблицы классический макет сводной таблицы.<br/> (позволяет перетаскивать поля в сетке)|
| [row_grand](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_grand) | Указывает, отображаются ли в отчете сводной таблицы общие итоги по строкам.|
| [display_null_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/display_null_string) | Указывает, отображает ли отчет сводной таблицы пользовательскую строку.<br/> в ячейках, содержащих нулевые значения.|
| [null_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/null_string) | Получает строку, отображаемую в ячейках, содержащих значения NULL.<br/>когда свойство DisplayNullString имеет значение true. Значением по умолчанию является пустая строка.|
| [display_error_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/display_error_string) | Указывает, отображает ли отчет сводной таблицы пользовательскую строку в ячейках, содержащих ошибки.|
| [data_field_header_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_field_header_name) | Получает и задает имя заголовка поля области значений в сводной таблице.|
| [error_string](/cells/python-net/ru/aspose.cells.pivot/pivottable/error_string) | Получает строку, отображаемую в ячейках, содержащих ошибки.<br/> когда свойство DisplayErrorString имеет значение true. Значением по умолчанию является пустая строка.|
| [is_auto_format](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_auto_format) | Указывает, форматируется ли отчет сводной таблицы автоматически.<br/> Флажок «автоформат таблицы», который находится в опции сводной таблицы для Excel 2003.|
| [autofit_column_width_on_update](/cells/python-net/ru/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Указывает, выполняется ли автоподбор ширины столбца при обновлении.|
| [auto_format_type](/cells/python-net/ru/aspose.cells.pivot/pivottable/auto_format_type) | Получает тип автоматического форматирования сводной таблицы.|
| [has_blank_rows](/cells/python-net/ru/aspose.cells.pivot/pivottable/has_blank_rows) | Указывает, добавлять ли пустые строки.<br/> Это свойство применяется только к типам автоматического форматирования сводных таблиц, в которых необходимо добавлять пустые строки.|
| [merge_labels](/cells/python-net/ru/aspose.cells.pivot/pivottable/merge_labels) | Указывает, есть ли в указанном отчете сводной таблицы элемент внешней строки, элемент столбца, промежуточный итог,<br/> а в метках общего итога используются объединенные ячейки.|
| [preserve_formatting](/cells/python-net/ru/aspose.cells.pivot/pivottable/preserve_formatting) |Указывает, сохраняется ли форматирование при обновлении или пересчете сводной таблицы.|
| [show_drill](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_drill) | Определяет, отображаются ли кнопки развернуть/свернуть.|
| [enable_drilldown](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_drilldown) | Проверяет, включена ли детализация.|
| [enable_field_dialog](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_field_dialog) | Указывает, доступно ли диалоговое окно «Поле сводной таблицы».<br/> когда пользователь дважды щелкает поле сводной таблицы.|
| [enable_field_list](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_field_list) | Получает информацию о том, включить ли список полей для сводной таблицы.|
| [enable_wizard](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_wizard) | Указывает, доступен ли мастер сводных таблиц.|
| [subtotal_hidden_page_items](/cells/python-net/ru/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Указывает, скрыты ли элементы полей страницы в отчете сводной таблицы.<br/>включаются в промежуточные итоги по строкам и столбцам, итоги по блокам и общие итоги.<br/> Значение по умолчанию неверно.|
| [grand_total_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/grand_total_name) | Возвращает метку текстовой строки, которая отображается в заголовке столбца или строки общего итога.<br/> Значением по умолчанию является строка «Общий итог».|
| [manual_update](/cells/python-net/ru/aspose.cells.pivot/pivottable/manual_update) | Указывает, пересчитывается ли отчет сводной таблицы только по запросу пользователя.|
| [is_multiple_field_filters](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Указывает логическое значение, указывающее, можно ли для полей сводной таблицы установить несколько фильтров.|
| [missing_items_limit](/cells/python-net/ru/aspose.cells.pivot/pivottable/missing_items_limit) | Указывает логическое значение, указывающее, можно ли для полей сводной таблицы установить несколько фильтров.|
| [enable_data_value_editing](/cells/python-net/ru/aspose.cells.pivot/pivottable/enable_data_value_editing) |Указывает логическое значение, указывающее, разрешено ли пользователю редактировать ячейки в области данных сводной таблицы.<br/> Включить редактирование ячеек в области значений|
| [show_data_tips](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_data_tips) | Указывает логическое значение, указывающее, следует ли отображать всплывающие подсказки для ячеек данных сводной таблицы.|
| [show_member_property_tips](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_member_property_tips) | Указывает логическое значение, указывающее, следует ли исключить информацию о свойствах элемента из подсказок сводной таблицы.|
| [show_values_row](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_values_row) | Указывает логическое значение, указывающее, отображать ли строку значений.<br/> показать строку значений|
| [show_empty_col](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_empty_col) | Указывает логическое значение, указывающее, включать ли пустые столбцы в таблицу.|
| [show_empty_row](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_empty_row) | Указывает логическое значение, указывающее, включать ли в таблицу пустые строки.|
| [field_list_sort_ascending](/cells/python-net/ru/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Указывает логическое значение, указывающее, сортируются ли поля сводной таблицы в списке полей в порядке, отличном от заданного по умолчанию.|
| [print_drill](/cells/python-net/ru/aspose.cells.pivot/pivottable/print_drill) | Указывает логическое значение, указывающее, следует ли печатать индикаторы детализации.<br/> печатать кнопки развертывания/свертывания при отображении в сводной таблице.|
| [alt_text_title](/cells/python-net/ru/aspose.cells.pivot/pivottable/alt_text_title) |Получает заголовок альтернативного текста|
| [alt_text_description](/cells/python-net/ru/aspose.cells.pivot/pivottable/alt_text_description) | Получает описание замещающего текста|
| [name](/cells/python-net/ru/aspose.cells.pivot/pivottable/name) | Получает имя сводной таблицы.|
| [column_header_caption](/cells/python-net/ru/aspose.cells.pivot/pivottable/column_header_caption) | Получает заголовок столбца сводной таблицы.|
| [indent](/cells/python-net/ru/aspose.cells.pivot/pivottable/indent) | Указывает шаг отступа для компактной оси и может использоваться для установки компактной формы макета отчета.|
| [row_header_caption](/cells/python-net/ru/aspose.cells.pivot/pivottable/row_header_caption) | Получает заголовок строки сводной таблицы.|
| [show_row_header_caption](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_row_header_caption) | Указывает, отображается ли заголовок строки в отчете сводной таблицы.<br/> Указывает, нужно ли отображать заголовки полей и раскрывающиеся списки фильтров.|
| [custom_list_sort](/cells/python-net/ru/aspose.cells.pivot/pivottable/custom_list_sort) | Указывает, следует ли учитывать встроенный настраиваемый список при сортировке данных.|
| [pivot_format_conditions](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_format_conditions) | Получает условия форматирования сводной таблицы.|
| [page_field_order](/cells/python-net/ru/aspose.cells.pivot/pivottable/page_field_order) | Получает порядок, в котором поля страницы добавляются в макет отчета сводной таблицы.|
| [page_field_wrap_count](/cells/python-net/ru/aspose.cells.pivot/pivottable/page_field_wrap_count) | Получает количество полей страницы в каждом столбце или строке отчета сводной таблицы.|
| [tag](/cells/python-net/ru/aspose.cells.pivot/pivottable/tag) | Получает строку, сохраненную вместе с отчетом сводной таблицы.|
| [save_data](/cells/python-net/ru/aspose.cells.pivot/pivottable/save_data) | Указывает, сохраняются ли данные отчета сводной таблицы вместе с книгой.|
| [refresh_data_on_opening_file](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Указывает, обновляются ли данные при открытии файла.|
| [refresh_data_flag](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data_flag) |Указывает, обновляются ли данные или нет.|
| [external_connection_data_source](/cells/python-net/ru/aspose.cells.pivot/pivottable/external_connection_data_source) | Получает источник данных внешнего подключения.|
| [data_source](/cells/python-net/ru/aspose.cells.pivot/pivottable/data_source) | Получает и задает источник данных сводной таблицы.|
| [pivot_formats](/cells/python-net/ru/aspose.cells.pivot/pivottable/pivot_formats) | Получает коллекцию форматов, примененных к сводной таблице.|
| [item_print_titles](/cells/python-net/ru/aspose.cells.pivot/pivottable/item_print_titles) | Бит, определяющий, будут ли заголовки сводных элементов располагаться на оси строки.<br/> повторяются на каждой печатной странице для сводных полей в табличной форме.|
| [print_titles](/cells/python-net/ru/aspose.cells.pivot/pivottable/print_titles) | Указывает, установлены ли печатные заголовки для листа на основе<br/> в отчете сводной таблицы. Значение по умолчанию неверно.|
| [display_immediate_items](/cells/python-net/ru/aspose.cells.pivot/pivottable/display_immediate_items) | Указывает, видны ли элементы в областях строк и столбцов.<br/> когда область данных сводной таблицы пуста. Значение по умолчанию верно.|
| [is_selected](/cells/python-net/ru/aspose.cells.pivot/pivottable/is_selected) | Указывает, выбрана ли сводная таблица.|
| [show_pivot_style_row_header](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Указывает, должен ли применяться стиль к заголовку строки в сводной таблице.|
| [show_pivot_style_column_header](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Указывает, следует ли применять стиль к заголовку столбца в сводной таблице.|
| [show_pivot_style_row_stripes](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Указывает, применяется ли форматирование полосы строк.|
| [show_pivot_style_column_stripes](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Указывает, применяется ли форматирование полос столбцов.|
| [show_pivot_style_last_column](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Указывает, применяется ли форматирование полос столбцов.|


###  Методы
| Метод| Описание|
| :- | :- |
| [remove_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) |Удаляет поле из определенной области поля|
| [remove_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) |Удаляет поле из определенной области поля|
| [remove_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Удалить поле из определенной области поля|
| [add_field_to_area](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Добавляет поле в определенную область.|
| [add_field_to_area](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Добавляет поле в определенную область.|
| [add_field_to_area](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Добавляет поле в определенную область.|
| [add_calculated_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Добавляет вычисляемое поле в сводное поле.|
| [add_calculated_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Добавляет вычисляемое поле в сводное поле и перетаскивает его в область данных.|
| [move](/cells/python-net/ru/aspose.cells.pivot/pivottable/move/#int-int) | Перемещает сводную таблицу в другое место на листе.|
| [move](/cells/python-net/ru/aspose.cells.pivot/pivottable/move/#str) | Перемещает сводную таблицу в другое место на листе.|
| [format](/cells/python-net/ru/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Форматирует выделенную область сводной таблицы.|
| [format](/cells/python-net/ru/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Форматирование ячейки в области сводной таблицы|
| [set_auto_group_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Устанавливает автоматическую группу полей с помощью сводной таблицы.|
| [set_auto_group_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Устанавливает автоматическую группу полей с помощью сводной таблицы.|
| [set_manual_group_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Устанавливает группу полей вручную с помощью сводной таблицы.|
| [set_manual_group_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Устанавливает группу полей вручную с помощью сводной таблицы.|
| [set_manual_group_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Устанавливает группу полей вручную с помощью сводной таблицы.|
| [set_manual_group_field](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Устанавливает группу полей вручную с помощью сводной таблицы.|
| [set_ungroup](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_ungroup/#int) | Наборы разгруппируются с помощью сводной таблицы|
| [set_ungroup](/cells/python-net/ru/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Наборы разгруппируются с помощью сводной таблицы|
| [copy_style](/cells/python-net/ru/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Копирует именованный стиль из другой сводной таблицы.|
| [show_report_filter_page](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Показать все страницы фильтра отчета в соответствии с PivotField, PivotField должен находиться в PageFields.|
| [show_report_filter_page_by_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Показать все страницы фильтра отчета в соответствии с именем PivotField. PivotField должен находиться в PageFields.|
| [show_report_filter_page_by_index](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Показать все страницы фильтра отчета в соответствии с индексом позиции в PageFields.|
| [fields](/cells/python-net/ru/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Получает определенные поля по типу поля.|
| [change_data_source](/cells/python-net/ru/aspose.cells.pivot/pivottable/change_data_source/#list) |Установите исходные данные сводной таблицы.<br/> Лист1!$A$1:$C$3|
| [get_source](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_source/#) | Получите исходные данные сводной таблицы.|
| [refresh_data](/cells/python-net/ru/aspose.cells.pivot/pivottable/refresh_data/#) | Обновляет данные и настройки сводной таблицы из ее источника данных.|
| [calculate_data](/cells/python-net/ru/aspose.cells.pivot/pivottable/calculate_data/#) | Рассчитывает данные сводной таблицы по ячейкам.|
| [clear_data](/cells/python-net/ru/aspose.cells.pivot/pivottable/clear_data/#) | Очистить данные и форматирование сводной таблицы.|
| [calculate_range](/cells/python-net/ru/aspose.cells.pivot/pivottable/calculate_range/#) | Вычисляет диапазон сводной таблицы.|
| [format_all](/cells/python-net/ru/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Отформатировать всю ячейку в области сводной таблицы|
| [format_row](/cells/python-net/ru/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Форматирование данных строки в области сводной таблицы|
| [get_horizontal_breaks](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | получить список индексов строк сводной таблицы с горизонтальными разрывами страниц|
| [show_in_compact_form](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Макет сводной таблицы в компактной форме.|
| [show_in_outline_form](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Макет сводной таблицы в структурной форме.|
| [show_in_tabular_form](/cells/python-net/ru/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Размещает сводную таблицу в табличной форме.|
| [get_cell_by_display_name](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Получает объект [`Cell`](/cells/python-net/ru/aspose.cells/cell) по отображаемому имени PivotField.|
| [get_children](/cells/python-net/ru/aspose.cells.pivot/pivottable/get_children/#) | Получает дочерние сводные таблицы, которые используют данные сводной таблицы в качестве источника данных.|



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
