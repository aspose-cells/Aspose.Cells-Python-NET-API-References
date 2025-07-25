---
title: TrendlineCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 350
url: /zh/aspose.cells.charts/trendlinecollection/
is_root: false
---
## TrendlineCollection类
表示指定数据系列的所有 [`Trendline`](/cells/python-net/zh/aspose.cells.charts/trendline) 对象的集合。



TrendlineCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, type)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype) |将指定类型的 [`Trendline`](/cells/python-net/zh/aspose.cells.charts/trendline) 对象添加到此集合。|
| [`add(self, type, name)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype-str) |将 [`Trendline`](/cells/python-net/zh/aspose.cells.charts/trendline) 对象以指定的类型和名称添加到此集合。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.trendline) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Trendline`](/cells/python-net/zh/aspose.cells.charts/trendline)
