---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
将图表添加到集合中。


### 返回

[`Chart`](/cells/python-net/zh/aspose.cells.charts/chart) 对象索引。


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/zh/aspose.cells.charts/charttype) |图表类型|
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| lower_right_row | int |右下行索引|
| lower_right_column | int |右下角列索引|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
将图表添加到集合中。


### 返回

[`Chart`](/cells/python-net/zh/aspose.cells.charts/chart) 对象索引。


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/zh/aspose.cells.charts/charttype) |图表类型|
| data_range | str |指定图表的数据范围|
| top_row | int |左上行索引。|
| left_column | int |左上角的列索引。|
| right_row | int |右下行索引|
| bottom_column | int |右下角列索引|
### 注意事项

注意：此成员现已过时。相反，
请使用[`ChartCollection.add`](/cells/python-net/zh/aspose.cells.charts/chartcollection/add)属性。
该房产将于 2022 年 5 月起 12 个月后拆除。
Aspose 对于您所遇到的不便深表歉意。

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
添加带有预设模板的图表。


### 返回

[`Chart`](/cells/python-net/zh/aspose.cells.charts/chart) 对象索引。


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| data | bytes |图表模板文件（.crtx）的数据。|
| data_range | str |指定图表的数据范围|
| is_vertical | bool |指定是否按行或按列绘制单元格值范围的序列。|
| top_row | int |左上行索引。|
| left_column | int |左上角的列索引。|
| right_row | int |右下行索引|
| bottom_column | int |右下角列索引|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
将图表添加到集合中。


### 返回

[`Chart`](/cells/python-net/zh/aspose.cells.charts/chart) 对象索引。


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/zh/aspose.cells.charts/charttype) |图表类型|
| data_range | str |指定图表的数据范围|
| is_vertical | bool |指定是否按行或按列绘制单元格值范围的序列。|
| top_row | int |左上行索引。|
| left_column | int |左上角的列索引。|
| right_row | int |右下行索引|
| bottom_column | int |右下角列索引|



### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)
* 类 [`ChartCollection`](/cells/python-net/zh/aspose.cells.charts/chartcollection)
