---
title: Config类
second_title: Aspose.Cells.GridJs for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cellsgridjs/config/
is_root: false
---
## Config类

代表GridJs的所有设置



Config 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cellsgridjs/config/__init__/#) |构造一个新的 Config 实例|


### 属性
|属性|描述|
| :- | :- |
| [save_html_as_zip](/cells/python-net/zh/aspose.cellsgridjs/config/save_html_as_zip) |设置/获取是否将 html 文件保存为 zip 存档，默认为 false。|
| [same_image_detecting](/cells/python-net/zh/aspose.cellsgridjs/config/same_image_detecting) |设置/获取是否检查图片是否同源，默认为true<br/>默认值是true。|
| [auto_optimize_for_large_cells](/cells/python-net/zh/aspose.cellsgridjs/config/auto_optimize_for_large_cells) |设置/获取是否自动优化具有大单元格的工作表的加载性能<br/>忽略一些样式/边框以减少加载时间<br/>默认值是true。|
| [islimit_shape_or_image](/cells/python-net/zh/aspose.cellsgridjs/config/islimit_shape_or_image) |设置/获取是否限制一张工作表内的总显示形状/图像数量，如果设置为 true，<br/> GridJs 会将一个工作表内的总显示形状/图像大小限制为 MaxShapeOrImageCount<br/>默认值是true。|
| [max_shape_or_image_count](/cells/python-net/zh/aspose.cellsgridjs/config/max_shape_or_image_count) |设置/获取活动工作表内的总显示形状/图像数量，当 IslimitShapes=true 时会受影响。<br/>默认值为 100。|
| [max_total_shape_or_image_count](/cells/python-net/zh/aspose.cellsgridjs/config/max_total_shape_or_image_count) |设置/获取整个工作簿内显示形状/图像的总数，当IslimitShapes=true时会影响。<br/>默认值为 300。|
| [max_shape_or_image_width_or_height](/cells/python-net/zh/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) |设置/获取形状/图像的最大宽度或高度，GridJs将忽略宽度或高度大于此的形状/图像，当IslimitShapes=true时会影响。<br/>默认值为 10000。|
| [max_pdf_save_seconds](/cells/python-net/zh/aspose.cellsgridjs/config/max_pdf_save_seconds) |设置/获取保存为 pdf 时的最大超时秒数。<br/>默认值为 10。|
| [ignore_empty_content](/cells/python-net/zh/aspose.cellsgridjs/config/ignore_empty_content) |设置/获取是否显示最大范围，包括数据、样式、合并单元格和形状。<br/>如果最后一行或最后一列包含没有值和公式但具有自定义样式的单元格<br/>那么当这个vlaue为true时我们将不会显示该行/列。<br/>默认值是true 。|
| [use_print_area](/cells/python-net/zh/aspose.cellsgridjs/config/use_print_area) |设置/获取当工作表具有 PrintArea 的 PageSetup 设置时是否使用 PageSetup.PrintArea 作为 UI 显示范围。<br/>默认值为 false 。|
| [load_time_out](/cells/python-net/zh/aspose.cellsgridjs/config/load_time_out) |设置/获取加载文件时的超时中断（以毫秒为单位），当加载文件的花费时间比预期长时，将引发异常。<br/>默认值为-1，即不设置超时中断。|
| [show_chart_sheet](/cells/python-net/zh/aspose.cellsgridjs/config/show_chart_sheet) |设置/获取是否显示图表工作表。<br/>默认值为 false 。|
| [page_size](/cells/python-net/zh/aspose.cellsgridjs/config/page_size) |设置/获取是否进行分页<br/>GridJs会根据PageSize限制行大小，如果PageSize为-1，则不会进行分页<br/>默认值为-1|
| [empty_sheet_max_row](/cells/python-net/zh/aspose.cellsgridjs/config/empty_sheet_max_row) |设置/获取空工作表的默认最大行。<br/>默认值为 12。|
| [empty_sheet_max_col](/cells/python-net/zh/aspose.cellsgridjs/config/empty_sheet_max_col) |设置/获取空工作表的默认最大列。<br/>默认值为 15。|
| [picture_cache_directory](/cells/python-net/zh/aspose.cellsgridjs/config/picture_cache_directory) |设置/获取图片的缓存目录（当GridJsWorkbook.CacheImp为null时生效）<br/>默认路径是 FileCacheDirectory 内的“_piccache”。|
| [file_cache_directory](/cells/python-net/zh/aspose.cellsgridjs/config/file_cache_directory) |设置/获取电子表格文件的缓存目录。<br/>在使用GridJs之前，我们需要将其设置为特定路径。|


### 方法
|方法|描述|
| :- | :- |
| [set_license](/cells/python-net/zh/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/zh/aspose.cellsgridjs/config/set_license/#io.RawIOBase) |许可该组件。|
| [set_font_folder](/cells/python-net/zh/aspose.cellsgridjs/config/set_font_folder/#str-bool) |设置字体文件夹|
| [set_font_folders](/cells/python-net/zh/aspose.cellsgridjs/config/set_font_folders/#list-bool) |设置字体文件夹|



### 也可以看看
* 模块[`aspose.cellsgridjs`](..)
