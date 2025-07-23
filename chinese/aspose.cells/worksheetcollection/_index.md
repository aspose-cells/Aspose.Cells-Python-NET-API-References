---
title: WorksheetCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1610
url: /zh/aspose.cells/worksheetcollection/
is_root: false
---
## WorksheetCollection类
封装 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet) 个对象的集合。



WorksheetCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/zh/aspose.cells/worksheetcollection/web_extension_task_panes) |获取任务窗格的列表。|
| [web_extensions](/cells/python-net/zh/aspose.cells/worksheetcollection/web_extensions) |获取任务窗格的列表。|
| [threaded_comment_authors](/cells/python-net/zh/aspose.cells/worksheetcollection/threaded_comment_authors) |获取主题注意事项作者列表。|
| [is_refresh_all_connections](/cells/python-net/zh/aspose.cells/worksheetcollection/is_refresh_all_connections) |指示在 MS Excel 中打开文件时是否刷新所有连接。|
| [names](/cells/python-net/zh/aspose.cells/worksheetcollection/names) |获取电子表格中所有 Name 对象的集合。|
| [active_sheet_name](/cells/python-net/zh/aspose.cells/worksheetcollection/active_sheet_name) |表示电子表格打开时活动工作表的名称。|
| [active_sheet_index](/cells/python-net/zh/aspose.cells/worksheetcollection/active_sheet_index) |表示电子表格打开时活动工作表的索引。|
| [dxfs](/cells/python-net/zh/aspose.cells/worksheetcollection/dxfs) |获取主差异格式记录。|
| [xml_maps](/cells/python-net/zh/aspose.cells/worksheetcollection/xml_maps) |获取并设置工作簿中的 XML 映射。|
| [built_in_document_properties](/cells/python-net/zh/aspose.cells/worksheetcollection/built_in_document_properties) |返回一个 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合代表电子表格的所有内置文档属性。|
| [custom_document_properties](/cells/python-net/zh/aspose.cells/worksheetcollection/custom_document_properties) |返回代表电子表格的所有自定义文档属性的 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合。|
| [ole_size](/cells/python-net/zh/aspose.cells/worksheetcollection/ole_size) |获取并设置当工作簿文件用作 Ole 对象时的显示大小。|
| [external_links](/cells/python-net/zh/aspose.cells/worksheetcollection/external_links) |代表工作簿中的外部链接。|
| [table_styles](/cells/python-net/zh/aspose.cells/worksheetcollection/table_styles) |获取 [`WorksheetCollection.table_styles`](/cells/python-net/zh/aspose.cells/worksheetcollection#table_styles) 对象。|
| [revision_logs](/cells/python-net/zh/aspose.cells/worksheetcollection/revision_logs) |代表修订日志。|
| [sensitivity_labels](/cells/python-net/zh/aspose.cells/worksheetcollection/sensitivity_labels) |代表所有敏感度标签。|
| [capacity](/cells/python-net/zh/aspose.cells/worksheetcollection/capacity) |获取或设置数组列表可包含的元素数量。|



获取指定索引处的 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet) 元素。
### 索引器
|名称|描述|
| :- | :- |
| [index] |元素的从零开始的索引。|


### 方法
|方法|描述|
| :- | :- |
| [`get(self, index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get/#int) |通过 .Net 添加 API for Python，因为不支持 this[int index]|
| [`get(self, sheet_name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get/#str) |通过 .Net 添加 API for Python，因为此 [string sheetName] 不受支持|
| [`add(self, type)`](/cells/python-net/zh/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) |将工作表添加到集合中。|
| [`add(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/add/#) |将工作表添加到集合中。|
| [`add(self, sheet_name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/add/#str) |将工作表添加到集合中。|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/zh/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) |在工作簿中添加插件功能|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/register_add_in_function/#int-str) |在工作簿中添加插件功能|
| [`add_copy(self, sheet_name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/add_copy/#str) |将工作表添加到集合并从现有工作表中复制数据。|
| [`add_copy(self, sheet_index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/add_copy/#int) |将工作表添加到集合并从现有工作表中复制数据。|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/zh/aspose.cells/worksheetcollection/add_copy/#list-list) |复制一组工作表。|
| [`get_range_by_name(self, range_name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get_range_by_name/#str) |通过预定义名称获取 Range 对象。|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) |通过预定义名称或表名获取 [`Range`](/cells/python-net/zh/aspose.cells/range)|
| [`refresh_pivot_tables(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/refresh_pivot_tables/#) |刷新 Excel 文件中的所有数据透视表。|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/zh/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) |刷新 Excel 文件中的所有数据透视表。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/worksheetcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`create_range(self, address, sheet_index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/create_range/#str-int) |从范围的地址创建一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/create_union_range/#str-int) |从范围的地址创建一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) |通过代码名称获取工作表。|
| [`sort_names(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/sort_names/#) |对定义的名称进行排序。|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/zh/aspose.cells/worksheetcollection/swap_sheet/#int-int) |交换两张表。|
| [`remove_by_name(self, name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/remove_by_name/#str) |通过工作表名称删除工作表。(CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/zh/aspose.cells/worksheetcollection/remove_by_index/#int) |通过工作表索引删除工作表|
| [`remove_at(self, name)`](/cells/python-net/zh/aspose.cells/worksheetcollection/remove_at/#str) |删除指定名称的元素。|
| [`get_named_ranges(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get_named_ranges/#) |获取电子表格中所有预定义的命名范围。|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) |获取电子表格中所有预定义的命名范围。|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/zh/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) |当工作簿文件用作 Ole 对象时设置显示的大小。|
| [`clear_pivottables(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/clear_pivottables/#) |从电子表格中清除数据透视表。|
| [`refresh_all(self)`](/cells/python-net/zh/aspose.cells/worksheetcollection/refresh_all/#) |使用数据透视源刷新所有数据透视表和图表。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
