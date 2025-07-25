---
title: FontConfigs类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 670
url: /zh/aspose.cells/fontconfigs/
is_root: false
---
## FontConfigs类
指定字体设置



FontConfigs 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/fontconfigs/__init__/#) |构造一个新的 FontConfigs 实例|


### 属性
|属性|描述|
| :- | :- |
| [default_font_name](/cells/python-net/zh/aspose.cells/fontconfigs/default_font_name) |获取或设置默认字体名称。|
| [prefer_system_font_substitutes](/cells/python-net/zh/aspose.cells/fontconfigs/prefer_system_font_substitutes) |指示当不存在某种字体且未设置该字体的替代时，是否首先使用系统字体替代。<br/>例如，在 Ubuntu 上，“Arial”字体通常被“Liberation Sans”取代。<br/>默认值为 false。|


### 方法
|方法|描述|
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/zh/aspose.cells/fontconfigs/is_font_available/#str) |指示字体是否可用。|
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/zh/aspose.cells/fontconfigs/get_font_file_data_info/#str-bool-bool-bool) |获取字体文件数据的数据信息。|
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/zh/aspose.cells/fontconfigs/set_font_substitutes/#str-list) |给定原始字体名称的字体替代名称。|
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/zh/aspose.cells/fontconfigs/get_font_substitutes/#str) |如果原始字体不存在，则返回包含要使用的字体替代名称的数组。|
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/zh/aspose.cells/fontconfigs/set_font_folder/#str-bool) |设置字体文件夹|
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/zh/aspose.cells/fontconfigs/set_font_folders/#list-bool) |设置字体文件夹|
| [`set_font_sources(, sources)`](/cells/python-net/zh/aspose.cells/fontconfigs/set_font_sources/#list) |  |
| [`get_font_sources()`](/cells/python-net/zh/aspose.cells/fontconfigs/get_font_sources/#) |获取包含源列表的数组的副本|



### 也可以看看
* 模块[`aspose.cells`](..)
