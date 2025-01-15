﻿---
title: PivotField class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 100
url: /aspose.cells.pivot/pivotfield/
is_root: false
---

## PivotField class

Represents a field in a PivotTable report.



The PivotField type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [pivot_items](/cells/python-net/aspose.cells.pivot/pivotfield/pivot_items) | Gets the pivot items of the pivot field |
| [range](/cells/python-net/aspose.cells.pivot/pivotfield/range) | Gets the group range of the pivot field |
| [group_settings](/cells/python-net/aspose.cells.pivot/pivotfield/group_settings) | Gets the group settings of the pivot field. |
| [is_calculated_field](/cells/python-net/aspose.cells.pivot/pivotfield/is_calculated_field) | Indicates whether the specified PivotTable field is calculated field. |
| [is_value_fields](/cells/python-net/aspose.cells.pivot/pivotfield/is_value_fields) | Indicates whether this field represents values fields. |
| [base_index](/cells/python-net/aspose.cells.pivot/pivotfield/base_index) | Represents the PivotField index in the base PivotFields. |
| [position](/cells/python-net/aspose.cells.pivot/pivotfield/position) | Represents the index of [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield) in the region. |
| [region_type](/cells/python-net/aspose.cells.pivot/pivotfield/region_type) | Specifies the region of the PivotTable that this field is displayed. |
| [name](/cells/python-net/aspose.cells.pivot/pivotfield/name) | Represents the name of PivotField. |
| [display_name](/cells/python-net/aspose.cells.pivot/pivotfield/display_name) | Represents the PivotField display name. |
| [is_auto_subtotals](/cells/python-net/aspose.cells.pivot/pivotfield/is_auto_subtotals) | Indicates whether the specified field shows automatic subtotals. Default is true. |
| [drag_to_column](/cells/python-net/aspose.cells.pivot/pivotfield/drag_to_column) | Indicates whether the specified field can be dragged to the column position.<br/>The default value is true. |
| [drag_to_hide](/cells/python-net/aspose.cells.pivot/pivotfield/drag_to_hide) | Indicates whether the specified field can be dragged to the hide position.<br/>The default value is true. |
| [drag_to_row](/cells/python-net/aspose.cells.pivot/pivotfield/drag_to_row) | Indicates whether the specified field can be dragged to the row position.<br/>The default value is true. |
| [drag_to_page](/cells/python-net/aspose.cells.pivot/pivotfield/drag_to_page) | Indicates whether the specified field can be dragged to the page position.<br/>The default value is true. |
| [drag_to_data](/cells/python-net/aspose.cells.pivot/pivotfield/drag_to_data) | Indicates whether the specified field can be dragged to the data position.<br/>The default value is true. |
| [is_multiple_item_selection_allowed](/cells/python-net/aspose.cells.pivot/pivotfield/is_multiple_item_selection_allowed) | indicates whether the field can have multiple items<br/>selected in the page field<br/>The default value is false. |
| [is_repeat_item_labels](/cells/python-net/aspose.cells.pivot/pivotfield/is_repeat_item_labels) | Indicates whether repeating labels of the field in the region.<br/>The default value is false. |
| [is_include_new_items_in_filter](/cells/python-net/aspose.cells.pivot/pivotfield/is_include_new_items_in_filter) | Indicates whether including new items to the field in manual filter.<br/>The default value is false. |
| [is_insert_page_breaks_between_items](/cells/python-net/aspose.cells.pivot/pivotfield/is_insert_page_breaks_between_items) | Indicates whether inserting page breaks after each item.<br/>The default value is false. |
| [show_all_items](/cells/python-net/aspose.cells.pivot/pivotfield/show_all_items) | Indicates whether all items displays in the PivotTable report, <br/>even if they don't contain summary data.<br/>show items with no data<br/>The default value is false. |
| [non_auto_sort_default](/cells/python-net/aspose.cells.pivot/pivotfield/non_auto_sort_default) | Indicates whether a sort operation that will be applied to this pivot field is an autosort operation or a simple data sort. |
| [is_auto_sort](/cells/python-net/aspose.cells.pivot/pivotfield/is_auto_sort) | Indicates whether the specified PivotTable field is automatically sorted. |
| [is_ascend_sort](/cells/python-net/aspose.cells.pivot/pivotfield/is_ascend_sort) | Indicates whether the specified PivotTable field is autosorted ascending. |
| [sort_setting](/cells/python-net/aspose.cells.pivot/pivotfield/sort_setting) | Gets all settings of auto sorting |
| [auto_sort_field](/cells/python-net/aspose.cells.pivot/pivotfield/auto_sort_field) | Represents the index of field which is auto sorted. <br/>-1 means PivotField itself,others means the position of the data fields. |
| [is_auto_show](/cells/python-net/aspose.cells.pivot/pivotfield/is_auto_show) | Indicates whether the specified PivotTable field is automatically shown,only valid for excel 2003. |
| [is_ascend_show](/cells/python-net/aspose.cells.pivot/pivotfield/is_ascend_show) | Indicates whether the specified PivotTable field is autoshown ascending. |
| [auto_show_count](/cells/python-net/aspose.cells.pivot/pivotfield/auto_show_count) | Represent the number of top or bottom items<br/>that are automatically shown in the specified PivotTable field. |
| [auto_show_field](/cells/python-net/aspose.cells.pivot/pivotfield/auto_show_field) | Represents auto show field index. -1 means PivotField itself.<br/>It should be the index of the data fields. |
| [function](/cells/python-net/aspose.cells.pivot/pivotfield/function) | Represents the function used to summarize the PivotTable data field. |
| [show_values_setting](/cells/python-net/aspose.cells.pivot/pivotfield/show_values_setting) | Gets the settings of showing values as when the ShowDataAs calculation is in use. |
| [data_display_format](/cells/python-net/aspose.cells.pivot/pivotfield/data_display_format) | Represents how to display the values in a data field of the pivot report. |
| [base_field_index](/cells/python-net/aspose.cells.pivot/pivotfield/base_field_index) | Represents the base field for a custom calculation when the ShowDataAs calculation is in use. |
| [base_item_position](/cells/python-net/aspose.cells.pivot/pivotfield/base_item_position) | Represents the item in the base field for a custom calculation when the ShowDataAs calculation is in use.<br/>Valid only for data fields. <br/>Because PivotItemPosition.Custom is only for read,if you need to set PivotItemPosition.Custom,<br/>please set PivotField.BaseItemIndex attribute. |
| [base_item_index](/cells/python-net/aspose.cells.pivot/pivotfield/base_item_index) | Represents the item in the base field for a custom calculation when the ShowDataAs calculation is in use.<br/>Valid only for data fields. |
| [current_page_item](/cells/python-net/aspose.cells.pivot/pivotfield/current_page_item) | Represents the current page item showing for the page field (valid only for page fields). |
| [number](/cells/python-net/aspose.cells.pivot/pivotfield/number) | Represents the built-in display format of numbers and dates. |
| [insert_blank_row](/cells/python-net/aspose.cells.pivot/pivotfield/insert_blank_row) | Indicates whether inserting blank line after each item. |
| [show_subtotal_at_top](/cells/python-net/aspose.cells.pivot/pivotfield/show_subtotal_at_top) | when ShowInOutlineForm is true, then display subtotals at the top of the list of items instead of at the bottom |
| [show_in_outline_form](/cells/python-net/aspose.cells.pivot/pivotfield/show_in_outline_form) | Indicates whether layout this field in outline form on the Pivot Table view |
| [number_format](/cells/python-net/aspose.cells.pivot/pivotfield/number_format) | Represents the custom display format of numbers and dates. |
| [items](/cells/python-net/aspose.cells.pivot/pivotfield/items) | Get all labels of pivot items in this field. |
| [original_items](/cells/python-net/aspose.cells.pivot/pivotfield/original_items) | Get the original base items; |
| [item_count](/cells/python-net/aspose.cells.pivot/pivotfield/item_count) | Gets the count of the base items in this pivot field. |
| [show_compact](/cells/python-net/aspose.cells.pivot/pivotfield/show_compact) | Indicates whether display labels from the next field in the same column on the Pivot Table view |


### Methods
| Method | Description |
| :- | :- |
| [group_by](/cells/python-net/aspose.cells.pivot/pivotfield/group_by/#float-bool) | Automatically group the field with internal |
| [group_by](/cells/python-net/aspose.cells.pivot/pivotfield/group_by/#DateTime-DateTime-list-float-bool) | Group the file by the date group types. |
| [group_by](/cells/python-net/aspose.cells.pivot/pivotfield/group_by/#float-float-float-bool) | Group the file by number. |
| [group_by](/cells/python-net/aspose.cells.pivot/pivotfield/group_by/#list-bool) | Custom group the field. |
| [sort_by](/cells/python-net/aspose.cells.pivot/pivotfield/sort_by/#aspose.cells.SortOrder-int) | Sorts this pivot field. |
| [sort_by](/cells/python-net/aspose.cells.pivot/pivotfield/sort_by/#aspose.cells.SortOrder-int-aspose.cells.pivot.PivotLineType-str) | Sorts this pivot field. |
| [hide_item](/cells/python-net/aspose.cells.pivot/pivotfield/hide_item/#int-bool) | Sets whether the specific PivotItem in a data field is hidden. |
| [hide_item](/cells/python-net/aspose.cells.pivot/pivotfield/hide_item/#str-bool) | Sets whether the specific PivotItem in a data field is hidden. |
| [init_pivot_items](/cells/python-net/aspose.cells.pivot/pivotfield/init_pivot_items/#) | Init the pivot items of the pivot field |
| [ungroup](/cells/python-net/aspose.cells.pivot/pivotfield/ungroup/#) | Ungroup the pivot field. |
| [get_pivot_filter_by_type](/cells/python-net/aspose.cells.pivot/pivotfield/get_pivot_filter_by_type/#aspose.cells.pivot.PivotFilterType) | Gets the pivot filter of the pivot field by type |
| [get_pivot_filters](/cells/python-net/aspose.cells.pivot/pivotfield/get_pivot_filters/#) | Gets the pivot filters of the pivot field |
| [get_filters](/cells/python-net/aspose.cells.pivot/pivotfield/get_filters/#) | Gets all pivot filters of this pivot field. |
| [clear_filter](/cells/python-net/aspose.cells.pivot/pivotfield/clear_filter/#) | Clears filter setting on this pivot field. |
| [filter_top10](/cells/python-net/aspose.cells.pivot/pivotfield/filter_top10/#int-aspose.cells.pivot.PivotFilterType-bool-int) | Filters by values of data pivot field. |
| [filter_by_value](/cells/python-net/aspose.cells.pivot/pivotfield/filter_by_value/#int-aspose.cells.pivot.PivotFilterType-float-float) | Filters by values of data pivot field. |
| [filter_by_label](/cells/python-net/aspose.cells.pivot/pivotfield/filter_by_label/#aspose.cells.pivot.PivotFilterType-str-str) | Filters by captions of row or column pivot field. |
| [filter_by_date](/cells/python-net/aspose.cells.pivot/pivotfield/filter_by_date/#aspose.cells.pivot.PivotFilterType-DateTime-DateTime) | Filters by date setting of row or column pivot field. |
| [get_calculated_field_formula](/cells/python-net/aspose.cells.pivot/pivotfield/get_calculated_field_formula/#) | Get the formula string of the specified calculated field . |
| [get_formula](/cells/python-net/aspose.cells.pivot/pivotfield/get_formula/#) | Gets formula of the calculated field . |
| [set_subtotals](/cells/python-net/aspose.cells.pivot/pivotfield/set_subtotals/#aspose.cells.pivot.PivotFieldSubtotalType-bool) | Sets whether the specified field shows that subtotals. |
| [get_subtotals](/cells/python-net/aspose.cells.pivot/pivotfield/get_subtotals/#aspose.cells.pivot.PivotFieldSubtotalType) | Indicates whether showing specified subtotal. |
| [show_values_as](/cells/python-net/aspose.cells.pivot/pivotfield/show_values_as/#aspose.cells.pivot.PivotFieldDataDisplayFormat-int-aspose.cells.pivot.PivotItemPositionType-int) | Shows values of data field as different display format when the ShowDataAs calculation is in use. |
| [is_hidden_item](/cells/python-net/aspose.cells.pivot/pivotfield/is_hidden_item/#int) | Gets whether the specific PivotItem is hidden. |
| [is_hidden_item_detail](/cells/python-net/aspose.cells.pivot/pivotfield/is_hidden_item_detail/#int) | Gets whether hidding the detail of  the specific PivotItem.. |
| [hide_item_detail](/cells/python-net/aspose.cells.pivot/pivotfield/hide_item_detail/#int-bool) | Sets whether the specific PivotItem in a pivot field is hidden detail. |
| [hide_detail](/cells/python-net/aspose.cells.pivot/pivotfield/hide_detail/#bool) | Sets whether the PivotItems in a pivot field is hidden detail.That is collapse/expand this field. |
| [add_calculated_item](/cells/python-net/aspose.cells.pivot/pivotfield/add_calculated_item/#str-str) | Add a calculated formula item to the pivot field. |



### Example 


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

### See Also
* module [`aspose.cells.pivot`](..)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
