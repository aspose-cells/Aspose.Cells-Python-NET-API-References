---
title: SettableGlobalizationSettings class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1470
url: /aspose.cells/settableglobalizationsettings/
is_root: false
---

## SettableGlobalizationSettings class

Implementation of GlobalizationSettings that supports user to set/change pre-defined texts.



**Inheritance:** [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings) → 
[`GlobalizationSettings`](/cells/python-net/aspose.cells/globalizationsettings)



The SettableGlobalizationSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells/settableglobalizationsettings/__init__/#) | Constructs a new instance of SettableGlobalizationSettings |


### Properties
| Property | Description |
| :- | :- |
| [chart_settings](/cells/python-net/aspose.cells/settableglobalizationsettings/chart_settings) | Gets or sets the globalization settings for Chart. |
| [pivot_settings](/cells/python-net/aspose.cells/settableglobalizationsettings/pivot_settings) | Gets or sets the globalization settings for pivot table. |
| [list_separator](/cells/python-net/aspose.cells/settableglobalizationsettings/list_separator) | Gets the separator for list, parameters of function, ...etc. |
| [row_separator_of_formula_array](/cells/python-net/aspose.cells/settableglobalizationsettings/row_separator_of_formula_array) | Gets the separator for rows in array data in formula. |
| [column_separator_of_formula_array](/cells/python-net/aspose.cells/settableglobalizationsettings/column_separator_of_formula_array) | Gets the separator for the items in array's row data in formula. |


### Methods
| Method | Description |
| :- | :- |
| [get_pivot_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_pivot_total_name/#) | Gets the name of "Total" label in the PivotTable.<br/>You need to override this method when the PivotTable contains two or more PivotFields in the data area. |
| [get_pivot_grand_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_pivot_grand_total_name/#) | Gets the name of "Grand Total" label in the PivotTable. |
| [get_multiple_items_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_multiple_items_name/#) | Gets the name of "(Multiple Items)" label in the PivotTable. |
| [get_all_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_all_name/#) | Gets the name of "(All)" label in the PivotTable. |
| [get_protection_name_of_pivot_table](/cells/python-net/aspose.cells/settableglobalizationsettings/get_protection_name_of_pivot_table/#) | Gets the protection name in the PivotTable. |
| [get_column_labels_of_pivot_table](/cells/python-net/aspose.cells/settableglobalizationsettings/get_column_labels_of_pivot_table/#) | Gets the name of "Column Labels" label in the PivotTable. |
| [get_row_labels_name_of_pivot_table](/cells/python-net/aspose.cells/settableglobalizationsettings/get_row_labels_name_of_pivot_table/#) | Gets the name of "Row Labels" label in the PivotTable. |
| [get_empty_data_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_empty_data_name/#) | Gets the name of "(blank)" label in the PivotTable. |
| [get_data_field_header_name_of_pivot_table](/cells/python-net/aspose.cells/settableglobalizationsettings/get_data_field_header_name_of_pivot_table/#) | Gets the the name of the value area field header in the PivotTable. |
| [get_sub_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_sub_total_name/#aspose.cells.pivot.PivotFieldSubtotalType) | Gets the name of [`PivotFieldSubtotalType`](/cells/python-net/aspose.cells.pivot/pivotfieldsubtotaltype) type in the PivotTable. |
| [get_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_total_name/#aspose.cells.ConsolidationFunction) | Gets the total name of specific function. |
| [get_grand_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_grand_total_name/#aspose.cells.ConsolidationFunction) | Gets the grand total name of the function. |
| [get_default_sheet_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_default_sheet_name/#) | Gets the default sheet name for adding worksheet automatically.<br/>Default is "Sheet". |
| [get_table_row_type_of_headers](/cells/python-net/aspose.cells/settableglobalizationsettings/get_table_row_type_of_headers/#) | Gets the type name of table rows that consists of the table header.<br/>Default is "Headers", so in formula "#Headers" represents the table header. |
| [get_table_row_type_of_data](/cells/python-net/aspose.cells/settableglobalizationsettings/get_table_row_type_of_data/#) | Gets the type name of table rows that consists of data region of referenced table.<br/>Default is "Data", so in formula "#Data" represents the data region of the table. |
| [get_table_row_type_of_all](/cells/python-net/aspose.cells/settableglobalizationsettings/get_table_row_type_of_all/#) | Gets the type name of table rows that consists of all rows in referenced table. |
| [get_table_row_type_of_totals](/cells/python-net/aspose.cells/settableglobalizationsettings/get_table_row_type_of_totals/#) | Gets the type name of table rows that consists of the total row of referenced table. |
| [get_table_row_type_of_current](/cells/python-net/aspose.cells/settableglobalizationsettings/get_table_row_type_of_current/#) | Gets the type name of table rows that consists of the current row in referenced table. |
| [get_error_value_string](/cells/python-net/aspose.cells/settableglobalizationsettings/get_error_value_string/#str) | Gets the display string value for cell's error value |
| [get_boolean_value_string](/cells/python-net/aspose.cells/settableglobalizationsettings/get_boolean_value_string/#bool) | Gets the display string value for cell's boolean value |
| [get_local_function_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_local_function_name/#str) | Gets the locale dependent function name according to given standard function name. |
| [get_standard_function_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_standard_function_name/#str) | Gets the standard function name according to given locale dependent function name. |
| [get_local_built_in_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_local_built_in_name/#str) | Gets the locale dependent text for built-in Name according to given standard text. |
| [get_standard_built_in_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_standard_built_in_name/#str) | Gets the standard text of built-in Name according to given locale dependent text. |
| [get_standard_header_footer_font_style_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_standard_header_footer_font_style_name/#str) | Gets standard English font style name(Regular, Bold, Italic) for Header/Footer according to given locale font style name. |
| [get_comment_title_name](/cells/python-net/aspose.cells/settableglobalizationsettings/get_comment_title_name/#aspose.cells.rendering.CommentTitleType) | Gets the locale dependent comment title name according to comment title type. |
| [compare](/cells/python-net/aspose.cells/settableglobalizationsettings/compare/#str-str-bool) | Compares two string values according to certain collation rules. |
| [set_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_total_name/#aspose.cells.ConsolidationFunction-str) | Sets the total name of specific function. |
| [set_grand_total_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_grand_total_name/#aspose.cells.ConsolidationFunction-str) | Sets the grand total name of specific function. |
| [set_table_row_type_of_headers](/cells/python-net/aspose.cells/settableglobalizationsettings/set_table_row_type_of_headers/#str) | Sets the type name of table rows that consists of the table header. |
| [set_table_row_type_of_data](/cells/python-net/aspose.cells/settableglobalizationsettings/set_table_row_type_of_data/#str) | Sets the type name of table rows that consists of data region of referenced table. |
| [set_table_row_type_of_all](/cells/python-net/aspose.cells/settableglobalizationsettings/set_table_row_type_of_all/#str) | Sets the type name of table rows that consists of all rows in referenced table. |
| [set_table_row_type_of_totals](/cells/python-net/aspose.cells/settableglobalizationsettings/set_table_row_type_of_totals/#str) | Sets the type name of table rows that consists of the total row of referenced table. |
| [set_table_row_type_of_current](/cells/python-net/aspose.cells/settableglobalizationsettings/set_table_row_type_of_current/#str) | Sets the type name of table rows that consists of the current row in referenced table. |
| [set_boolean_value_string](/cells/python-net/aspose.cells/settableglobalizationsettings/set_boolean_value_string/#bool-str) | Sets the display string value for cell's boolean value |
| [set_local_function_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_local_function_name/#str-str-bool) | Sets the locale dependent function name corresponding to given standard function name. |
| [set_standard_function_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_standard_function_name/#str-str-bool) | Sets the locale dependent function name according to given standard function name. |
| [set_local_built_in_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_local_built_in_name/#str-str-bool) | Sets the locale dependent text for the built-in name with given standard name text. |
| [set_standard_built_in_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_standard_built_in_name/#str-str-bool) | Sets the locale dependent function name according to given standard function name. |
| [set_list_separator](/cells/python-net/aspose.cells/settableglobalizationsettings/set_list_separator/#char) | Sets the separator for list, parameters of function, ...etc. |
| [set_row_separator_of_formula_array](/cells/python-net/aspose.cells/settableglobalizationsettings/set_row_separator_of_formula_array/#char) | Sets the separator for rows in array data in formula. |
| [set_column_separator_of_formula_array](/cells/python-net/aspose.cells/settableglobalizationsettings/set_column_separator_of_formula_array/#char) | Sets the separator for the items in array's row data in formula. |
| [set_standard_header_footer_font_style_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_standard_header_footer_font_style_name/#str-str) | Sets the locale dependent function name according to given standard function name. |
| [set_comment_title_name](/cells/python-net/aspose.cells/settableglobalizationsettings/set_comment_title_name/#aspose.cells.rendering.CommentTitleType-str) | Gets the locale dependent comment title name according to comment title type. |



### See Also
* module [`aspose.cells`](..)
* class [`GlobalizationSettings`](/cells/python-net/aspose.cells/globalizationsettings)
* class [`PivotFieldSubtotalType`](/cells/python-net/aspose.cells.pivot/pivotfieldsubtotaltype)
* class [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings)
