﻿---
title: SheetRender class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 130
url: /aspose.cells.rendering/sheetrender/
is_root: false
---

## SheetRender class

Represents a worksheet render which can render worksheet to various images such as (BMP, PNG, JPEG, TIFF..)
The constructor of this class , must be used after modification of pagesetup, cell style.



The SheetRender type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | the construct of SheetRender, need worksheet and ImageOrPrintOptions as params |


### Properties
| Property | Description |
| :- | :- |
| [page_count](/cells/python-net/aspose.cells.rendering/sheetrender/page_count) | Gets the total page count of current worksheet. |
| [page_scale](/cells/python-net/aspose.cells.rendering/sheetrender/page_scale) | Gets calculated page scale of the sheet.<br/>Returns the set scale if [`PageSetup.zoom`](/cells/python-net/aspose.cells/pagesetup#zoom) is set. Otherwise, returns the calculated scale according to [`PageSetup.fit_to_pages_wide`](/cells/python-net/aspose.cells/pagesetup#fit_to_pages_wide) and [`PageSetup.fit_to_pages_tall`](/cells/python-net/aspose.cells/pagesetup#fit_to_pages_tall). |


### Methods
| Method | Description |
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_image/#int-str) | Render certain page to a file. |
| [`to_image(self, page_index, stream)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Render certain page to a stream. |
| [`to_tiff(self, stream)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Render whole worksheet as Tiff Image to stream. |
| [`to_tiff(self, filename)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_tiff/#str) | Render whole worksheet as Tiff Image to a file. |
| [`to_printer(self, printer_name)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_printer/#str) | Render worksheet to Printer |
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Render worksheet to Printer |
| [`to_printer(self, printer_settings)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Render worksheet to Printer |
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Render worksheet to Printer |
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Render worksheet to Printer |
| [`get_page_size_inch(self, page_index)`](/cells/python-net/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Get page size in inch of output image. |
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Client can control page setting of printer when print each page using this function. |
| [`dispose(self)`](/cells/python-net/aspose.cells.rendering/sheetrender/dispose/#) | Releases resources created and used for rendering. |



### See Also
* module [`aspose.cells.rendering`](..)
