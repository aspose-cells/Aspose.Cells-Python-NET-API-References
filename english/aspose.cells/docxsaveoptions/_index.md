﻿---
title: DocxSaveOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 510
url: /aspose.cells/docxsaveoptions/
is_root: false
---

## DocxSaveOptions class

Represents options of saving .docx file.



**Inheritance:** [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/aspose.cells/saveoptions)



The DocxSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells/docxsaveoptions/__init__/#) | Represents options of saving .docx file. |
| [__init__](/cells/python-net/aspose.cells/docxsaveoptions/__init__/#bool) | Represents options of saving .docx file. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/cells/python-net/aspose.cells/docxsaveoptions/save_format) | Gets the save file format. |
| [clear_data](/cells/python-net/aspose.cells/docxsaveoptions/clear_data) | Make the workbook empty after saving the file. |
| [cached_file_folder](/cells/python-net/aspose.cells/docxsaveoptions/cached_file_folder) | The cached file folder is used to store some large data. |
| [validate_merged_areas](/cells/python-net/aspose.cells/docxsaveoptions/validate_merged_areas) | Indicates whether validate merged cells before saving the file. |
| [merge_areas](/cells/python-net/aspose.cells/docxsaveoptions/merge_areas) | Indicates whether merge the areas of conditional formatting and validation before saving the file. |
| [create_directory](/cells/python-net/aspose.cells/docxsaveoptions/create_directory) | If true and the directory does not exist, the directory will be automatically created before saving the file. |
| [sort_names](/cells/python-net/aspose.cells/docxsaveoptions/sort_names) | Indicates whether sorting defined names before saving file. |
| [sort_external_names](/cells/python-net/aspose.cells/docxsaveoptions/sort_external_names) | Indicates whether sorting external defined names before saving file. |
| [refresh_chart_cache](/cells/python-net/aspose.cells/docxsaveoptions/refresh_chart_cache) | Indicates whether refreshing chart cache data |
| [warning_callback](/cells/python-net/aspose.cells/docxsaveoptions/warning_callback) | Gets or sets warning callback. |
| [update_smart_art](/cells/python-net/aspose.cells/docxsaveoptions/update_smart_art) | Indicates whether updating smart art setting.<br/>The default value is false. |
| [default_font](/cells/python-net/aspose.cells/docxsaveoptions/default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters.<br/>If this property is not set, Aspose.Cells will use system default font to show these unicode characters. |
| [check_workbook_default_font](/cells/python-net/aspose.cells/docxsaveoptions/check_workbook_default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set this to true to try to use workbook's default font to show these characters first. |
| [check_font_compatibility](/cells/python-net/aspose.cells/docxsaveoptions/check_font_compatibility) | Indicates whether to check font compatibility for every character in text. |
| [is_font_substitution_char_granularity](/cells/python-net/aspose.cells/docxsaveoptions/is_font_substitution_char_granularity) | Indicates whether to only substitute the font of character when the cell font is not compatibility for it. |
| [one_page_per_sheet](/cells/python-net/aspose.cells/docxsaveoptions/one_page_per_sheet) | If OnePagePerSheet is true , all content of one sheet will output to only one page in result. <br/>The paper size of pagesetup will be invalid, and the other settings of pagesetup <br/>will still take effect. |
| [all_columns_in_one_page_per_sheet](/cells/python-net/aspose.cells/docxsaveoptions/all_columns_in_one_page_per_sheet) | If AllColumnsInOnePagePerSheet is true , all column content of one sheet will output to only one page in result. <br/>The width of paper size of pagesetup will be ignored, and the other settings of pagesetup <br/>will still take effect. |
| [ignore_error](/cells/python-net/aspose.cells/docxsaveoptions/ignore_error) | Indicates if you need to hide the error while rendering.<br/>The error can be error in shape, image, chart rendering, etc. |
| [output_blank_page_when_nothing_to_print](/cells/python-net/aspose.cells/docxsaveoptions/output_blank_page_when_nothing_to_print) | Indicates whether to output a blank page when there is nothing to print. |
| [page_index](/cells/python-net/aspose.cells/docxsaveoptions/page_index) | Gets or sets the 0-based index of the first page to save. |
| [page_count](/cells/python-net/aspose.cells/docxsaveoptions/page_count) | Gets or sets the number of pages to save. |
| [printing_page_type](/cells/python-net/aspose.cells/docxsaveoptions/printing_page_type) | Indicates which pages will not be printed. |
| [gridline_type](/cells/python-net/aspose.cells/docxsaveoptions/gridline_type) | Gets or sets gridline type. |
| [text_cross_type](/cells/python-net/aspose.cells/docxsaveoptions/text_cross_type) | Gets or sets displaying text type when the text width is larger than cell width. |
| [default_edit_language](/cells/python-net/aspose.cells/docxsaveoptions/default_edit_language) | Gets or sets default edit language. |
| [sheet_set](/cells/python-net/aspose.cells/docxsaveoptions/sheet_set) | Gets or sets the sheets to render. Default is all visible sheets in the workbook: [`SheetSet.visible`](/cells/python-net/aspose.cells.rendering/sheetset#visible). |
| [draw_object_event_handler](/cells/python-net/aspose.cells/docxsaveoptions/draw_object_event_handler) | Implements this interface to get DrawObject and Bound when rendering. |
| [page_saving_callback](/cells/python-net/aspose.cells/docxsaveoptions/page_saving_callback) | Control/Indicate progress of page saving process. |
| [emf_render_setting](/cells/python-net/aspose.cells/docxsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |



### See Also
* module [`aspose.cells`](..)
* class [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions)
* class [`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions)
* class [`SaveOptions`](/cells/python-net/aspose.cells/saveoptions)
