﻿---
title: SeriesCollection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 240
url: /aspose.cells.charts/seriescollection/
is_root: false
---

## SeriesCollection class

Encapsulates a collection of [`Series`](/cells/python-net/aspose.cells.charts/series) objects.



The SeriesCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [category_data](/cells/python-net/aspose.cells.charts/seriescollection/category_data) | Gets or sets the range of category Axis values. <br/>It can be a range of cells (such as, "d1:e10"), <br/>or a sequence of values (such as,"{2,6,8,10}"). |
| [second_category_data](/cells/python-net/aspose.cells.charts/seriescollection/second_category_data) | Gets or sets the range of second category Axis values. <br/>It can be a range of cells (such as, "d1:e10"), <br/>or a sequence of values (such as,"{2,6,8,10}"). <br/>Only effects when some ASerieses plot on the second axis. |
| [is_color_varied](/cells/python-net/aspose.cells.charts/seriescollection/is_color_varied) | Represents if the color of points is varied. |
| [capacity](/cells/python-net/aspose.cells.charts/seriescollection/capacity) | Gets or sets the number of elements that the array list can contain. |


### Methods
| Method | Description |
| :- | :- |
| [add](/cells/python-net/aspose.cells.charts/seriescollection/add/#str-bool) | Adds the [`SeriesCollection`](/cells/python-net/aspose.cells.charts/seriescollection) collection to a chart. |
| [add](/cells/python-net/aspose.cells.charts/seriescollection/add/#str-bool-bool) | Adds the [`SeriesCollection`](/cells/python-net/aspose.cells.charts/seriescollection) collection to a chart. |
| [copy_to](/cells/python-net/aspose.cells.charts/seriescollection/copy_to/#list) | Copies the entire array list to a compatible one-dimensional array list, starting at the beginning of the target array list. |
| [copy_to](/cells/python-net/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Copies a range of elements from the array list to a compatible one-dimensional array list, starting at the specified index of the target array list. |
| [index_of](/cells/python-net/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that extends from the specified index to the last element. |
| [index_of](/cells/python-net/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int-int) | Searches for the specified object and returns the zero-based index of the first occurrence within the range of elements in the array list that starts at the specified index and contains the specified number of elements. |
| [last_index_of](/cells/python-net/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series) | Searches for the specified object and returns the zero-based index of the last occurrence within the entire array list. |
| [last_index_of](/cells/python-net/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that extends from the first element to the specified index. |
| [last_index_of](/cells/python-net/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int-int) | Searches for the specified object and returns the zero-based index of the last occurrence within the range of elements in the array list that contains the specified number of elements and ends at the specified index. |
| [get_series_by_order](/cells/python-net/aspose.cells.charts/seriescollection/get_series_by_order/#int) | Gets the [`Series`](/cells/python-net/aspose.cells.charts/series) element by order. |
| [change_series_order](/cells/python-net/aspose.cells.charts/seriescollection/change_series_order/#int-int) | Directly changes the orders of the two series. |
| [set_series_names](/cells/python-net/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Sets the name of all the serieses in the chart. |
| [add_r1c1](/cells/python-net/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | Adds the [`SeriesCollection`](/cells/python-net/aspose.cells.charts/seriescollection) collection to a chart. |
| [binary_search](/cells/python-net/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.Series) | Searches the entire sorted array list for an element using the default comparer and returns the zero-based index of the element. |



### Example 


```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

### See Also
* module [`aspose.cells.charts`](..)
* class [`Series`](/cells/python-net/aspose.cells.charts/series)
* class [`SeriesCollection`](/cells/python-net/aspose.cells.charts/seriescollection)
