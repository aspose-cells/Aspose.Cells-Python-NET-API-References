---
title: ImageSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 860
url: /zh/aspose.cells/imagesaveoptions/
is_root: false
---
## ImageSaveOptions类
代表图像保存选项。
如需高级使用，请使用 [`WorkbookRender`](/cells/python-net/zh/aspose.cells.rendering/workbookrender) 或 [`SheetRender`](/cells/python-net/zh/aspose.cells.rendering/sheetrender)。



**继承：** [`ImageSaveOptions`](/cells/python-net/aspose.cells/imagesaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



ImageSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/imagesaveoptions/__init__/#) |创建保存图像文件的选项。|
| [`__init__(self, save_format)`](/cells/python-net/zh/aspose.cells/imagesaveoptions/__init__/#aspose.cells.saveformat) |创建保存图像文件的选项。|


### 属性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells/imagesaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells/imagesaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells/imagesaveoptions/cached_file_folder) |可用作数据缓存的临时文件的文件夹。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells/imagesaveoptions/validate_merged_areas) |指示在保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells/imagesaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证的区域。|
| [create_directory](/cells/python-net/zh/aspose.cells/imagesaveoptions/create_directory) |如果为 true 并且目录不存在，则在保存文件之前会自动创建目录。|
| [sort_names](/cells/python-net/zh/aspose.cells/imagesaveoptions/sort_names) |表示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells/imagesaveoptions/sort_external_names) |表示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells/imagesaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/imagesaveoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入的值超过 32K 时，它将被截断。|
| [update_smart_art](/cells/python-net/zh/aspose.cells/imagesaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [encrypt_document_properties](/cells/python-net/zh/aspose.cells/imagesaveoptions/encrypt_document_properties) |指示保存为 .xls 文件时是否加密文档属性。<br/>默认值为 true。|
| [image_or_print_options](/cells/python-net/zh/aspose.cells/imagesaveoptions/image_or_print_options) |附加图像创建选项。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`ImageSaveOptions`](/cells/python-net/zh/aspose.cells/imagesaveoptions)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
* 类 [`SheetRender`](/cells/python-net/zh/aspose.cells.rendering/sheetrender)
* 类 [`WorkbookRender`](/cells/python-net/zh/aspose.cells.rendering/workbookrender)
