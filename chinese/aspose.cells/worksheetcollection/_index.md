---
title: WorksheetCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1700
url: /zh/aspose.cells/worksheetcollection/
is_root: false
---
## WorksheetCollection类
封装了 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet) 对象的集合。



WorksheetCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/zh/aspose.cells/worksheetcollection/web_extension_task_panes) |获取任务窗格的列表。|
| [web_extensions](/cells/python-net/zh/aspose.cells/worksheetcollection/web_extensions) |获取任务窗格的列表。|
| [threaded_comment_authors](/cells/python-net/zh/aspose.cells/worksheetcollection/threaded_comment_authors) |获取线索评论作者列表。|
| [is_refresh_all_connections](/cells/python-net/zh/aspose.cells/worksheetcollection/is_refresh_all_connections) |指示在 MS Excel 中打开文件时是否刷新所有连接。|
| [names](/cells/python-net/zh/aspose.cells/worksheetcollection/names) |获取电子表格中所有 Name 对象的集合。|
| [active_sheet_name](/cells/python-net/zh/aspose.cells/worksheetcollection/active_sheet_name) |表示打开电子表格时活动工作表的名称。|
| [active_sheet_index](/cells/python-net/zh/aspose.cells/worksheetcollection/active_sheet_index) |表示打开电子表格时活动工作表的索引。|
| [dxfs](/cells/python-net/zh/aspose.cells/worksheetcollection/dxfs) |获取主差异格式化记录。|
| [xml_maps](/cells/python-net/zh/aspose.cells/worksheetcollection/xml_maps) |获取和设置工作簿中的 XML 映射。|
| [built_in_document_properties](/cells/python-net/zh/aspose.cells/worksheetcollection/built_in_document_properties) |返回 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合表示电子表格的所有内置文档属性。|
| [custom_document_properties](/cells/python-net/zh/aspose.cells/worksheetcollection/custom_document_properties) |返回 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合表示电子表格的所有自定义文档属性。|
| [ole_size](/cells/python-net/zh/aspose.cells/worksheetcollection/ole_size) |获取和设置工作簿文件用作 Ole 对象时的显示大小。|
| [external_links](/cells/python-net/zh/aspose.cells/worksheetcollection/external_links) |表示工作簿中的外部链接。|
| [table_styles](/cells/python-net/zh/aspose.cells/worksheetcollection/table_styles) |获取 [`WorksheetCollection.table_styles`](/cells/python-net/zh/aspose.cells/worksheetcollection#table_styles) 对象。|
| [revision_logs](/cells/python-net/zh/aspose.cells/worksheetcollection/revision_logs) |代表修订日志。|
| [capacity](/cells/python-net/zh/aspose.cells/worksheetcollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [get](/cells/python-net/zh/aspose.cells/worksheetcollection/get/#int) |通过 .Net 添加 API for Python，因为不支持此[int index]|
| [get](/cells/python-net/zh/aspose.cells/worksheetcollection/get/#str) |通过 .Net 添加 API for Python，因为不支持此[字符串sheetName]|
| [add](/cells/python-net/zh/aspose.cells/worksheetcollection/add/#aspose.cells.SheetType) |将工作表添加到集合中。|
| [add](/cells/python-net/zh/aspose.cells/worksheetcollection/add/#) |将工作表添加到集合中。|
| [add](/cells/python-net/zh/aspose.cells/worksheetcollection/add/#str) |将工作表添加到集合中。|
| [register_add_in_function](/cells/python-net/zh/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) |将插件功能添加到工作簿中|
| [register_add_in_function](/cells/python-net/zh/aspose.cells/worksheetcollection/register_add_in_function/#int-str) |将插件功能添加到工作簿中|
| [add_copy](/cells/python-net/zh/aspose.cells/worksheetcollection/add_copy/#str) |将工作表添加到集合并从现有工作表复制数据。|
| [add_copy](/cells/python-net/zh/aspose.cells/worksheetcollection/add_copy/#int) |将工作表添加到集合并从现有工作表复制数据。|
| [add_copy](/cells/python-net/zh/aspose.cells/worksheetcollection/add_copy/#list-list) |复制一组工作表。|
| [get_range_by_name](/cells/python-net/zh/aspose.cells/worksheetcollection/get_range_by_name/#str) |通过预定义名称获取 Range 对象。|
| [get_range_by_name](/cells/python-net/zh/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) |通过预定义名称或表名称获取 [`Range`](/cells/python-net/zh/aspose.cells/range)|
| [copy_to](/cells/python-net/zh/aspose.cells/worksheetcollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells/worksheetcollection/index_of/#aspose.cells.Worksheet-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells/worksheetcollection/index_of/#aspose.cells.Worksheet-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.Worksheet) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.Worksheet-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.Worksheet-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [create_range](/cells/python-net/zh/aspose.cells/worksheetcollection/create_range/#str-int) |从范围地址创建 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [create_union_range](/cells/python-net/zh/aspose.cells/worksheetcollection/create_union_range/#str-int) |从范围地址创建 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [get_sheet_by_code_name](/cells/python-net/zh/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) |通过代码名称获取工作表。|
| [sort_names](/cells/python-net/zh/aspose.cells/worksheetcollection/sort_names/#) |对定义的名称进行排序。|
| [swap_sheet](/cells/python-net/zh/aspose.cells/worksheetcollection/swap_sheet/#int-int) |交换两张纸。|
| [remove_at](/cells/python-net/zh/aspose.cells/worksheetcollection/remove_at/#str) |删除指定名称的元素。|
| [get_named_ranges](/cells/python-net/zh/aspose.cells/worksheetcollection/get_named_ranges/#) |获取电子表格中所有预定义的命名范围。|
| [get_named_ranges_and_tables](/cells/python-net/zh/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) |获取电子表格中所有预定义的命名范围。|
| [set_ole_size](/cells/python-net/zh/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) |设置工作簿文件用作 Ole 对象时的显示大小。|
| [clear_pivottables](/cells/python-net/zh/aspose.cells/worksheetcollection/clear_pivottables/#) |从电子表格中清除数据透视表。|
| [refresh_all](/cells/python-net/zh/aspose.cells/worksheetcollection/refresh_all/#) |使用数据透视源刷新所有数据透视表和图表。|
| [refresh_pivot_tables](/cells/python-net/zh/aspose.cells/worksheetcollection/refresh_pivot_tables/#) |刷新 WorksheetCollection 中的所有数据透视表。|
| [binary_search](/cells/python-net/zh/aspose.cells/worksheetcollection/binary_search/#aspose.cells.Worksheet) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



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
