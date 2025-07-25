---
title: PivotField класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells.pivot/pivotfield/
is_root: false
---
##  PivotField класс
Представляет поле в отчете сводной таблицы.



Тип PivotField предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [pivot_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/pivot_items) | Получает опорные элементы опорного поля|
| [range](/cells/python-net/ru/aspose.cells.pivot/pivotfield/range) | Получает диапазон группы поля опорной точки|
| [group_settings](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_settings) | Получает групповые настройки поля сводки.|
| [is_calculated_field](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_calculated_field) | Указывает, является ли указанное поле сводной таблицы вычисляемым полем.|
| [is_value_fields](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_value_fields) | Указывает, представляет ли это поле поля значений.|
| [base_index](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_index) | Представляет индекс PivotField в базовых PivotFields.|
| [position](/cells/python-net/ru/aspose.cells.pivot/pivotfield/position) | Представляет индекс [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield) в регионе.|
| [region_type](/cells/python-net/ru/aspose.cells.pivot/pivotfield/region_type) | Указывает область сводной таблицы, в которой отображается это поле.|
| [name](/cells/python-net/ru/aspose.cells.pivot/pivotfield/name) | Представляет имя PivotField.|
| [display_name](/cells/python-net/ru/aspose.cells.pivot/pivotfield/display_name) | Представляет отображаемое имя PivotField.|
| [is_auto_subtotals](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_auto_subtotals) | Указывает, отображаются ли в указанном поле автоматические промежуточные итоги. Значение по умолчанию — true.|
| [drag_to_column](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_column) | Указывает, можно ли перетащить указанное поле в позицию столбца.<br/> Значение по умолчанию — true.|
| [drag_to_hide](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_hide) | Указывает, можно ли перетащить указанное поле в положение скрытия.<br/> Значение по умолчанию — true.|
| [drag_to_row](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_row) | Указывает, можно ли перетащить указанное поле в позицию строки.<br/> Значение по умолчанию — true.|
| [drag_to_page](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_page) |Указывает, можно ли перетащить указанное поле на страницу.<br/> Значение по умолчанию — true.|
| [drag_to_data](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_data) | Указывает, можно ли перетащить указанное поле в позицию данных.<br/> Значение по умолчанию — true.|
| [is_multiple_item_selection_allowed](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_multiple_item_selection_allowed) | указывает, может ли поле иметь несколько элементов<br/>выбрано в поле страницы<br/> Значение по умолчанию — false.|
| [is_repeat_item_labels](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_repeat_item_labels) | Указывает, повторяются ли метки поля в регионе.<br/> Значение по умолчанию — false.|
| [is_include_new_items_in_filter](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_include_new_items_in_filter) | Указывает, следует ли включать новые элементы в поле при ручном фильтре.<br/> Значение по умолчанию — false.|
| [is_insert_page_breaks_between_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_insert_page_breaks_between_items) | Указывает, будет ли вставка разрыва страницы после каждого элемента.<br/> Значение по умолчанию — false.|
| [show_all_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_all_items) | Указывает, отображаются ли все элементы в отчете сводной таблицы,<br/>даже если они не содержат сводных данных.<br/>показать элементы без данных<br/> Значение по умолчанию — false.|
| [non_auto_sort_default](/cells/python-net/ru/aspose.cells.pivot/pivotfield/non_auto_sort_default) | Указывает, является ли операция сортировки, которая будет применена к этому полю сводной таблицы, операцией автоматической сортировки или простой сортировкой данных.|
| [is_auto_sort](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_auto_sort) | Указывает, сортируется ли указанное поле сводной таблицы автоматически.|
| [is_ascend_sort](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_ascend_sort) | Указывает, сортируется ли указанное поле сводной таблицы автоматически по возрастанию.|
| [sort_setting](/cells/python-net/ru/aspose.cells.pivot/pivotfield/sort_setting) | Получает все настройки автосортировки|
| [auto_sort_field](/cells/python-net/ru/aspose.cells.pivot/pivotfield/auto_sort_field) | Представляет индекс поля, которое сортируется автоматически.<br/> -1 означает само PivotField, остальные означают положение полей данных.|
| [is_auto_show](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_auto_show) |Указывает, отображается ли указанное поле сводной таблицы автоматически. Действительно только для Excel 2003.|
| [is_ascend_show](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_ascend_show) | Указывает, отображается ли указанное поле сводной таблицы автоматически по возрастанию.|
| [auto_show_count](/cells/python-net/ru/aspose.cells.pivot/pivotfield/auto_show_count) | Представляет количество верхних или нижних элементов<br/> которые автоматически отображаются в указанном поле сводной таблицы.|
| [auto_show_field](/cells/python-net/ru/aspose.cells.pivot/pivotfield/auto_show_field) | Представляет индекс поля автоматического показа. -1 означает сам PivotField.<br/> Это должен быть индекс полей данных.|
| [function](/cells/python-net/ru/aspose.cells.pivot/pivotfield/function) | Представляет функцию, используемую для суммирования поля данных сводной таблицы.|
| [show_values_setting](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_values_setting) | Получает настройки отображения значений, когда используется расчет ShowDataAs.|
| [data_display_format](/cells/python-net/ru/aspose.cells.pivot/pivotfield/data_display_format) | Показывает, как отображать значения в поле данных сводного отчета.|
| [base_field_index](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_field_index) | Представляет базовое поле для пользовательского расчета, когда используется расчет ShowDataAs.|
| [base_item_position](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_item_position) | Представляет элемент в базовом поле для пользовательского расчета, когда используется расчет ShowDataAs.<br/> Действительно только для полей данных.<br/>Поскольку PivotItemPosition.Custom предназначен только для чтения, если вам нужно установить PivotItemPosition.Custom,<br/> пожалуйста, установите атрибут PivotField.BaseItemIndex.|
| [base_item_index](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_item_index) | Представляет элемент в базовом поле для пользовательского расчета, когда используется расчет ShowDataAs.<br/> Действительно только для полей данных.|
| [current_page_item](/cells/python-net/ru/aspose.cells.pivot/pivotfield/current_page_item) |Представляет текущий элемент страницы, отображаемый для поля страницы (действительно только для полей страницы).|
| [number](/cells/python-net/ru/aspose.cells.pivot/pivotfield/number) | Представляет встроенный формат отображения чисел и дат.|
| [insert_blank_row](/cells/python-net/ru/aspose.cells.pivot/pivotfield/insert_blank_row) | Указывает, следует ли вставлять пустую строку после каждого элемента.|
| [show_subtotal_at_top](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_subtotal_at_top) | если ShowInOutlineForm имеет значение true, то отображать промежуточные итоги в верхней части списка элементов, а не в нижней.|
| [show_in_outline_form](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_in_outline_form) | Указывает, следует ли отображать это поле в виде структуры в представлении сводной таблицы.|
| [number_format](/cells/python-net/ru/aspose.cells.pivot/pivotfield/number_format) | Представляет собой пользовательский формат отображения чисел и дат.|
| [items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/items) | Получить все метки элементов сводки в этом поле.|
| [original_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/original_items) | Получите оригинальные базовые предметы;|
| [item_count](/cells/python-net/ru/aspose.cells.pivot/pivotfield/item_count) | Получает количество базовых элементов в этом сводном поле.|
| [show_compact](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_compact) | Указывает, отображать ли метки из следующего поля в том же столбце в представлении сводной таблицы.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`group_by(self, interval, new_field)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#float-bool) | Автоматически группировать поле с внутренними|
| [`group_by(self, start, end, groups, interval, first_as_new_field)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#datetime-datetime-list-float-bool) | Сгруппируйте файл по типу группы дат.|
| [`group_by(self, start, end, interval, new_field)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#float-float-float-bool) | Сгруппируйте файл по номеру.|
| [`group_by(self, custom_group_items, new_field)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#list-bool) | Пользовательская группа полей.|
| [`sort_by(self, sort_type, field_sorted_by)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/sort_by/#aspose.cells.sortorder-int) | Сортирует это опорное поле.|
| [`sort_by(self, sort_type, field_sorted_by, data_type, cell_name)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/sort_by/#aspose.cells.sortorder-int-aspose.cells.pivot.pivotlinetype-str) | Сортирует это опорное поле.|
| [`hide_item(self, index, is_hidden)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_item/#int-bool) | Устанавливает, будет ли скрыт определенный PivotItem в поле данных.|
| [`hide_item(self, item_value, is_hidden)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_item/#str-bool) | Устанавливает, будет ли скрыт определенный PivotItem в поле данных.|
| [`init_pivot_items(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/init_pivot_items/#) |Инициализируйте элементы опорной области опорной области.|
| [`ungroup(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/ungroup/#) | Разгруппируйте поле поворота.|
| [`get_pivot_filter_by_type(self, type)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_pivot_filter_by_type/#aspose.cells.pivot.pivotfiltertype) | Получает фильтр сводной таблицы для поля сводной таблицы по типу|
| [`get_pivot_filters(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_pivot_filters/#) | Получает фильтры опорной области опорного поля|
| [`get_filters(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_filters/#) | Получает все фильтры сводки для этого поля сводки.|
| [`clear_filter(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/clear_filter/#) | Очищает настройки фильтра для этого поля сводки.|
| [`filter_top10(self, value_field_index, type, is_top, item_count)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/filter_top10/#int-aspose.cells.pivot.pivotfiltertype-bool-int) | Фильтрует по значениям поля сводных данных.|
| [`filter_by_value(self, value_field_index, type, value1, value2)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/filter_by_value/#int-aspose.cells.pivot.pivotfiltertype-float-float) | Фильтрует по значениям поля сводных данных.|
| [`filter_by_label(self, type, label1, label2)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/filter_by_label/#aspose.cells.pivot.pivotfiltertype-str-str) | Фильтрует по заголовкам поля сводной строки или столбца.|
| [`filter_by_date(self, type, date_time1, date_time2)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/filter_by_date/#aspose.cells.pivot.pivotfiltertype-datetime-datetime) | Фильтрует по настройке даты сводного поля строки или столбца.|
| [`get_calculated_field_formula(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_calculated_field_formula/#) | Получить строку формулы указанного вычисляемого поля.|
| [`get_formula(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_formula/#) | Получает формулу вычисляемого поля.|
| [`set_subtotals(self, subtotal_type, shown)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/set_subtotals/#aspose.cells.pivot.pivotfieldsubtotaltype-bool) | Устанавливает, отображает ли указанное поле промежуточные итоги.|
| [`get_subtotals(self, subtotal_type)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_subtotals/#aspose.cells.pivot.pivotfieldsubtotaltype) | Указывает, отображается ли указанный промежуточный итог.|
| [`show_values_as(self, display_format, base_field, base_item_position_type, base_item)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_values_as/#aspose.cells.pivot.pivotfielddatadisplayformat-int-aspose.cells.pivot.pivotitempositiontype-int) | Показывает значения поля данных в другом формате отображения, если используется расчет ShowDataAs.|
| [`is_hidden_item(self, index)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_hidden_item/#int) | Указывает, скрыт ли конкретный PivotItem.|
| [`is_hidden_item_detail(self, index)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_hidden_item_detail/#int) | Получает информацию о том, скрыты ли сведения о конкретном PivotItem.|
| [`hide_item_detail(self, index, is_hidden_detail)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_item_detail/#int-bool) | Устанавливает, является ли конкретный PivotItem в поле сводки скрытой информацией.|
| [`hide_detail(self, is_hidden_detail)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_detail/#bool) |Устанавливает, является ли PivotItems в поле сводки скрытой информацией. То есть сворачивает/разворачивает это поле.|
| [`add_calculated_item(self, name, formula)`](/cells/python-net/ru/aspose.cells.pivot/pivotfield/add_calculated_item/#str-str) | Добавьте вычисляемый элемент формулы в поле сводной таблицы.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

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
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
* класс [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield)
