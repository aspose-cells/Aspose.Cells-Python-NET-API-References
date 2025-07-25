---
title: LoadFilter类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 940
url: /zh/aspose.cells/loadfilter/
is_root: false
---
## LoadFilter类
表示从模板加载工作簿时提供加载数据选项的过滤器。



LoadFilter 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/loadfilter/__init__/#) |使用默认过滤选项 LoadDataFilterOptions.All 构造一个 LoadFilter。|
| [`__init__(self, opts)`](/cells/python-net/zh/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) |使用给定的过滤选项构造一个 LoadFilter。|


### 属性
|属性|描述|
| :- | :- |
| [load_data_filter_options](/cells/python-net/zh/aspose.cells/loadfilter/load_data_filter_options) |过滤选项指示应加载哪些数据。|
| [sheets_in_loading_order](/cells/python-net/zh/aspose.cells/loadfilter/sheets_in_loading_order) |指定要加载的工作表（索引）和顺序。<br/>默认值为空，表示按照模板文件中的默认顺序加载所有工作表。<br/>如果不为空并且某个工作表的索引不在返回的数组中，则不会加载该工作表。|


### 方法
|方法|描述|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/zh/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) |在加载给定的工作表之前准备过滤选项。<br/>用户的 LoadFilter 实现可以在这里更改 LoadDataFilterOptions<br/>表示如何为该工作表加载数据。|



### 注意事项

用户可以指定过滤选项或实现自己的 LoadFilter 来指定如何加载数据。

### 也可以看看
* 模块[`aspose.cells`](..)
