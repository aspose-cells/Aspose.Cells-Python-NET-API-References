---
title: SheetRender类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells.rendering/sheetrender/
is_root: false
---
## SheetRender类
表示一个工作表渲染，可以将工作表渲染为各种图像，例如（BMP、PNG、JPEG、TIFF..）
该类的构造函数，必须在修改pagesetup、cell style后使用。



SheetRender 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | SheetRender的构造，需要worksheet和ImageOrPrintOptions作为参数|


### 特性
|属性|描述|
| :- | :- |
| [page_count](/cells/python-net/zh/aspose.cells.rendering/sheetrender/page_count) |获取当前工作表的总页数。|
| [page_scale](/cells/python-net/zh/aspose.cells.rendering/sheetrender/page_scale) |获取工作表的计算页面比例。<br/>如果设置了 [`PageSetup.zoom`](/cells/python-net/zh/aspose.cells/pagesetup#zoom)，则返回设置的比例。否则，返回根据[`PageSetup.fit_to_pages_wide`](/cells/python-net/zh/aspose.cells/pagesetup#fit_to_pages_wide)和[`PageSetup.fit_to_pages_tall`](/cells/python-net/zh/aspose.cells/pagesetup#fit_to_pages_tall)计算的比例。|


### 方法
|方法|描述|
| :- | :- |
| [to_image](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_image/#int-str) |将特定页面渲染到文件中。|
| [to_image](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) |将特定页面渲染到流。|
| [to_tiff](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) |将整个工作表渲染为 Tiff 图像以进行流式传输。|
| [to_tiff](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_tiff/#str) |将整个工作表作为 Tiff 图像渲染到文件中。|
| [to_printer](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#str) |将工作表渲染到打印机|
| [to_printer](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#str-str) |将工作表渲染到打印机|
| [to_printer](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) |将工作表渲染到打印机|
| [to_printer](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) |将工作表渲染到打印机|
| [to_printer](/cells/python-net/zh/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) |将工作表渲染到打印机|
| [get_page_size_inch](/cells/python-net/zh/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) |获取输出图像的页面大小（以英寸为单位）。|
| [custom_print](/cells/python-net/zh/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) |使用此功能打印每一页时，客户端可以控制打印机的页面设置。|
| [dispose](/cells/python-net/zh/aspose.cells.rendering/sheetrender/dispose/#) |释放创建并用于渲染的资源。|



### 也可以看看
* 模块[`aspose.cells.rendering`](..)
