---
title: GridJsWorkbook类
second_title: Aspose.Cells.GridJs for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cellsgridjs/gridjsworkbook/
is_root: false
---
## GridJsWorkbook类

代表GridJs的主要入口类



GridJsWorkbook 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/__init__/#) |构造 GridJsWorkbook 的新实例|


### 属性
|属性|描述|
| :- | :- |
| [settings](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/settings) |代表工作簿设置。|
| [cache_imp](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/cache_imp) |缓存存储的自定义实现，如果想以流的方式存储缓存，则需要设置并实现它。|
| [calculate_engine](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/calculate_engine) |计算引擎的自定义实现，如果要做自定义计算，需要设置并实现。|


### 方法
|方法|描述|
| :- | :- |
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-str-str) |从文件路径和打开密码导入 Excel 文件。|
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-str) |从文件路径导入 Excel 文件。|
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str) |从文件路径导入 Excel 文件。|
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str) |从文件流导入 Excel 文件，并带有加载格式和打开密码。|
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat) |从文件流导入 Excel 文件。|
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str) |从文件流导入 Excel 文件，并带有加载格式和打开密码。|
| [import_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat) |以加载格式从文件流导入 Excel 文件。|
| [export_to_json](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/export_to_json/#str) |从指定文件名的内存数据中获取 JSON 格式字符串。|
| [export_to_json](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/export_to_json/#) |获取默认空电子表格文件的 JSON 格式字符串。|
| [save_to_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_excel_file/#io.RawIOBase) |根据原始文件格式将内存数据保存到流中。|
| [save_to_excel_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_excel_file/#str) |将内存数据保存到文件路径中，如果文件有扩展名，则根据文件扩展名保存格式。|
| [save_to_pdf](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_pdf/#str) |将内存数据保存到文件路径，保存格式为pdf。|
| [save_to_pdf](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_pdf/#io.RawIOBase) |将内存数据保存到sream中，保存格式为pdf。|
| [save_to_xlsx](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_xlsx/#str) |将内存数据保存到文件路径，保存格式为xlsx。|
| [save_to_xlsx](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_xlsx/#io.RawIOBase) |将内存数据保存到sream中，保存格式为xlsx。|
| [save_to_html](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_html/#str) |将内存数据保存到文件路径，保存格式为html。|
| [save_to_html](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_html/#io.RawIOBase) |将内存数据保存到sream中，保存格式为html|
| [get_json_str_by_uid](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/get_json_str_by_uid/#str-str) |通过指定的唯一id从文件缓存中获取JSON格式字符串。|
| [get_uid_for_file](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/get_uid_for_file/#str) |获取文件缓存的唯一 ID。|
| [import_excel_file_from_json](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file_from_json/#str) |从 JSON 格式字符串导入 Excel 文件。|
| [merge_excel_file_from_json](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/merge_excel_file_from_json/#str-str) |对内存数据应用批量更新。|
| [save_to_cache_with_file_name](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/save_to_cache_with_file_name/#str-str-str) |将内存数据保存到指定文件名的缓存文件中，并设置打开密码，保存格式根据文件名的文件扩展名而定。|
| [get_image_stream](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/get_image_stream/#str-str) |从内存数据中获取图像流。|
| [get_ole](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/get_ole/#str-str-int-any) |获取嵌入的 ole 对象的字节数组数据。|
| [update_cell](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/update_cell/#str-str) |应用更新操作。|
| [insert_image](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/insert_image/#str-str-io.RawIOBase-str) |从文件流或 URL 插入工作表中的图像（应提供文件流或 URL）<br/>或/细胞/<br/>插入 sh/cells/n p.type 是 AutoShapeType 之一|
| [copy_image_or_shape](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/copy_image_or_shape/#str-str) |复制图像或形状。|
| [error_json](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/error_json/#str) |获取 JSON 格式的错误消息字符串。|
| [get_grid_load_format](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/get_grid_load_format/#str) |通过文件扩展名获取加载格式|
| [get_image_url](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/get_image_url/#str-str-str) |获取图像 URL。|
| [set_image_url_base](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook/set_image_url_base/#str) |  |



### 也可以看看
* 模块[`aspose.cellsgridjs`](..)
