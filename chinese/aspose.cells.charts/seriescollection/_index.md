---
title: SeriesCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 250
url: /zh/aspose.cells.charts/seriescollection/
is_root: false
---
## SeriesCollection类
封装了 [`Series`](/cells/python-net/zh/aspose.cells.charts/series) 对象的集合。



SeriesCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [category_data](/cells/python-net/zh/aspose.cells.charts/seriescollection/category_data) |获取或设置类别轴值的范围。<br/>它可以是一系列单元格（例如“d1:e10”），<br/>或值序列（例如“{2,6,8,10}”）。|
| [second_category_data](/cells/python-net/zh/aspose.cells.charts/seriescollection/second_category_data) |获取或设置第二类轴值的范围。<br/>它可以是一系列单元格（例如“d1:e10”），<br/>或值序列（例如“{2,6,8,10}”）。<br/>仅当某些 ASeries 在第二个轴上绘制时才有效。|
| [is_color_varied](/cells/python-net/zh/aspose.cells.charts/seriescollection/is_color_varied) |表示点的颜色是否变化。|
| [capacity](/cells/python-net/zh/aspose.cells.charts/seriescollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add](/cells/python-net/zh/aspose.cells.charts/seriescollection/add/#str-bool) |将 [`Series`](/cells/python-net/zh/aspose.cells.charts/series) 集合添加到图表中。|
| [add](/cells/python-net/zh/aspose.cells.charts/seriescollection/add/#str-bool-bool) |将 [`Series`](/cells/python-net/zh/aspose.cells.charts/series) 集合添加到图表中。|
| [copy_to](/cells/python-net/zh/aspose.cells.charts/seriescollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [get_series_by_order](/cells/python-net/zh/aspose.cells.charts/seriescollection/get_series_by_order/#int) |按顺序获取[`Series`](/cells/python-net/zh/aspose.cells.charts/series)元素。|
| [change_series_order](/cells/python-net/zh/aspose.cells.charts/seriescollection/change_series_order/#int-int) |直接改变两个系列的顺序。|
| [set_series_names](/cells/python-net/zh/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) |设置图表中所有系列的名称。|
| [add_r1c1](/cells/python-net/zh/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) |将 [`Series`](/cells/python-net/zh/aspose.cells.charts/series) 集合添加到图表中。|
| [binary_search](/cells/python-net/zh/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.Series) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

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

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Series`](/cells/python-net/zh/aspose.cells.charts/series)
