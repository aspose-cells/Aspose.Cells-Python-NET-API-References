---
title: ColumnCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 250
url: /zh/aspose.cells/columncollection/
is_root: false
---
## ColumnCollection类
代表工作表中各个列（设置）的 [`Column`](/cells/python-net/zh/aspose.cells/column) 个对象的集合。
Column 对象仅代表整列的列宽、样式等设置，
与相应列中是否存在非空单元格（数据）无关。
而这个集合的“Count”仅仅代表这个集合中已经实例化的Column对象的数量，
与工作表中是否存在非空单元格（数据）无关。



ColumnCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/columncollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/columncollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/columncollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/columncollection/index_of/#aspose.cells.column-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/columncollection/last_index_of/#aspose.cells.column) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get_by_index(self, index)`](/cells/python-net/zh/aspose.cells/columncollection/get_by_index/#int) |通过索引获取列对象。|
| [`get_column_by_index(self, index)`](/cells/python-net/zh/aspose.cells/columncollection/get_column_by_index/#int) |根据列表中的位置获取 [`Column`](/cells/python-net/zh/aspose.cells/column) 对象。|
| [`get(self, column_index)`](/cells/python-net/zh/aspose.cells/columncollection/get/#int) |通过 .Net 添加 API for Python。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/columncollection/binary_search/#aspose.cells.column) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Column`](/cells/python-net/zh/aspose.cells/column)
