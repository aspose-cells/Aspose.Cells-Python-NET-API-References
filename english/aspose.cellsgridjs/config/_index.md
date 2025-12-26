---
title: Config class
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cellsgridjs/config/
is_root: false
---

## Config class

Represents all the static settings for GridJs



The Config type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cellsgridjs/config/__init__/#) | Constructs a new instance of Config |


### Properties
| Property | Description |
| :- | :- |
| [save_html_as_zip](/cells/python-net/aspose.cellsgridjs/config/save_html_as_zip) | Gets/Sets  whether to save html file as zip archive,the default is false. |
| [skip_invisible_shapes](/cells/python-net/aspose.cellsgridjs/config/skip_invisible_shapes) | Gets/Sets  whether to skip shapes that are invisble to UI ,the default value is true. |
| [lazy_loading](/cells/python-net/aspose.cellsgridjs/config/lazy_loading) | Gets/Sets  whether to load active worksheet only,the default is false. |
| [same_image_detecting](/cells/python-net/aspose.cellsgridjs/config/same_image_detecting) | Gets/Sets  whether to check if images have same source,the default is true<br/>the default value is true. |
| [auto_optimize_for_large_cells](/cells/python-net/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Gets/Sets  whether to automatically optimize the load performance for worksheet with large cells.<br/>it will ignore some style /borders to reduce the load  time.<br/>the default value is true. |
| [islimit_shape_or_image](/cells/python-net/aspose.cellsgridjs/config/islimit_shape_or_image) | Gets/Sets  whether to limit the total display shape/image count in one worksheet ,if set to true,<br/>GridJs will limit the total count of the display shapes or images in one worksheet  to MaxShapeOrImageCount<br/>the default value is true. |
| [max_shape_or_image_count](/cells/python-net/aspose.cellsgridjs/config/max_shape_or_image_count) | Gets/Sets the total count of the display shapes or images in the active sheet,it takes effect  when IslimitShapeOrImage=true.<br/>the default value is 100. |
| [max_total_shape_or_image_count](/cells/python-net/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Gets/Sets the total count of the display shapes or images  in the workbook,it takes effect  when IslimitShapeOrImage=true.<br/>the default value is 300. |
| [max_shape_or_image_width_or_height](/cells/python-net/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Gets/Sets the  max width or height for a shape or an image ,GridJs will ignore the shape or image with the width or height larger than this, it takes effect when IslimitShapeOrImage=true.<br/>the default value is 10000. |
| [max_pdf_save_seconds](/cells/python-net/aspose.cellsgridjs/config/max_pdf_save_seconds) | Gets/Sets the max timed out seconds when save to PDF.<br/>the default value is 10. |
| [ignore_empty_content](/cells/python-net/aspose.cellsgridjs/config/ignore_empty_content) | Gets/Sets whether to show  the max range which includes data ,style, merged cells and shapes.<br/>if the last row or column contains cells with  no value and formula but has custom style <br/>then we will not show this row/column when this vlaue is true。<br/>the default value is true . |
| [use_print_area](/cells/python-net/aspose.cellsgridjs/config/use_print_area) | Gets/Sets whether to use PageSetup.PrintArea for the UI display range when the worksheet has PageSetup setting for PrintArea.<br/>the default value is false . |
| [is_collaborative](/cells/python-net/aspose.cellsgridjs/config/is_collaborative) | Gets/Sets  whether to support collabrative editing,the default is false. |
| [custom_pdf_save_options](/cells/python-net/aspose.cellsgridjs/config/custom_pdf_save_options) | Gets/Sets the custom PdfSaveOptions for PDF export. If set, this will be used instead of the default options.<br/>the default value is null. |
| [load_time_out](/cells/python-net/aspose.cellsgridjs/config/load_time_out) | Gets/Sets a timeout interrupt in milliseconds in loading file, when the cost time period of loading file  is longer than the expectation   ，it will raise exception.<br/>the default value is -1,which means no timeout interrupt is set . |
| [show_chart_sheet](/cells/python-net/aspose.cellsgridjs/config/show_chart_sheet) | Gets/Sets whether to show chart worksheet.<br/>the default value is false . |
| [empty_sheet_max_row](/cells/python-net/aspose.cellsgridjs/config/empty_sheet_max_row) | Gets/Sets default max row for an empty worksheet.<br/>the default value is 12. |
| [empty_sheet_max_col](/cells/python-net/aspose.cellsgridjs/config/empty_sheet_max_col) | Gets/Sets default max column for an empty worksheet.<br/>the default value is 15. |
| [picture_cache_directory](/cells/python-net/aspose.cellsgridjs/config/picture_cache_directory) | Gets/Sets the cache directory for pictures.(this takes effect when GridJsWorkbook.CacheImp is null)<br/>the default path will be "_piccache" inside the FileCacheDirectory. |
| [file_cache_directory](/cells/python-net/aspose.cellsgridjs/config/file_cache_directory) | Gets/Sets the cache directory for storing spreadsheet file.<br/>We need to set it to a specific path before we use GridJs. |
| [base_route_name](/cells/python-net/aspose.cellsgridjs/config/base_route_name) | Gets/Sets the base route name for GridJs controller URL. the default is "/GridJs2". |
| [message_topic](/cells/python-net/aspose.cellsgridjs/config/message_topic) | Gets/Sets the websocket destinations prefixed with "/topic". the default is "/topic/opr".used in collaborative mode only. |
| [auto_fit_rows_height_on_load](/cells/python-net/aspose.cellsgridjs/config/auto_fit_rows_height_on_load) | Indicates whether to autofit rows height  when loading the file,the default value is false. |


### Methods
| Method | Description |
| :- | :- |
| [`set_license(, license_name)`](/cells/python-net/aspose.cellsgridjs/config/set_license/#system.string) | Licenses the component. |
| [`set_license(, stream)`](/cells/python-net/aspose.cellsgridjs/config/set_license/#io.rawiobase) | Licenses the component. |
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/aspose.cellsgridjs/config/set_font_folder/#system.string-bool) | Sets the fonts folder |
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Sets the fonts folders |



### See Also
* module [`aspose.cellsgridjs`](..)
