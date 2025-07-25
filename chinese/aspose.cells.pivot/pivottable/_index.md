---
title: PivotTable类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 230
url: /zh/aspose.cells.pivot/pivottable/
is_root: false
---
## PivotTable类
PivotTable 的摘要说明。



PivotTable 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/zh/aspose.cells.pivot/pivottable/is_excel_2003_compatible) |指定刷新数据透视表时数据透视表是否兼容Excel2003，<br/>如果为 true，则字符串必须小于或等于 255 个字符，因此如果字符串大于 255 个字符，<br/>它将被截断。如果为假，则字符串将不会有上述限制。<br/>默认值为 true。|
| [refreshed_by_who](/cells/python-net/zh/aspose.cells.pivot/pivottable/refreshed_by_who) |获取最后刷新此数据透视表的用户的名称|
| [refresh_date](/cells/python-net/zh/aspose.cells.pivot/pivottable/refresh_date) |获取数据透视表上次刷新的日期时间。|
| [pivot_table_style_name](/cells/python-net/zh/aspose.cells.pivot/pivottable/pivot_table_style_name) |获取并设置数据透视表样式名称。|
| [pivot_table_style_type](/cells/python-net/zh/aspose.cells.pivot/pivottable/pivot_table_style_type) |获取并设置内置数据透视表样式。|
| [column_fields](/cells/python-net/zh/aspose.cells.pivot/pivottable/column_fields) |返回当前显示为列字段的 PivotFields 对象。|
| [row_fields](/cells/python-net/zh/aspose.cells.pivot/pivottable/row_fields) |返回当前显示为行字段的 PivotFields 对象。|
| [page_fields](/cells/python-net/zh/aspose.cells.pivot/pivottable/page_fields) |返回当前显示为页面字段的 PivotFields 对象。|
| [data_fields](/cells/python-net/zh/aspose.cells.pivot/pivottable/data_fields) |获取一个 PivotField 对象，该对象表示数据透视表中的所有数据字段。<br/>只读。仅当DataPiovtFiels中有两个或两个以上的数据字段时才会初始化。<br/>它仅用于将 DataPivotField 添加到数据透视表的行/列区域。默认在行区域。|
| [data_field](/cells/python-net/zh/aspose.cells.pivot/pivottable/data_field) |获取一个 [`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield) 对象，该对象表示数据透视表中的所有数据字段。<br/>只读。<br/>仅当数据区域中有两个或更多数据字段时才会创建它。<br/>默认位于行区域。您可以使用 PivotTable.AddFieldToArea() 方法将其拖到行/列区域。|
| [base_fields](/cells/python-net/zh/aspose.cells.pivot/pivottable/base_fields) |返回数据透视表中的所有基本数据透视字段。|
| [pivot_filters](/cells/python-net/zh/aspose.cells.pivot/pivottable/pivot_filters) |返回数据透视表中数据透视字段的所有过滤器。|
| [column_range](/cells/python-net/zh/aspose.cells.pivot/pivottable/column_range) |返回代表范围的 CellArea 对象<br/>包含数据透视表中的列区域。只读。|
| [row_range](/cells/python-net/zh/aspose.cells.pivot/pivottable/row_range) |返回代表范围的 CellArea 对象<br/>包含数据透视表中的行区域。只读。|
| [data_body_range](/cells/python-net/zh/aspose.cells.pivot/pivottable/data_body_range) |返回一个 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) 对象，该对象表示包含数据区域的范围<br/>位于标题行和插入行之间的列表中。只读。|
| [table_range1](/cells/python-net/zh/aspose.cells.pivot/pivottable/table_range1) |返回一个 CellArea 对象，该对象代表包含整个数据透视表的范围，<br/>但不包含页面字段。只读。|
| [table_range2](/cells/python-net/zh/aspose.cells.pivot/pivottable/table_range2) |返回一个 CellArea 对象，该对象代表包含整个数据透视表的范围，<br/>包含页面字段。只读。|
| [is_grid_drop_zones](/cells/python-net/zh/aspose.cells.pivot/pivottable/is_grid_drop_zones) |指示数据透视表是否显示经典数据透视表布局。<br/> （允许在网格中拖动字段）|
| [show_column_grand_totals](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_column_grand_totals) |指示是否显示此数据透视表的列总计。|
| [show_row_grand_totals](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_row_grand_totals) |指示是否显示数据透视表各行的总计。|
| [column_grand](/cells/python-net/zh/aspose.cells.pivot/pivottable/column_grand) |指示数据透视表是否显示列的总计。|
| [row_grand](/cells/python-net/zh/aspose.cells.pivot/pivottable/row_grand) |指示是否显示此数据透视表各行的总计。|
| [display_null_string](/cells/python-net/zh/aspose.cells.pivot/pivottable/display_null_string) |指示当值为空时数据透视表是否显示自定义字符串。|
| [null_string](/cells/python-net/zh/aspose.cells.pivot/pivottable/null_string) |获取包含空值的单元格中显示的字符串<br/>当DisplayNullString属性为true时，默认值为空字符串。|
| [display_error_string](/cells/python-net/zh/aspose.cells.pivot/pivottable/display_error_string) |指示数据透视表是否在包含错误的单元格中显示自定义字符串。|
| [data_field_header_name](/cells/python-net/zh/aspose.cells.pivot/pivottable/data_field_header_name) |获取并设置数据透视表中值区域字段标题的名称。|
| [error_string](/cells/python-net/zh/aspose.cells.pivot/pivottable/error_string) |获取包含错误的单元格中显示的字符串<br/>当 DisplayErrorString 属性为 true 时，默认值为空字符串。|
| [is_auto_format](/cells/python-net/zh/aspose.cells.pivot/pivottable/is_auto_format) |指示数据透视表是否自动格式化。<br/>勾选“自动套用表格格式”，这是 Excel 2003 数据透视表选项中的一项|
| [autofit_column_width_on_update](/cells/python-net/zh/aspose.cells.pivot/pivottable/autofit_column_width_on_update) |指示更新时是否自动调整列宽|
| [auto_format_type](/cells/python-net/zh/aspose.cells.pivot/pivottable/auto_format_type) |获取并设置数据透视表的自动格式类型。|
| [has_blank_rows](/cells/python-net/zh/aspose.cells.pivot/pivottable/has_blank_rows) |指示是否添加空白行。<br/>此属性仅适用于需要添加空行的透视表自动格式类型。|
| [merge_labels](/cells/python-net/zh/aspose.cells.pivot/pivottable/merge_labels) |如果指定的数据透视表的外部行项、列项、小计和总计标签使用合并单元格，则为 True。|
| [preserve_formatting](/cells/python-net/zh/aspose.cells.pivot/pivottable/preserve_formatting) |指示刷新或重新计算数据透视表时是否保留格式。|
| [show_drill](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_drill) |获取或设置是否显示展开/折叠按钮。|
| [enable_drilldown](/cells/python-net/zh/aspose.cells.pivot/pivottable/enable_drilldown) |获取是否启用下钻。|
| [enable_field_dialog](/cells/python-net/zh/aspose.cells.pivot/pivottable/enable_field_dialog) |指示数据透视表字段对话框是否可用<br/>当用户双击数据透视表字段时。|
| [enable_field_list](/cells/python-net/zh/aspose.cells.pivot/pivottable/enable_field_list) |指示数据透视表的字段列表是否在 Excel 视图上可用。|
| [enable_wizard](/cells/python-net/zh/aspose.cells.pivot/pivottable/enable_wizard) |指示数据透视表向导是否可用。|
| [subtotal_hidden_page_items](/cells/python-net/zh/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |指示数据透视表中是否隐藏页面字段项<br/>包括在行和列小计、块总计和总计中。<br/>默认值为 False。|
| [grand_total_name](/cells/python-net/zh/aspose.cells.pivot/pivottable/grand_total_name) |返回总计列或行标题中显示的标签。<br/>默认值是字符串“Grand Total”。|
| [manual_update](/cells/python-net/zh/aspose.cells.pivot/pivottable/manual_update) |指示是否仅在用户请求时重新计算数据透视表。|
| [is_multiple_field_filters](/cells/python-net/zh/aspose.cells.pivot/pivottable/is_multiple_field_filters) |指定一个布尔值，指示数据透视表的字段是否可以设置多个过滤器。|
| [allow_multiple_filters_per_field](/cells/python-net/zh/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) |指定一个布尔值，指示数据透视表的字段是否可以设置多个过滤器。|
| [missing_items_limit](/cells/python-net/zh/aspose.cells.pivot/pivottable/missing_items_limit) |指定一个布尔值，指示数据透视表的字段是否可以设置多个过滤器。|
| [enable_data_value_editing](/cells/python-net/zh/aspose.cells.pivot/pivottable/enable_data_value_editing) |指定一个布尔值，指示是否允许用户编辑数据透视表数据区域中的单元格。<br/>在值区域中启用单元格编辑|
| [show_data_tips](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_data_tips) |指定一个布尔值，指示是否应为数据透视表数据单元格显示工具提示。|
| [show_member_property_tips](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_member_property_tips) |指定一个布尔值，指示是否应从数据透视表工具提示中省略成员属性信息。|
| [show_values_row](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_values_row) |指示是否显示值行。|
| [show_empty_col](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_empty_col) |指示是否在表中包含空列|
| [show_empty_row](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_empty_row) |指示是否在表中包含空行。|
| [field_list_sort_ascending](/cells/python-net/zh/aspose.cells.pivot/pivottable/field_list_sort_ascending) |指示数据透视表中的字段是否按字段列表中的非默认顺序排序。|
| [print_drill](/cells/python-net/zh/aspose.cells.pivot/pivottable/print_drill) |指定一个布尔值，指示是否应打印钻取指示器。<br/>在数据透视表上显示时打印展开/折叠按钮。|
| [alt_text_title](/cells/python-net/zh/aspose.cells.pivot/pivottable/alt_text_title) |获取并设置改变文本的标题。|
| [alt_text_description](/cells/python-net/zh/aspose.cells.pivot/pivottable/alt_text_description) |获取 alt 文本的描述。|
| [name](/cells/python-net/zh/aspose.cells.pivot/pivottable/name) |获取数据透视表的名称|
| [column_header_caption](/cells/python-net/zh/aspose.cells.pivot/pivottable/column_header_caption) |获取数据透视表的列标题。|
| [indent](/cells/python-net/zh/aspose.cells.pivot/pivottable/indent) |指定紧凑轴的缩进增量，可用于将报告布局设置为紧凑形式。|
| [row_header_caption](/cells/python-net/zh/aspose.cells.pivot/pivottable/row_header_caption) |获取数据透视表的行标题。|
| [show_row_header_caption](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_row_header_caption) |指示数据透视表中是否显示行标题<br/>指示是否显示字段标题和过滤器下拉菜单|
| [custom_list_sort](/cells/python-net/zh/aspose.cells.pivot/pivottable/custom_list_sort) |指示排序数据时是否考虑内置自定义列表|
| [pivot_format_conditions](/cells/python-net/zh/aspose.cells.pivot/pivottable/pivot_format_conditions) |获取数据透视表的格式条件。|
| [conditional_formats](/cells/python-net/zh/aspose.cells.pivot/pivottable/conditional_formats) |获取数据透视表的条件格式。|
| [page_field_order](/cells/python-net/zh/aspose.cells.pivot/pivottable/page_field_order) |获取并设置页面字段添加到数据透视表布局的顺序。|
| [page_field_wrap_count](/cells/python-net/zh/aspose.cells.pivot/pivottable/page_field_wrap_count) |获取数据透视表中每列或每行的页字段数。|
| [tag](/cells/python-net/zh/aspose.cells.pivot/pivottable/tag) |获取随数据透视表报告保存的字符串。|
| [save_data](/cells/python-net/zh/aspose.cells.pivot/pivottable/save_data) |指示数据透视表的数据是否与工作簿一起保存。|
| [refresh_data_on_opening_file](/cells/python-net/zh/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) |指示打开文件时是否刷新数据。|
| [refresh_data_flag](/cells/python-net/zh/aspose.cells.pivot/pivottable/refresh_data_flag) |指示是否刷新数据。|
| [source_type](/cells/python-net/zh/aspose.cells.pivot/pivottable/source_type) |获取数据透视表的数据源类型。|
| [external_connection_data_source](/cells/python-net/zh/aspose.cells.pivot/pivottable/external_connection_data_source) |获取外部连接数据源。|
| [data_source](/cells/python-net/zh/aspose.cells.pivot/pivottable/data_source) |获取并设置数据透视表的数据源。|
| [pivot_formats](/cells/python-net/zh/aspose.cells.pivot/pivottable/pivot_formats) |获取应用于数据透视表的格式的集合。|
| [item_print_titles](/cells/python-net/zh/aspose.cells.pivot/pivottable/item_print_titles) |指示是否应在每个打印页面的顶部重复 PivotItem 名称。|
| [repeat_items_on_each_printed_page](/cells/python-net/zh/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) |指示行区域上的数据透视表项标题是否在表格形式的数据透视表字段的每个打印页面上重复。|
| [print_titles](/cells/python-net/zh/aspose.cells.pivot/pivottable/print_titles) |指示工作表的打印标题是否基于<br/>在数据透视表上。默认值为 false。|
| [display_immediate_items](/cells/python-net/zh/aspose.cells.pivot/pivottable/display_immediate_items) |指示行和列区域中的项目是否可见<br/>当数据透视表的数据区域为空时。默认值为 true。|
| [is_selected](/cells/python-net/zh/aspose.cells.pivot/pivottable/is_selected) |指示是否选择了此数据透视表。|
| [show_pivot_style_row_header](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_pivot_style_row_header) |指示数据透视表中的行标题是否应应用该样式。|
| [show_pivot_style_column_header](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_pivot_style_column_header) |指示数据透视表中的列标题是否应应用该样式。|
| [show_pivot_style_row_stripes](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) |指示是否应用行条纹格式。|
| [show_pivot_style_column_stripes](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) |指示是否对列应用条纹格式。|
| [show_pivot_style_last_column](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_pivot_style_last_column) |指示是否应用列格式。|


### 方法
|方法|描述|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) |从特定字段区域中删除字段|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) |从特定字段区域中删除字段|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) |从特定字段区域删除字段|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) |将字段添加到特定区域。|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) |将字段添加到特定区域。|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) |将字段添加到特定区域。|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) |向数据透视表字段添加计算字段。|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) |将计算字段添加到数据透视字段并将其拖动到数据区域。|
| [`move(self, row, column)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/move/#int-int) |将数据透视表移动到工作表中的其他位置。|
| [`move(self, dest_cell_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/move/#str) |将数据透视表移动到工作表中的其他位置。|
| [`move_to(self, row, column)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/move_to/#int-int) |将数据透视表移动到工作表中的其他位置。|
| [`move_to(self, dest_cell_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/move_to/#str) |将数据透视表移动到工作表中的其他位置。|
| [`get_source(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_source/#) |获取数据透视表的源数据。|
| [`get_source(self, is_original)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_source/#bool) |获取数据透视表的源数据。|
| [`refresh_data(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/refresh_data/#) |从数据源刷新数据透视表的数据和设置。|
| [`refresh_data(self, option)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) |使用选项从数据源刷新数据透视表的数据和设置。|
| [`calculate_data(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/calculate_data/#) |将数据透视表的数据计算到单元格。|
| [`calculate_data(self, option)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) |使用选项计算数据透视表|
| [`format(self, pivot_area, style)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) |格式化数据透视表的选定区域。|
| [`format(self, ca, style)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) |格式化数据透视表的选定区域。|
| [`format(self, row, column, style)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) |设置数据透视表区域中单元格的格式|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_auto_group_field/#int) |通过数据透视表设置自动字段组。|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) |通过数据透视表设置自动字段组。|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) |通过数据透视表设置手动字段组。|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) |通过数据透视表设置手动字段组。|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) |通过数据透视表设置手动字段组。|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) |通过数据透视表设置手动字段组。|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_ungroup/#int) |通过数据透视表设置取消分组|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) |通过数据透视表设置取消分组|
| [`copy_style(self, pivot_table)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) |从另一个数据透视表复制命名样式。|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) |根据PivotField显示所有报表过滤页面，PivotField必须位于PageFields中。|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) |根据 PivotField 的名称显示所有报表过滤页面，PivotField 必须位于 PageFields 中。|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) |根据PageFields中的位置索引显示所有报表过滤页面|
| [`get_fields(self, field_type)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) |获取按地区划分的具体数据透视字段列表。|
| [`fields(self, field_type)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) |根据字段类型获取具体字段。|
| [`get_source_data_connections(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_source_data_connections/#) |获取外部连接数据源。|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) |获取外部源数据连接的名称。|
| [`change_data_source(self, source)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/change_data_source/#list) |设置数据透视表的源数据。|
| [`clear_data(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/clear_data/#) |清除数据透视表的数据和格式|
| [`calculate_range(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/calculate_range/#) |计算数据透视表的范围。|
| [`format_all(self, style)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) |格式化数据透视表区域中的所有单元格|
| [`format_row(self, row, style)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) |格式化数据透视表区域中的行数据|
| [`select_area(self, ca)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) |选择数据透视表视图的一个区域。|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) |将数据区域中某一项的详细信息显示到新表中。|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) |获取此数据透视表的水平分页符。|
| [`get_horizontal_breaks(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) |获取水平分页符的数据透视表行索引列表|
| [`show_in_compact_form(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_in_compact_form/#) |以紧凑形式布局数据透视表。|
| [`show_in_outline_form(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_in_outline_form/#) |以大纲形式布局数据透视表。|
| [`show_in_tabular_form(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/show_in_tabular_form/#) |以表格形式布局数据透视表。|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) |通过 PivotField 的显示名称获取 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 对象。|
| [`get_children(self)`](/cells/python-net/zh/aspose.cells.pivot/pivottable/get_children/#) |获取使用此数据透视表数据作为数据源的子数据透视表。|



### 例子

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

### 也可以看看
* 模块[`aspose.cells.pivot`](..)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
* 类 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea)
* 类 [`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield)
