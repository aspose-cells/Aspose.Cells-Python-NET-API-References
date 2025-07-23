---
title: JsonSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 920
url: /zh/aspose.cells/jsonsaveoptions/
is_root: false
---
## JsonSaveOptions类
表示将工作簿保存为 json 文件的选项。



**继承：** [`JsonSaveOptions`](/cells/python-net/aspose.cells/jsonsaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



JsonSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/jsonsaveoptions/__init__/#) |创建用于保存 json 文件的选项。|


### 属性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells/jsonsaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells/jsonsaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells/jsonsaveoptions/cached_file_folder) |可用作数据缓存的临时文件的文件夹。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells/jsonsaveoptions/validate_merged_areas) |指示在保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells/jsonsaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证的区域。|
| [create_directory](/cells/python-net/zh/aspose.cells/jsonsaveoptions/create_directory) |如果为 true 并且目录不存在，则在保存文件之前会自动创建目录。|
| [sort_names](/cells/python-net/zh/aspose.cells/jsonsaveoptions/sort_names) |表示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells/jsonsaveoptions/sort_external_names) |表示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells/jsonsaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/jsonsaveoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入的值超过 32K 时，它将被截断。|
| [update_smart_art](/cells/python-net/zh/aspose.cells/jsonsaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [encrypt_document_properties](/cells/python-net/zh/aspose.cells/jsonsaveoptions/encrypt_document_properties) |指示保存为 .xls 文件时是否加密文档属性。<br/>默认值为 true。|
| [export_style_pool](/cells/python-net/zh/aspose.cells/jsonsaveoptions/export_style_pool) |指示是否将样式集体导出或单独导出到每个单元格。|
| [export_hyperlink_type](/cells/python-net/zh/aspose.cells/jsonsaveoptions/export_hyperlink_type) |表示将超链接导出为json的类型。|
| [skip_empty_rows](/cells/python-net/zh/aspose.cells/jsonsaveoptions/skip_empty_rows) |指示是否跳过空行。|
| [sheet_indexes](/cells/python-net/zh/aspose.cells/jsonsaveoptions/sheet_indexes) |表示导出工作表的索引。|
| [schemas](/cells/python-net/zh/aspose.cells/jsonsaveoptions/schemas) |每个工作表的原始 json 模式。|
| [export_area](/cells/python-net/zh/aspose.cells/jsonsaveoptions/export_area) |获取或设置导出范围。|
| [has_header_row](/cells/python-net/zh/aspose.cells/jsonsaveoptions/has_header_row) |指示范围是否包含标题行。|
| [export_as_string](/cells/python-net/zh/aspose.cells/jsonsaveoptions/export_as_string) |将单元格的字符串值导出为 json。|
| [indent](/cells/python-net/zh/aspose.cells/jsonsaveoptions/indent) |表示缩进。|
| [export_nested_structure](/cells/python-net/zh/aspose.cells/jsonsaveoptions/export_nested_structure) |导出为父子层次Json结构。|
| [export_empty_cells](/cells/python-net/zh/aspose.cells/jsonsaveoptions/export_empty_cells) |指示是否将空单元格导出为空。|
| [always_export_as_json_object](/cells/python-net/zh/aspose.cells/jsonsaveoptions/always_export_as_json_object) |指示是否始终将 Excel 导出为 JSON 作为对象，即使文件中只有一个工作表。|
| [to_excel_struct](/cells/python-net/zh/aspose.cells/jsonsaveoptions/to_excel_struct) |是否转换为Excel文件的json结构体。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`JsonSaveOptions`](/cells/python-net/zh/aspose.cells/jsonsaveoptions)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
