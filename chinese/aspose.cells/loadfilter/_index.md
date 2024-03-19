---
title: LoadFilter类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1050
url: /zh/aspose.cells/loadfilter/
is_root: false
---
## LoadFilter类
表示过滤器，该过滤器提供从模板加载工作簿时加载数据的选项。



LoadFilter 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/loadfilter/__init__/#) |使用默认筛选器选项 LoadDataFilterOptions.All 构造一个 LoadFilter。|
| [__init__](/cells/python-net/zh/aspose.cells/loadfilter/__init__/#aspose.cells.LoadDataFilterOptions) |使用给定的过滤器选项构造一个 LoadFilter。|


### 特性
|属性|描述|
| :- | :- |
| [load_data_filter_options](/cells/python-net/zh/aspose.cells/loadfilter/load_data_filter_options) |过滤器选项指示应加载哪些数据。|
| [sheets_in_loading_order](/cells/python-net/zh/aspose.cells/loadfilter/sheets_in_loading_order) |指定要加载的工作表（索引）和顺序。<br/>默认为空，表示按照模板文件中的默认顺序加载所有sheet。<br/>如果不为 null 并且某些工作表的索引不在返回的数组中，则不会加载该工作表。|


### 方法
|方法|描述|
| :- | :- |
| [start_sheet](/cells/python-net/zh/aspose.cells/loadfilter/start_sheet/#aspose.cells.Worksheet) |在加载给定工作表之前准备过滤器选项。<br/>用户的LoadFilter实现可以在这里更改LoadDataFilterOptions<br/>表示如何加载此工作表的数据。|



### 评论

用户可以指定过滤器选项或实现自己的LoadFilter来指定如何加载数据。

### 也可以看看
* 模块[`aspose.cells`](..)
