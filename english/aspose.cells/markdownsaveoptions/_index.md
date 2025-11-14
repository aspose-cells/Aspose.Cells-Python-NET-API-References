---
title: MarkdownSaveOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1060
url: /aspose.cells/markdownsaveoptions/
is_root: false
---

## MarkdownSaveOptions class

Represents the save options for markdown.



**Inheritance:** [`MarkdownSaveOptions`](/cells/python-net/aspose.cells/markdownsaveoptions) → 
[`SaveOptions`](/cells/python-net/aspose.cells/saveoptions)



The MarkdownSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells/markdownsaveoptions/__init__/#) | Creates options for saving markdown document |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/cells/python-net/aspose.cells/markdownsaveoptions/save_format) | Gets the save file format. |
| [clear_data](/cells/python-net/aspose.cells/markdownsaveoptions/clear_data) | Make the workbook empty after saving the file. |
| [cached_file_folder](/cells/python-net/aspose.cells/markdownsaveoptions/cached_file_folder) | The folder for temporary files that may be used as data cache. |
| [validate_merged_areas](/cells/python-net/aspose.cells/markdownsaveoptions/validate_merged_areas) | Indicates whether validate merged cells before saving the file. |
| [merge_areas](/cells/python-net/aspose.cells/markdownsaveoptions/merge_areas) | Indicates whether merge the areas of conditional formatting and validation before saving the file. |
| [create_directory](/cells/python-net/aspose.cells/markdownsaveoptions/create_directory) | If true and the directory does not exist, the directory will be automatically created before saving the file. |
| [sort_names](/cells/python-net/aspose.cells/markdownsaveoptions/sort_names) | Indicates whether sorting defined names before saving file. |
| [sort_external_names](/cells/python-net/aspose.cells/markdownsaveoptions/sort_external_names) | Indicates whether sorting external defined names before saving file. |
| [refresh_chart_cache](/cells/python-net/aspose.cells/markdownsaveoptions/refresh_chart_cache) | Indicates whether refreshing chart cache data |
| [warning_callback](/cells/python-net/aspose.cells/markdownsaveoptions/warning_callback) | Gets or sets warning callback. |
| [check_excel_restriction](/cells/python-net/aspose.cells/markdownsaveoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects.<br/>For example, excel does not allow inputting string value longer than 32K.<br/>When you input a value longer than 32K, it will be truncated. |
| [update_smart_art](/cells/python-net/aspose.cells/markdownsaveoptions/update_smart_art) | Indicates whether updating smart art setting.<br/>The default value is false. |
| [encrypt_document_properties](/cells/python-net/aspose.cells/markdownsaveoptions/encrypt_document_properties) | Indicates whether encrypt document properties when saving as .xls file.<br/>The default value is true. |
| [encoding](/cells/python-net/aspose.cells/markdownsaveoptions/encoding) | Gets and sets the default encoding. |
| [format_strategy](/cells/python-net/aspose.cells/markdownsaveoptions/format_strategy) | Gets and sets the format strategy when exporting the cell value as string. |
| [light_cells_data_provider](/cells/python-net/aspose.cells/markdownsaveoptions/light_cells_data_provider) | The Data provider to provide cells data for saving workbook in light mode. |
| [line_separator](/cells/python-net/aspose.cells/markdownsaveoptions/line_separator) | Gets and sets the line separator. |
| [table_header_type](/cells/python-net/aspose.cells/markdownsaveoptions/table_header_type) | Gets and sets how set the header of the table. |
| [sheet_set](/cells/python-net/aspose.cells/markdownsaveoptions/sheet_set) | Gets or sets the sheets to render. Default is all visible sheets in the workbook: [`SheetSet.active`](/cells/python-net/aspose.cells.rendering/sheetset#active). |
| [image_options](/cells/python-net/aspose.cells/markdownsaveoptions/image_options) | Get the ImageOrPrintOptions object before exporting |
| [export_images_as_base64](/cells/python-net/aspose.cells/markdownsaveoptions/export_images_as_base64) | Specifies whether images are saved in Base64 format to Markdown.<br/>The default value is true. |
| [stream_provider](/cells/python-net/aspose.cells/markdownsaveoptions/stream_provider) | Gets or sets the IStreamProvider for exporting objects.<br/>If `null`, the exported objects will be saved to the same directory as the output file. |
| [calculate_formula](/cells/python-net/aspose.cells/markdownsaveoptions/calculate_formula) | Indicates whether to calculate formulas before saving markdown file. |
| [export_hyperlink_as_reference](/cells/python-net/aspose.cells/markdownsaveoptions/export_hyperlink_as_reference) | Indicates whether to export hyperlink using reference definitions instead of inline format.<br/>The default value is false. |
| [align_column_padding](/cells/python-net/aspose.cells/markdownsaveoptions/align_column_padding) | Indicates whether column alignment is enabled for generated Markdown tables.<br/>When enabled, columns are aligned by padding cell content with the specified character(typically ' ' for spaces).<br/>Set to '\0' to disable column alignment (default). |
| [split_tables_by_blank_row](/cells/python-net/aspose.cells/markdownsaveoptions/split_tables_by_blank_row) | Indicates whether blank rows in the worksheet should be treated as table separators when exporting to Markdown.<br/>The default value is false. |
| [office_math_output_type](/cells/python-net/aspose.cells/markdownsaveoptions/office_math_output_type) | Indicates how export OfficeMath objects to Markdown, Default value is Image. |



### See Also
* module [`aspose.cells`](..)
* class [`MarkdownSaveOptions`](/cells/python-net/aspose.cells/markdownsaveoptions)
* class [`SaveOptions`](/cells/python-net/aspose.cells/saveoptions)
