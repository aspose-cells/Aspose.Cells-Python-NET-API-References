﻿---
title: Config class
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 10
url: /aspose.cellsgridjs/config/
is_root: false
---

## Config class

Represents all the settings for GridJs



The Config type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/gridjs/python-net/aspose.cellsgridjs/config/__init__/#) | Constructs a new instance of Config |


### Properties
| Property | Description |
| :- | :- |
| [save_html_as_zip](/gridjs/python-net/aspose.cellsgridjs/config/save_html_as_zip) | Sets/Gets  whether to save html file as zip archive,the default is false. |
| [same_image_detecting](/gridjs/python-net/aspose.cellsgridjs/config/same_image_detecting) | Sets/Gets  whether to check if picture has same source,the default is true
| [auto_optimize_for_large_cells](/gridjs/python-net/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Sets/Gets  whether to automatically optimize the load performance for worksheet with large cells
| [islimit_shape_or_image](/gridjs/python-net/aspose.cellsgridjs/config/islimit_shape_or_image) | Sets/Gets  whether to limit the total display shape/image count inside one worksheet ,if set to true,
| [max_shape_or_image_count](/gridjs/python-net/aspose.cellsgridjs/config/max_shape_or_image_count) | Sets/Gets the total display shape/image count inside the active sheet,it will take affec when IslimitShapes=true.
| [max_total_shape_or_image_count](/gridjs/python-net/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Sets/Gets the total display shape/image count inside the whole workbook,it will take affec when IslimitShapes=true.
| [max_shape_or_image_width_or_height](/gridjs/python-net/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Sets/Gets the  max width or height for a shape/image ,GridJs will ignore the shape/image with the width or height larger than this, it will take affec when IslimitShapes=true.
| [max_pdf_save_seconds](/gridjs/python-net/aspose.cellsgridjs/config/max_pdf_save_seconds) | Sets/Gets the max timed out seconds when save to pdf.
| [ignore_empty_content](/gridjs/python-net/aspose.cellsgridjs/config/ignore_empty_content) | Sets/Gets whether to show  the max range which includes data ,style, merged cells and shapes.
| [use_print_area](/gridjs/python-net/aspose.cellsgridjs/config/use_print_area) | Sets/Gets whether to use PageSetup.PrintArea for the UI display range when the worksheet has PageSetup setting for PrintArea.
| [load_time_out](/gridjs/python-net/aspose.cellsgridjs/config/load_time_out) | Sets/Gets a timeout interrupt in milliseconds in loading file, when the cost time period of loading file  is longer than the expectation   ，it will raise exception.
| [show_chart_sheet](/gridjs/python-net/aspose.cellsgridjs/config/show_chart_sheet) | Sets/Gets whether to show chart worksheet.
| [page_size](/gridjs/python-net/aspose.cellsgridjs/config/page_size) | Sets/Gets whether to do pagination
| [empty_sheet_max_row](/gridjs/python-net/aspose.cellsgridjs/config/empty_sheet_max_row) | Sets/Gets default max row for an empty worksheet.
| [empty_sheet_max_col](/gridjs/python-net/aspose.cellsgridjs/config/empty_sheet_max_col) | Sets/Gets default max column for an empty worksheet.
| [picture_cache_directory](/gridjs/python-net/aspose.cellsgridjs/config/picture_cache_directory) | Sets/Gets the cache directory for pictures.(this will take affect when GridJsWorkbook.CacheImp is null)
| [file_cache_directory](/gridjs/python-net/aspose.cellsgridjs/config/file_cache_directory) | Sets/Gets the cache directory for spreadsheet file.


### Methods
| Method | Description |
| :- | :- |
| [set_license](/gridjs/python-net/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/gridjs/python-net/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Licenses the component. |
| [set_font_folder](/gridjs/python-net/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Sets the fonts folder |
| [set_font_folders](/gridjs/python-net/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Sets the fonts folders |



### See Also
* module [`aspose.cellsgridjs`](..)