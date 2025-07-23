---
title: OoxmlSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1050
url: /zh/aspose.cells/ooxmlsaveoptions/
is_root: false
---
## OoxmlSaveOptions类
表示保存 Office Open XML 文件的选项。



**继承：** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



OoxmlSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/__init__/#) |创建用于保存 Office Open XML 文件的选项。|
| [`__init__(self, save_format)`](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) |创建用于保存 Office Open XML 文件的选项。|


### 属性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/cached_file_folder) |可用作数据缓存的临时文件的文件夹。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/validate_merged_areas) |指示在保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证的区域。|
| [create_directory](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/create_directory) |如果为 true 并且目录不存在，则在保存文件之前会自动创建目录。|
| [sort_names](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/sort_names) |表示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/sort_external_names) |表示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入的值超过 32K 时，它将被截断。|
| [update_smart_art](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [encrypt_document_properties](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) |指示保存为 .xls 文件时是否加密文档属性。<br/>默认值为 true。|
| [export_cell_name](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/export_cell_name) |指示是否将单元格名称导出到 Excel2007 .xlsx (.xlsm, .xltx, .xltm) 文件。<br/>如果输出文件可以被 SQL Server DTS 访问，则该值必须为 true。<br/>将该值设置为 false 将大大提高性能并在创建大文件时减小文件大小。<br/>默认值为 true。|
| [update_zoom](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/update_zoom) |指示是否在保存文件之前更新缩放因子<br/>如果 PageSetup.FitToPagesWide 和 PageSetup.FitToPagesTall 属性控制工作表的缩放方式。|
| [enable_zip64](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/enable_zip64) |编写 zip 档案时始终使用 ZIP64 扩展，即使没有必要。|
| [embed_ooxml_as_ole_object](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) |指示是否将OleObject的Ooxml文件嵌入为ole对象。|
| [compression_type](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/compression_type) |获取并设置 ooxml 文件的压缩类型。|
| [wps_compatibility](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions/wps_compatibility) |指示是否使 xls 与 WPS 更加兼容。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`OoxmlSaveOptions`](/cells/python-net/zh/aspose.cells/ooxmlsaveoptions)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
