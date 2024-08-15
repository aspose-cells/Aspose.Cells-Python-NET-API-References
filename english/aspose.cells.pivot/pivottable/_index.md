---
title: PivotTable class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 200
url: /aspose.cells.pivot/pivottable/
is_root: false
---

## PivotTable class

Summary description for PivotTable.



The PivotTable type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Specifies whether the PivotTable is compatible for Excel2003 when refreshing PivotTable,<br/>if true, a string must be less than or equal to 255 characters, so if the string is greater than 255 characters,<br/>it will be truncated. if false, a string will not have the aforementioned restriction.<br/>The default value is true. |
| [refreshed_by_who](/cells/python-net/aspose.cells.pivot/pivottable/refreshed_by_who) | Gets the name of the last user who refreshed this PivotTable |
| [refresh_date](/cells/python-net/aspose.cells.pivot/pivottable/refresh_date) | Gets the last date time when the PivotTable was refreshed. |
| [pivot_table_style_name](/cells/python-net/aspose.cells.pivot/pivottable/pivot_table_style_name) | Gets and sets the pivottable style name. |
| [pivot_table_style_type](/cells/python-net/aspose.cells.pivot/pivottable/pivot_table_style_type) | Gets and sets the built-in pivot table style. |
| [column_fields](/cells/python-net/aspose.cells.pivot/pivottable/column_fields) | Returns a PivotFields object that are currently shown as column fields. |
| [row_fields](/cells/python-net/aspose.cells.pivot/pivottable/row_fields) | Returns a PivotFields object that are currently shown as row fields. |
| [page_fields](/cells/python-net/aspose.cells.pivot/pivottable/page_fields) | Returns a PivotFields object that are currently shown as page fields. |
| [data_fields](/cells/python-net/aspose.cells.pivot/pivottable/data_fields) | Gets a PivotField object that represents all the data fields in a PivotTable.<br/>Read-only.It would be init only when there are two or more data fields in the DataPiovtFiels.<br/>It only use to add DataPivotField to the PivotTable row/column area . Default is in row area. |
| [data_field](/cells/python-net/aspose.cells.pivot/pivottable/data_field) | Gets a [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield) object that represents all the data fields in a PivotTable.<br/>Read-only.<br/>It would only be created when there are two or more data fields in the Data region.<br/>Defaultly it is in row region. You can drag it to the row/column region with PivotTable.AddFieldToArea() method . |
| [base_fields](/cells/python-net/aspose.cells.pivot/pivottable/base_fields) | Returns all base pivot fields in the PivotTable. |
| [pivot_filters](/cells/python-net/aspose.cells.pivot/pivottable/pivot_filters) | Returns a list of pivot filters. |
| [column_range](/cells/python-net/aspose.cells.pivot/pivottable/column_range) | Returns a CellArea object that represents the range<br/>that contains the column area in the PivotTable report. Read-only. |
| [row_range](/cells/python-net/aspose.cells.pivot/pivottable/row_range) | Returns a CellArea object that represents the range<br/>that contains the row area in the PivotTable report. Read-only. |
| [data_body_range](/cells/python-net/aspose.cells.pivot/pivottable/data_body_range) | Returns a [`CellArea`](/cells/python-net/aspose.cells/cellarea) object that represents the range that contains the data area<br/>in the list between the header row and the insert row. Read-only. |
| [table_range1](/cells/python-net/aspose.cells.pivot/pivottable/table_range1) | Returns a CellArea object that represents the range containing the entire PivotTable report,<br/>but doesn't include page fields. Read-only. |
| [table_range2](/cells/python-net/aspose.cells.pivot/pivottable/table_range2) | Returns a CellArea object that represents the range containing the entire PivotTable report,<br/>includes page fields. Read-only. |
| [column_grand](/cells/python-net/aspose.cells.pivot/pivottable/column_grand) | Indicates whether the PivotTable report shows grand totals for columns. |
| [is_grid_drop_zones](/cells/python-net/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Indicates whether the PivotTable report displays classic pivottable layout.<br/>(enables dragging fields in the grid) |
| [row_grand](/cells/python-net/aspose.cells.pivot/pivottable/row_grand) | Indicates whether the PivotTable report shows grand totals for rows. |
| [display_null_string](/cells/python-net/aspose.cells.pivot/pivottable/display_null_string) | Indicates whether the PivotTable report displays a custom string if the value is null. |
| [null_string](/cells/python-net/aspose.cells.pivot/pivottable/null_string) | Gets the string displayed in cells that contain null values<br/>when the DisplayNullString property is true.The default value is an empty string. |
| [display_error_string](/cells/python-net/aspose.cells.pivot/pivottable/display_error_string) | Indicates whether the PivotTable report displays a custom string in cells that contain errors. |
| [data_field_header_name](/cells/python-net/aspose.cells.pivot/pivottable/data_field_header_name) | Gets and sets the name of the value area field header in the PivotTable. |
| [error_string](/cells/python-net/aspose.cells.pivot/pivottable/error_string) | Gets the string displayed in cells that contain errors<br/>when the DisplayErrorString property is true.The default value is an empty string. |
| [is_auto_format](/cells/python-net/aspose.cells.pivot/pivottable/is_auto_format) | Indicates whether the PivotTable report is automatically formatted.<br/>Checkbox "autoformat table " which is in pivottable option for Excel 2003 |
| [autofit_column_width_on_update](/cells/python-net/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Indicates whether autofitting column width on update |
| [auto_format_type](/cells/python-net/aspose.cells.pivot/pivottable/auto_format_type) | Gets and sets the auto format type of PivotTable. |
| [has_blank_rows](/cells/python-net/aspose.cells.pivot/pivottable/has_blank_rows) | Indicates whether to add blank rows.<br/>This property only applies for the PivotTable auto format types which needs to add blank rows. |
| [merge_labels](/cells/python-net/aspose.cells.pivot/pivottable/merge_labels) | True if the specified PivotTable report's outer-row item, column item, subtotal, and grand total labels use merged cells. |
| [preserve_formatting](/cells/python-net/aspose.cells.pivot/pivottable/preserve_formatting) | Indicates whether formatting is preserved when the PivotTable is refreshed or recalculated. |
| [show_drill](/cells/python-net/aspose.cells.pivot/pivottable/show_drill) | Gets and sets whether showing expand/collapse buttons. |
| [enable_drilldown](/cells/python-net/aspose.cells.pivot/pivottable/enable_drilldown) | Gets whether drilldown is enabled. |
| [enable_field_dialog](/cells/python-net/aspose.cells.pivot/pivottable/enable_field_dialog) | Indicates whether the PivotTable Field dialog box is available<br/>when the user double-clicks the PivotTable field. |
| [enable_field_list](/cells/python-net/aspose.cells.pivot/pivottable/enable_field_list) | Gets whether enable the field list for the PivotTable. |
| [enable_wizard](/cells/python-net/aspose.cells.pivot/pivottable/enable_wizard) | Indicates whether the PivotTable Wizard is available. |
| [subtotal_hidden_page_items](/cells/python-net/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Indicates whether hidden page field items in the PivotTable report<br/>are included in row and column subtotals, block totals, and grand totals.<br/>The default value is False. |
| [grand_total_name](/cells/python-net/aspose.cells.pivot/pivottable/grand_total_name) | Returns the text string label that is displayed in the grand total column or row heading.<br/>The default value is the string "Grand Total". |
| [manual_update](/cells/python-net/aspose.cells.pivot/pivottable/manual_update) | Indicates whether the PivotTable report is recalculated only at the user's request. |
| [is_multiple_field_filters](/cells/python-net/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Specifies a boolean value that indicates whether the fields of a PivotTable can have multiple filters set on them. |
| [missing_items_limit](/cells/python-net/aspose.cells.pivot/pivottable/missing_items_limit) | Specifies a boolean value that indicates whether the fields of a PivotTable can have multiple filters set on them. |
| [enable_data_value_editing](/cells/python-net/aspose.cells.pivot/pivottable/enable_data_value_editing) | Specifies a boolean value that indicates whether the user is allowed to edit the cells in the data area of the pivottable.<br/>Enable cell editing in the values area |
| [show_data_tips](/cells/python-net/aspose.cells.pivot/pivottable/show_data_tips) | Specifies a boolean value that indicates whether tooltips should be displayed for PivotTable data cells. |
| [show_member_property_tips](/cells/python-net/aspose.cells.pivot/pivottable/show_member_property_tips) | Specifies a boolean value that indicates whether member property information should be omitted from PivotTable tooltips. |
| [show_values_row](/cells/python-net/aspose.cells.pivot/pivottable/show_values_row) | Specifies a boolean value that indicates whether show values row.<br/>show the values row |
| [show_empty_col](/cells/python-net/aspose.cells.pivot/pivottable/show_empty_col) | Specifies a boolean value that indicates whether to include empty columns in the table |
| [show_empty_row](/cells/python-net/aspose.cells.pivot/pivottable/show_empty_row) | Specifies a boolean value that indicates whether to include empty rows in the table. |
| [field_list_sort_ascending](/cells/python-net/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Indicates whether fields in the PivotTable are sorted in non-default order in the field list. |
| [print_drill](/cells/python-net/aspose.cells.pivot/pivottable/print_drill) | Specifies a boolean value that indicates whether drill indicators should be printed.<br/>print expand/collapse buttons when displayed on pivottable. |
| [alt_text_title](/cells/python-net/aspose.cells.pivot/pivottable/alt_text_title) | Gets and sets the title of the alter text. |
| [alt_text_description](/cells/python-net/aspose.cells.pivot/pivottable/alt_text_description) | Gets the description of the alt text. |
| [name](/cells/python-net/aspose.cells.pivot/pivottable/name) | Gets the name of the PivotTable |
| [column_header_caption](/cells/python-net/aspose.cells.pivot/pivottable/column_header_caption) | Gets the Column Header Caption of the PivotTable. |
| [indent](/cells/python-net/aspose.cells.pivot/pivottable/indent) | Specifies the indentation increment for compact axis and can be used to set the Report Layout to Compact Form. |
| [row_header_caption](/cells/python-net/aspose.cells.pivot/pivottable/row_header_caption) | Gets the Row Header Caption of the PivotTable. |
| [show_row_header_caption](/cells/python-net/aspose.cells.pivot/pivottable/show_row_header_caption) | Indicates whether row header caption is shown in the PivotTable report<br/>Indicates whether Display field captions and filter drop downs |
| [custom_list_sort](/cells/python-net/aspose.cells.pivot/pivottable/custom_list_sort) | Indicates whether consider built-in custom list when sort data |
| [pivot_format_conditions](/cells/python-net/aspose.cells.pivot/pivottable/pivot_format_conditions) | Gets the Format Conditions of the pivot table. |
| [page_field_order](/cells/python-net/aspose.cells.pivot/pivottable/page_field_order) | Gets and sets the order in which page fields are added to the PivotTable report's layout. |
| [page_field_wrap_count](/cells/python-net/aspose.cells.pivot/pivottable/page_field_wrap_count) | Gets the number of page fields in each column or row in the PivotTable report. |
| [tag](/cells/python-net/aspose.cells.pivot/pivottable/tag) | Gets a string saved with the PivotTable report. |
| [save_data](/cells/python-net/aspose.cells.pivot/pivottable/save_data) | Indicates whether data for the PivotTable report is saved with the workbook. |
| [refresh_data_on_opening_file](/cells/python-net/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indicates whether Refresh Data when Opening File. |
| [refresh_data_flag](/cells/python-net/aspose.cells.pivot/pivottable/refresh_data_flag) | Indicates whether Refreshing Data or not. |
| [source_type](/cells/python-net/aspose.cells.pivot/pivottable/source_type) | Gets the data source type of the pivot table. |
| [external_connection_data_source](/cells/python-net/aspose.cells.pivot/pivottable/external_connection_data_source) | Gets the external connection data source. |
| [data_source](/cells/python-net/aspose.cells.pivot/pivottable/data_source) | Gets and sets the data source of the pivot table. |
| [pivot_formats](/cells/python-net/aspose.cells.pivot/pivottable/pivot_formats) | Gets the collection of formats applied to PivotTable. |
| [item_print_titles](/cells/python-net/aspose.cells.pivot/pivottable/item_print_titles) | Indicates whether PivotItem names should be repeated at the top of each printed page. |
| [print_titles](/cells/python-net/aspose.cells.pivot/pivottable/print_titles) | Indicates whether the print titles for the worksheet are set based<br/>on the PivotTable report. The default value is false. |
| [display_immediate_items](/cells/python-net/aspose.cells.pivot/pivottable/display_immediate_items) | Indicates whether items in the row and column areas are visible<br/>when the data area of the PivotTable is empty. The default value is true. |
| [is_selected](/cells/python-net/aspose.cells.pivot/pivottable/is_selected) | Indicates whether this PivotTable is selected. |
| [show_pivot_style_row_header](/cells/python-net/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Indicates whether the row header in the pivot table should have the style applied. |
| [show_pivot_style_column_header](/cells/python-net/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Indicates whether the column header in the pivot table should have the style applied. |
| [show_pivot_style_row_stripes](/cells/python-net/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indicates whether row stripe formatting is applied. |
| [show_pivot_style_column_stripes](/cells/python-net/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indicates whether stripe formatting is applied for column. |
| [show_pivot_style_last_column](/cells/python-net/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indicates whether the column formatting is applied. |


### Methods
| Method | Description |
| :- | :- |
| [remove_field](/cells/python-net/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) | Removes a field from specific field area |
| [remove_field](/cells/python-net/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) | Removes a field from specific field area |
| [remove_field](/cells/python-net/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Remove field from specific field area |
| [add_field_to_area](/cells/python-net/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Adds the field to the specific area. |
| [add_field_to_area](/cells/python-net/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Adds the field to the specific area. |
| [add_field_to_area](/cells/python-net/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Adds the field to the specific area. |
| [add_calculated_field](/cells/python-net/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Adds a calculated field to pivot field. |
| [add_calculated_field](/cells/python-net/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Adds a calculated field to pivot field and drag it to data area. |
| [move](/cells/python-net/aspose.cells.pivot/pivottable/move/#int-int) | Moves the PivotTable to a different location in the worksheet. |
| [move](/cells/python-net/aspose.cells.pivot/pivottable/move/#str) | Moves the PivotTable to a different location in the worksheet. |
| [refresh_data](/cells/python-net/aspose.cells.pivot/pivottable/refresh_data/#) | Refreshes pivottable's data and setting from it's data source. |
| [refresh_data](/cells/python-net/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.PivotTableRefreshOption) | Refreshes pivottable's data and setting from it's data source with options. |
| [calculate_data](/cells/python-net/aspose.cells.pivot/pivottable/calculate_data/#) | Calculates pivottable's data to cells. |
| [calculate_data](/cells/python-net/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.PivotTableCalculateOption) | Calculating pivot tables with options |
| [format](/cells/python-net/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Formats selected area of the PivotTable. |
| [format](/cells/python-net/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Format the cell in the pivottable area |
| [set_auto_group_field](/cells/python-net/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Sets auto field group by the PivotTable. |
| [set_auto_group_field](/cells/python-net/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Sets auto field group by the PivotTable. |
| [set_manual_group_field](/cells/python-net/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Sets manual field group by the PivotTable. |
| [set_manual_group_field](/cells/python-net/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Sets manual field group by the PivotTable. |
| [set_manual_group_field](/cells/python-net/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Sets manual field group by the PivotTable. |
| [set_manual_group_field](/cells/python-net/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Sets manual field group by the PivotTable. |
| [set_ungroup](/cells/python-net/aspose.cells.pivot/pivottable/set_ungroup/#int) | Sets ungroup by the PivotTable |
| [set_ungroup](/cells/python-net/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Sets ungroup by the PivotTable |
| [copy_style](/cells/python-net/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Copies named style from another pivot table. |
| [show_report_filter_page](/cells/python-net/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Show all the report filter pages according to PivotField, the PivotField must be located in the PageFields. |
| [show_report_filter_page_by_name](/cells/python-net/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Show all the report filter pages according to PivotField's name, the PivotField must be located in the PageFields. |
| [show_report_filter_page_by_index](/cells/python-net/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Show all the report filter pages according to the position index in the PageFields |
| [get_fields](/cells/python-net/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.PivotFieldType) | Gets the specific pivot field list by the region. |
| [fields](/cells/python-net/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Gets the specific fields by the field type. |
| [change_data_source](/cells/python-net/aspose.cells.pivot/pivottable/change_data_source/#list) | Set pivottable's source data.<br/>Sheet1!$A$1:$C$3 |
| [get_source](/cells/python-net/aspose.cells.pivot/pivottable/get_source/#) | Get pivottable's source data. |
| [clear_data](/cells/python-net/aspose.cells.pivot/pivottable/clear_data/#) | Clear PivotTable's data and formatting |
| [calculate_range](/cells/python-net/aspose.cells.pivot/pivottable/calculate_range/#) | Calculates pivottable's range. |
| [format_all](/cells/python-net/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Format all the cell in the pivottable area |
| [format_row](/cells/python-net/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Format the row data in the pivottable area |
| [show_datail](/cells/python-net/aspose.cells.pivot/pivottable/show_datail/#int-int-bool-int-int) | Show the detail of one item in the data region to a new Table. |
| [get_horizontal_breaks](/cells/python-net/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | get pivot table row index list of horizontal pagebreaks |
| [show_in_compact_form](/cells/python-net/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Layouts the PivotTable in compact form. |
| [show_in_outline_form](/cells/python-net/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Layouts the PivotTable in outline form. |
| [show_in_tabular_form](/cells/python-net/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Layouts the PivotTable in tabular form. |
| [get_cell_by_display_name](/cells/python-net/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Gets the [`Cell`](/cells/python-net/aspose.cells/cell) object by the display name of PivotField. |
| [get_children](/cells/python-net/aspose.cells.pivot/pivottable/get_children/#) | Gets the Children Pivot Tables which use this PivotTable data as data source. |



### Example 


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

### See Also
* module [`aspose.cells.pivot`](..)
* class [`Cell`](/cells/python-net/aspose.cells/cell)
* class [`CellArea`](/cells/python-net/aspose.cells/cellarea)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
