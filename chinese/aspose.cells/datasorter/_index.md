---
title: DataSorter类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 410
url: /zh/aspose.cells/datasorter/
is_root: false
---
## DataSorter类
DataSorter 的摘要说明。



DataSorter 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [keys](/cells/python-net/zh/aspose.cells/datasorter/keys) |获取数据排序器的键列表。|
| [has_headers](/cells/python-net/zh/aspose.cells/datasorter/has_headers) |表示范围是否有标题。|
| [key1](/cells/python-net/zh/aspose.cells/datasorter/key1) |表示第一个排序列的索引（绝对位置，A 列为 0，B 列为 1，...）。|
| [order1](/cells/python-net/zh/aspose.cells/datasorter/order1) |表示第一个键的排序顺序。|
| [key2](/cells/python-net/zh/aspose.cells/datasorter/key2) |表示第二个排序列索引（绝对位置，A 列为 0，B 列为 1，...）。|
| [order2](/cells/python-net/zh/aspose.cells/datasorter/order2) |表示第二个键的排序顺序。|
| [key3](/cells/python-net/zh/aspose.cells/datasorter/key3) |表示第三个排序列索引（绝对位置，A 列为 0，B 列为 1，...）。|
| [order3](/cells/python-net/zh/aspose.cells/datasorter/order3) |表示第三个键的排序顺序。|
| [sort_left_to_right](/cells/python-net/zh/aspose.cells/datasorter/sort_left_to_right) |True 表示排序方向是从左到右。<br/>False 表示排序方向是从上到下。<br/>默认值为 false。|
| [case_sensitive](/cells/python-net/zh/aspose.cells/datasorter/case_sensitive) |获取或设置比较字符串时是否区分大小写。|
| [sort_as_number](/cells/python-net/zh/aspose.cells/datasorter/sort_as_number) |指示是否对任何看起来像数字的东西进行排序。|


### 方法
|方法|描述|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/zh/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) |添加已排序列索引和排序顺序。|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/zh/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) |使用自定义排序列表添加已排序列索引和排序顺序。|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/zh/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) |使用自定义排序列表添加已排序列索引和排序顺序。|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/zh/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) |使用自定义排序列表添加已排序列索引和排序顺序。|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/zh/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) |对区域的数据进行排序。|
| [`sort(self, cells, area)`](/cells/python-net/zh/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) |对区域的数据进行排序。|
| [`sort(self)`](/cells/python-net/zh/aspose.cells/datasorter/sort/#) |对范围内的数据进行排序。|
| [`clear(self)`](/cells/python-net/zh/aspose.cells/datasorter/clear/#) |清除所有设置。|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/zh/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) |添加颜色排序键。|



### 例子

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
