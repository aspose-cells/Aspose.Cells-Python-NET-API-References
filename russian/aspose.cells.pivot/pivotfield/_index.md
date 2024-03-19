---
title: PivotField класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 70
url: /ru/aspose.cells.pivot/pivotfield/
is_root: false
---
##  PivotField класс
Представляет поле в отчете сводной таблицы.



Тип PivotField предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [pivot_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/pivot_items) | Получает сводные элементы сводного поля.|
| [range](/cells/python-net/ru/aspose.cells.pivot/pivotfield/range) | Получает групповой диапазон сводного поля.|
| [group_settings](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_settings) | Получает параметры группы сводного поля.|
| [is_calculated_field](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_calculated_field) | Указывает, является ли указанное поле сводной таблицы вычисляемым полем.|
| [base_index](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_index) | Представляет индекс PivotField в базовых PivotFields.|
| [position](/cells/python-net/ru/aspose.cells.pivot/pivotfield/position) | Представляет собой индекс [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield) в регионе.|
| [name](/cells/python-net/ru/aspose.cells.pivot/pivotfield/name) |Представляет имя PivotField.|
| [display_name](/cells/python-net/ru/aspose.cells.pivot/pivotfield/display_name) | Представляет отображаемое имя PivotField.|
| [is_auto_subtotals](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_auto_subtotals) | Указывает, отображаются ли в указанном поле автоматические промежуточные итоги. По умолчанию верно.|
| [drag_to_column](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_column) | Указывает, можно ли перетащить указанное поле на позицию столбца.<br/> Значение по умолчанию верно.|
| [drag_to_hide](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_hide) | Указывает, можно ли перетащить указанное поле в положение скрытия.<br/> Значение по умолчанию верно.|
| [drag_to_row](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_row) | Указывает, можно ли перетащить указанное поле на позицию строки.<br/> Значение по умолчанию верно.|
| [drag_to_page](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_page) | Указывает, можно ли перетащить указанное поле на место страницы.<br/> Значение по умолчанию верно.|
| [drag_to_data](/cells/python-net/ru/aspose.cells.pivot/pivotfield/drag_to_data) | Указывает, можно ли перетащить указанное поле в положение данных.<br/> Значение по умолчанию верно.|
| [is_multiple_item_selection_allowed](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_multiple_item_selection_allowed) | указывает, может ли поле содержать несколько элементов<br/>выбрано в поле страницы<br/> Значение по умолчанию неверно.|
| [is_repeat_item_labels](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_repeat_item_labels) | указывает, может ли поле повторять метки элементов<br/> Значение по умолчанию неверно.|
| [is_include_new_items_in_filter](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_include_new_items_in_filter) | указывает, может ли поле включать новые элементы в ручной фильтр<br/> Значение по умолчанию неверно.|
| [is_insert_page_breaks_between_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_insert_page_breaks_between_items) | указывает, может ли поле вставлять разрывы страниц между элементами<br/>вставлять разрыв страницы после каждого элемента<br/> Значение по умолчанию неверно.|
| [show_all_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_all_items) | Указывает, отображаются ли все элементы в отчете сводной таблицы.<br/>даже если они не содержат сводных данных.<br/>показать элементы без данных<br/> Значение по умолчанию неверно.|
| [non_auto_sort_default](/cells/python-net/ru/aspose.cells.pivot/pivotfield/non_auto_sort_default) |Указывает, будет ли операция сортировки, которая будет применена к этому сводному полю, операцией автосортировки или простой сортировкой данных.|
| [is_auto_sort](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_auto_sort) | Указывает, сортируется ли указанное поле сводной таблицы автоматически.|
| [is_ascend_sort](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_ascend_sort) | Указывает, выполняется ли автосортировка по возрастанию указанного поля сводной таблицы.|
| [auto_sort_field](/cells/python-net/ru/aspose.cells.pivot/pivotfield/auto_sort_field) | Представляет индекс поля автосортировки.<br/> -1 означает сам PivotField, другие — положение полей данных.|
| [is_auto_show](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_auto_show) | Указывает, отображается ли указанное поле сводной таблицы автоматически. Действует только для Excel 2003.|
| [is_ascend_show](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_ascend_show) | Указывает, отображается ли указанное поле сводной таблицы автоматически по возрастанию.|
| [auto_show_count](/cells/python-net/ru/aspose.cells.pivot/pivotfield/auto_show_count) | Представлять количество верхних или нижних элементов<br/> которые автоматически отображаются в указанном поле сводной таблицы.|
| [auto_show_field](/cells/python-net/ru/aspose.cells.pivot/pivotfield/auto_show_field) | Представляет индекс поля автоматического показа. -1 означает сам PivotField.<br/> Это должен быть индекс полей данных.|
| [function](/cells/python-net/ru/aspose.cells.pivot/pivotfield/function) | Представляет функцию, используемую для суммирования поля данных сводной таблицы.|
| [data_display_format](/cells/python-net/ru/aspose.cells.pivot/pivotfield/data_display_format) | Представляет способ отображения значений, содержащихся в поле данных.|
| [base_field_index](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_field_index) |Представляет базовое поле для пользовательского расчета.|
| [base_item_position](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_item_position) | Представляет элемент в базовом поле для пользовательского расчета.<br/> Действительно только для полей данных.<br/>Поскольку PivotItemPosition.Custom предназначен только для чтения, если вам нужно установить PivotItemPosition.Custom,<br/> установите атрибут PivotField.BaseItemIndex.|
| [base_item_index](/cells/python-net/ru/aspose.cells.pivot/pivotfield/base_item_index) | Представляет элемент в базовом поле для пользовательского расчета.<br/> Действительно только для полей данных.|
| [current_page_item](/cells/python-net/ru/aspose.cells.pivot/pivotfield/current_page_item) | Представляет текущий элемент страницы, отображаемый для поля страницы (действительно только для полей страницы).|
| [number](/cells/python-net/ru/aspose.cells.pivot/pivotfield/number) | Представляет встроенный формат отображения чисел и дат.|
| [insert_blank_row](/cells/python-net/ru/aspose.cells.pivot/pivotfield/insert_blank_row) | Указывает, вставлять ли пустую строку после каждого элемента.|
| [show_subtotal_at_top](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_subtotal_at_top) | когда ShowInOutlineForm имеет значение true, промежуточные итоги отображаются вверху списка элементов, а не внизу.|
| [show_in_outline_form](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_in_outline_form) | Указывает, будет ли это поле отображаться в виде схемы в представлении сводной таблицы.|
| [number_format](/cells/python-net/ru/aspose.cells.pivot/pivotfield/number_format) | Представляет пользовательский формат отображения чисел и дат.|
| [items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/items) | Получите все базовые предметы;|
| [original_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/original_items) | Получите оригинальные базовые предметы;|
| [item_count](/cells/python-net/ru/aspose.cells.pivot/pivotfield/item_count) | Получает количество базовых элементов этого сводного поля.|
| [show_compact](/cells/python-net/ru/aspose.cells.pivot/pivotfield/show_compact) | Указывает, отображаются ли метки из следующего поля в том же столбце в представлении сводной таблицы.|


###  Методы
| Метод| Описание|
| :- | :- |
| [group_by](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#float-bool) | Автоматически группировать поле с внутренними|
| [group_by](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#DateTime-DateTime-list-float-bool) | Сгруппируйте файл по типам групп дат.|
| [group_by](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#float-float-float-bool) |Сгруппируйте файл по номеру.|
| [group_by](/cells/python-net/ru/aspose.cells.pivot/pivotfield/group_by/#list-bool) | Пользовательская группировка поля.|
| [hide_item](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_item/#int-bool) | Устанавливает, скрыт ли конкретный PivotItem в поле данных.|
| [hide_item](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_item/#str-bool) | Устанавливает, скрыт ли конкретный PivotItem в поле данных.|
| [get_pivot_filter_by_type](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_pivot_filter_by_type/#aspose.cells.pivot.PivotFilterType) | Получает сводный фильтр сводного поля по типу.|
| [get_pivot_filters](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_pivot_filters/#) | Получает сводные фильтры сводного поля.|
| [get_filters](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_filters/#) | Получает все сводные фильтры этого сводного поля.|
| [init_pivot_items](/cells/python-net/ru/aspose.cells.pivot/pivotfield/init_pivot_items/#) | Инициализировать элементы сводного поля|
| [ungroup](/cells/python-net/ru/aspose.cells.pivot/pivotfield/ungroup/#) | Разгруппируйте сводное поле.|
| [get_calculated_field_formula](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_calculated_field_formula/#) | Получите строку формулы указанного вычисляемого поля.|
| [set_subtotals](/cells/python-net/ru/aspose.cells.pivot/pivotfield/set_subtotals/#aspose.cells.pivot.PivotFieldSubtotalType-bool) | Устанавливает, отображаются ли в указанном поле эти промежуточные итоги.|
| [get_subtotals](/cells/python-net/ru/aspose.cells.pivot/pivotfield/get_subtotals/#aspose.cells.pivot.PivotFieldSubtotalType) | Указывает, отображается ли указанный промежуточный итог.|
| [is_hidden_item](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_hidden_item/#int) | Указывает, скрыт ли конкретный PivotItem.|
| [is_hidden_item_detail](/cells/python-net/ru/aspose.cells.pivot/pivotfield/is_hidden_item_detail/#int) | Указывает, является ли конкретный PivotItem скрытой деталью.|
| [hide_item_detail](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_item_detail/#int-bool) | Устанавливает, является ли конкретный PivotItem в сводном поле скрытой деталью.|
| [hide_detail](/cells/python-net/ru/aspose.cells.pivot/pivotfield/hide_detail/#bool) | Устанавливает, являются ли элементы PivotItems в сводном поле скрытыми деталями. То есть свернуть/развернуть это поле.|
| [add_calculated_item](/cells/python-net/ru/aspose.cells.pivot/pivotfield/add_calculated_item/#str-str) | Добавьте вычисляемый элемент в поле сводной таблицы.|



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
