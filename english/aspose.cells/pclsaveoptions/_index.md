---
title: PclSaveOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1260
url: /aspose.cells/pclsaveoptions/
is_root: false
---

## PclSaveOptions class

Represents the options for saving Pcl file.



**Inheritance:** [`PclSaveOptions`](/cells/python-net/aspose.cells/pclsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/aspose.cells/saveoptions)



The PclSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells/pclsaveoptions/__init__/#) | Creates the options for saving pdf file. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/cells/python-net/aspose.cells/pclsaveoptions/save_format) | Gets the save file format. |
| [clear_data](/cells/python-net/aspose.cells/pclsaveoptions/clear_data) | Make the workbook empty after saving the file. |
| [cached_file_folder](/cells/python-net/aspose.cells/pclsaveoptions/cached_file_folder) | The cached file folder is used to store some large data. |
| [validate_merged_areas](/cells/python-net/aspose.cells/pclsaveoptions/validate_merged_areas) | Indicates whether validate merged cells before saving the file. |
| [merge_areas](/cells/python-net/aspose.cells/pclsaveoptions/merge_areas) | Indicates whether merge the areas of conditional formatting and validation before saving the file. |
| [create_directory](/cells/python-net/aspose.cells/pclsaveoptions/create_directory) | If true and the directory does not exist, the directory will be automatically created before saving the file. |
| [sort_names](/cells/python-net/aspose.cells/pclsaveoptions/sort_names) | Indicates whether sorting defined names before saving file. |
| [sort_external_names](/cells/python-net/aspose.cells/pclsaveoptions/sort_external_names) | Indicates whether sorting external defined names before saving file. |
| [refresh_chart_cache](/cells/python-net/aspose.cells/pclsaveoptions/refresh_chart_cache) | Indicates whether refreshing chart cache data |
| [warning_callback](/cells/python-net/aspose.cells/pclsaveoptions/warning_callback) | Gets or sets warning callback. |
| [check_excel_restriction](/cells/python-net/aspose.cells/pclsaveoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects.<br/>For example, excel does not allow inputting string value longer than 32K.<br/>When you input a value longer than 32K, it will be truncated. |
| [update_smart_art](/cells/python-net/aspose.cells/pclsaveoptions/update_smart_art) | Indicates whether updating smart art setting.<br/>The default value is false. |
| [encrypt_document_properties](/cells/python-net/aspose.cells/pclsaveoptions/encrypt_document_properties) | Indicates whether encrypt document properties when saving as .xls file.<br/>The default value is true. |
| [default_font](/cells/python-net/aspose.cells/pclsaveoptions/default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters.<br/>If this property is not set, Aspose.Cells will use system default font to show these unicode characters. |
| [check_workbook_default_font](/cells/python-net/aspose.cells/pclsaveoptions/check_workbook_default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set this to true to try to use workbook's default font to show these characters first. |
| [check_font_compatibility](/cells/python-net/aspose.cells/pclsaveoptions/check_font_compatibility) | Indicates whether to check font compatibility for every character in text. |
| [is_font_substitution_char_granularity](/cells/python-net/aspose.cells/pclsaveoptions/is_font_substitution_char_granularity) | Indicates whether to only substitute the font of character when the cell font is not compatibility for it. |
| [one_page_per_sheet](/cells/python-net/aspose.cells/pclsaveoptions/one_page_per_sheet) | If OnePagePerSheet is true , all content of one sheet will output to only one page in result. <br/>The paper size of pagesetup will be invalid, and the other settings of pagesetup <br/>will still take effect. |
| [all_columns_in_one_page_per_sheet](/cells/python-net/aspose.cells/pclsaveoptions/all_columns_in_one_page_per_sheet) | If AllColumnsInOnePagePerSheet is true , all column content of one sheet will output to only one page in result. <br/>The width of paper size of pagesetup will be ignored, and the other settings of pagesetup <br/>will still take effect. |
| [ignore_error](/cells/python-net/aspose.cells/pclsaveoptions/ignore_error) | Indicates if you need to hide the error while rendering.<br/>The error can be error in shape, image, chart rendering, etc. |
| [output_blank_page_when_nothing_to_print](/cells/python-net/aspose.cells/pclsaveoptions/output_blank_page_when_nothing_to_print) | Indicates whether to output a blank page when there is nothing to print. |
| [page_index](/cells/python-net/aspose.cells/pclsaveoptions/page_index) | Gets or sets the 0-based index of the first page to save. |
| [page_count](/cells/python-net/aspose.cells/pclsaveoptions/page_count) | Gets or sets the number of pages to save. |
| [printing_page_type](/cells/python-net/aspose.cells/pclsaveoptions/printing_page_type) | Indicates which pages will not be printed. |
| [gridline_type](/cells/python-net/aspose.cells/pclsaveoptions/gridline_type) | Gets or sets gridline type. |
| [text_cross_type](/cells/python-net/aspose.cells/pclsaveoptions/text_cross_type) | Gets or sets displaying text type when the text width is larger than cell width. |
| [default_edit_language](/cells/python-net/aspose.cells/pclsaveoptions/default_edit_language) | Gets or sets default edit language. |
| [sheet_set](/cells/python-net/aspose.cells/pclsaveoptions/sheet_set) | Gets or sets the sheets to render. Default is all visible sheets in the workbook: [`SheetSet.visible`](/cells/python-net/aspose.cells.rendering/sheetset#visible). |
| [draw_object_event_handler](/cells/python-net/aspose.cells/pclsaveoptions/draw_object_event_handler) | Implements this interface to get DrawObject and Bound when rendering. |
| [page_saving_callback](/cells/python-net/aspose.cells/pclsaveoptions/page_saving_callback) | Control/Indicate progress of page saving process. |
| [emf_render_setting](/cells/python-net/aspose.cells/pclsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |


### Methods
| Method | Description |
| :- | :- |
| [add_printer_font](/cells/python-net/aspose.cells/pclsaveoptions/add_printer_font/#str-str) | Adds information about font that is already added to the printer by manufacturer. |



### See Also
* module [`aspose.cells`](..)
* class [`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions)
* class [`PclSaveOptions`](/cells/python-net/aspose.cells/pclsaveoptions)
* class [`SaveOptions`](/cells/python-net/aspose.cells/saveoptions)
