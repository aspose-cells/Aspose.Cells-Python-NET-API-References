---
title: SheetRender类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells.rendering/sheetrender/
is_root: false
---
## SheetRender类
表示可以将工作表渲染为各种图像的工作表渲染，例如（BMP、PNG、JPEG、TIFF..）
该类的构造函数，在修改pagesetup、cell样式后必须使用。



SheetRender 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | SheetRender 的构造函数，需要 worksheet 和 ImageOrPrintOptions 作为参数|


### 属性
|属性|描述|
| :- | :- |
| [page_count](/cells/python-net/zh/aspose.cells.rendering/sheetrender/page_count) |获取当前工作表的总页数。|
| [page_scale](/cells/python-net/zh/aspose.cells.rendering/sheetrender/page_scale) |获取计算出的纸张页面比例。<br/>如果设置了 [`PageSetup.zoom`](/cells/python-net/zh/aspose.cells/pagesetup#zoom)，则返回设置的比例。否则，返回根据 [`PageSetup.fit_to_pages_wide`](/cells/python-net/zh/aspose.cells/pagesetup#fit_to_pages_wide) 和 [`PageSetup.fit_to_pages_tall`](/cells/python-net/zh/aspose.cells/pagesetup#fit_to_pages_tall) 计算出的比例。|


### 方法
|方法|描述|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_image/#int-str) |将特定页面渲染到文件。|
| [`to_image(self, page_index, stream)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) |将特定页面渲染到流中。|
| [`to_tiff(self, stream)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) |将整个工作表作为 Tiff 图像渲染到流中。|
| [`to_tiff(self, filename)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_tiff/#str) |将整个工作表作为 Tiff 图像呈现到文件中。|
| [`to_printer(self, printer_name)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#str) |将工作表渲染至打印机|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#str-str) |将工作表渲染至打印机|
| [`to_printer(self, printer_settings)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) |将工作表渲染至打印机|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) |将工作表渲染至打印机|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) |将工作表渲染至打印机|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) |获取输出图像的页面尺寸（以英寸为单位）。|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) |客户端可以通过该功能控制打印机在打印每一页时的页面设置。|
| [`dispose(self)`](/cells/python-net/zh/aspose.cells.rendering/sheetrender/dispose/#) |释放为渲染创建和使用的资源。|



### 也可以看看
* 模块[`aspose.cells.rendering`](..)
