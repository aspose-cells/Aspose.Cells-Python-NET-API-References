---
title: AutoFilter class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.cells/autofilter/
is_root: false
---

## AutoFilter class

Represents autofiltering for the specified worksheet.



The AutoFilter type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [sorter](/cells/python-net/aspose.cells/autofilter/sorter) | Gets the data sorter. |
| [range](/cells/python-net/aspose.cells/autofilter/range) | Represents the range to which the specified AutoFilter applies. |
| [show_filter_button](/cells/python-net/aspose.cells/autofilter/show_filter_button) | Indicates whether the AutoFilter button for this column is visible. |
| [filter_columns](/cells/python-net/aspose.cells/autofilter/filter_columns) | Gets the collection of the filter columns. |


### Methods
| Method | Description |
| :- | :- |
| [remove_filter](/cells/python-net/aspose.cells/autofilter/remove_filter/#int-str) | Removes a filter for a filter column. |
| [remove_filter](/cells/python-net/aspose.cells/autofilter/remove_filter/#int) | Remove the specific filter. |
| [custom](/cells/python-net/aspose.cells/autofilter/custom/#int-aspose.cells.FilterOperatorType-any) | Filters a list with a custom criteria. |
| [custom](/cells/python-net/aspose.cells/autofilter/custom/#int-aspose.cells.FilterOperatorType-any-bool-aspose.cells.FilterOperatorType-any) | Filters a list with custom criteria. |
| [refresh](/cells/python-net/aspose.cells/autofilter/refresh/#) | Refresh auto filters to hide or unhide the rows. |
| [refresh](/cells/python-net/aspose.cells/autofilter/refresh/#bool) | Gets all hidden rows' indexes. |
| [set_range](/cells/python-net/aspose.cells/autofilter/set_range/#int-int-int) | Sets the range to which the specified AutoFilter applies. |
| [get_cell_area](/cells/python-net/aspose.cells/autofilter/get_cell_area/#) | Gets the [`CellArea`](/cells/python-net/aspose.cells/cellarea) where the specified AutoFilter applies to. |
| [add_filter](/cells/python-net/aspose.cells/autofilter/add_filter/#int-str) | Adds a filter for a filter column. |
| [add_date_filter](/cells/python-net/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int) | Adds a date filter. |
| [remove_date_filter](/cells/python-net/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int) | Removes a date filter. |
| [filter](/cells/python-net/aspose.cells/autofilter/filter/#int-str) | Filters a list with specified criteria. |
| [filter_top10](/cells/python-net/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Filter the top 10 item in the list |
| [dynamic_filter](/cells/python-net/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.DynamicFilterType) | Adds a dynamic filter. |
| [add_font_color_filter](/cells/python-net/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.CellsColor) | Adds a font color filter. |
| [add_fill_color_filter](/cells/python-net/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.BackgroundType-aspose.cells.CellsColor-aspose.cells.CellsColor) | Adds a fill color filter. |
| [add_icon_filter](/cells/python-net/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.IconSetType-int) | Adds an icon filter. |
| [match_blanks](/cells/python-net/aspose.cells/autofilter/match_blanks/#int) | Match all blank cell in the list. |
| [match_non_blanks](/cells/python-net/aspose.cells/autofilter/match_non_blanks/#int) | Match all not blank cell in the list. |
| [show_all](/cells/python-net/aspose.cells/autofilter/show_all/#) | Unhide all rows. |



### Example 


```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

### See Also
* module [`aspose.cells`](..)
* class [`CellArea`](/cells/python-net/aspose.cells/cellarea)
