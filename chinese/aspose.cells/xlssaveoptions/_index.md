---
title: XlsSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1630
url: /zh/aspose.cells/xlssaveoptions/
is_root: false
---
## XlsSaveOptions类
代表 Excel 97-2003 文件格式的保存选项：xls 和 xlt。



**继承：** [`XlsSaveOptions`](/cells/python-net/aspose.cells/xlssaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



XlsSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/xlssaveoptions/__init__/#) |创建用于保存 Excel 97-2003 xls 文件的选项。|
| [`__init__(self, save_format)`](/cells/python-net/zh/aspose.cells/xlssaveoptions/__init__/#aspose.cells.saveformat) |创建用于保存 Excel 97-2003 xls/xlt 文件的选项。|


### 属性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells/xlssaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells/xlssaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells/xlssaveoptions/cached_file_folder) |可用作数据缓存的临时文件的文件夹。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells/xlssaveoptions/validate_merged_areas) |指示在保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells/xlssaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证的区域。|
| [create_directory](/cells/python-net/zh/aspose.cells/xlssaveoptions/create_directory) |如果为 true 并且目录不存在，则在保存文件之前会自动创建目录。|
| [sort_names](/cells/python-net/zh/aspose.cells/xlssaveoptions/sort_names) |表示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells/xlssaveoptions/sort_external_names) |表示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells/xlssaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/xlssaveoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入的值超过 32K 时，它将被截断。|
| [update_smart_art](/cells/python-net/zh/aspose.cells/xlssaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [encrypt_document_properties](/cells/python-net/zh/aspose.cells/xlssaveoptions/encrypt_document_properties) |指示保存为 .xls 文件时是否加密文档属性。<br/>默认值为 true。|
| [is_template](/cells/python-net/zh/aspose.cells/xlssaveoptions/is_template) |指示是否保存模板文件。|
| [match_color](/cells/python-net/zh/aspose.cells/xlssaveoptions/match_color) |表示是否匹配字体颜色，因为标准调色板中有 56 种颜色。|
| [wps_compatibility](/cells/python-net/zh/aspose.cells/xlssaveoptions/wps_compatibility) |指示是否使 xls 与 WPS 更加兼容。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
* 类 [`XlsSaveOptions`](/cells/python-net/zh/aspose.cells/xlssaveoptions)
