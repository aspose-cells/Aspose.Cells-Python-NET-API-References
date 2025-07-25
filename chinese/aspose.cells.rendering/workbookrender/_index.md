---
title: WorkbookRender类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells.rendering/workbookrender/
is_root: false
---
## WorkbookRender类
表示工作簿渲染。
该类的构造函数，在修改pagesetup、cell样式后必须使用。



WorkbookRender 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | WorkbookRender 的构造|


### 属性
|属性|描述|
| :- | :- |
| [page_count](/cells/python-net/zh/aspose.cells.rendering/workbookrender/page_count) |获取工作簿的总页数。|


### 方法
|方法|描述|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) |将整个工作簿作为 Tiff 图像呈现到流中。|
| [`to_image(self, filename)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_image/#str) |将整个工作簿作为 Tiff 图像呈现到文件中。|
| [`to_image(self, page_index, file_name)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_image/#int-str) |将特定页面渲染到文件。|
| [`to_image(self, page_index, stream)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) |将特定页面渲染到流中。|
| [`to_printer(self, printer_name)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_printer/#str) |将工作簿渲染到打印机|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_printer/#str-str) |将工作簿渲染到打印机|
| [`to_printer(self, printer_settings)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) |将工作簿渲染到打印机|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) |将工作簿渲染到打印机|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) |将工作簿渲染到打印机|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) |获取输出图像的页面尺寸（以英寸为单位）。|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) |客户端可以通过该功能控制打印机在打印每一页时的页面设置。|
| [`dispose(self)`](/cells/python-net/zh/aspose.cells.rendering/workbookrender/dispose/#) |释放为渲染创建和使用的资源。|



### 注意事项



### 也可以看看
* 模块[`aspose.cells.rendering`](..)
