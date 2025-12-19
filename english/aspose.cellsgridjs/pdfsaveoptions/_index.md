---
title: PdfSaveOptions class
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 180
url: /aspose.cellsgridjs/pdfsaveoptions/
is_root: false
---

## PdfSaveOptions class

Represents the options for saving pdf file.



The PdfSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/__init__/#) | Creates the options for saving pdf file. |


### Properties
| Property | Description |
| :- | :- |
| [font_encoding](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/font_encoding) | Gets or sets embedded font encoding in pdf. |
| [display_doc_title](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/display_doc_title) | Indicates whether the window's title bar should display the document title. |
| [export_document_structure](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/export_document_structure) | Indicates whether to export document structure. |
| [custom_properties_export](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/custom_properties_export) | Gets or sets a value determining the way of custom document properties are exported to PDF file. Default value is None. |
| [optimization_type](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/optimization_type) | Gets and sets pdf optimization type. |
| [producer](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/producer) | Gets and sets producer of generated pdf document. |
| [created_time](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/created_time) | Gets and sets the time of generating the pdf document. |
| [pdf_compression](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/pdf_compression) | Indicate the compression algorithm |
| [calculate_formula](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/calculate_formula) | Indicates whether to calculate formulas before saving pdf file. |
| [security_options](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/security_options) | Set this options, when security is need in xls2pdf result. |
| [compliance](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/compliance) | Gets or sets the PDF standards compliance level for output documents. |
| [embed_standard_windows_fonts](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/embed_standard_windows_fonts) | True to embed true type fonts. <br/>Affects only ASCII characters 32-127.<br/>Fonts for character codes greater than 127 are always embedded.<br/>Fonts are always embedded for PDF/A-1a, PDF/A-1b standard.<br/>Default is true. |
| [embed_attachments](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/embed_attachments) | Indicates whether to embed attachment for Ole objects in Excel. |
| [default_edit_language](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/default_edit_language) | Gets or sets default edit language. |
| [text_cross_type](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/text_cross_type) | Gets or sets displaying text type when the text width is larger than cell width. |
| [gridline_color](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/gridline_color) | Gets or sets gridline colr. |
| [gridline_type](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/gridline_type) | Gets or sets gridline type. |
| [printing_page_type](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/printing_page_type) | Indicates which pages will not be printed. |
| [emf_render_setting](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |
| [page_count](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/page_count) | Gets or sets the number of pages to save. |
| [page_index](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/page_index) | Gets or sets the 0-based index of the first page to save. |
| [ignore_error](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/ignore_error) | Indicates if you need to hide the error while rendering.<br/>The error can be error in shape, image, chart rendering, etc. |
| [output_blank_page_when_nothing_to_print](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/output_blank_page_when_nothing_to_print) | Indicates whether to output a blank page when there is nothing to print. |
| [default_font](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters.<br/>If this property is not set, Aspose.Cells will use system default font to show these unicode characters. |
| [check_workbook_default_font](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/check_workbook_default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set this to true to try to use workbook's default font to show these characters first. |
| [check_font_compatibility](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/check_font_compatibility) | Indicates whether to check font compatibility for every character in text. |
| [is_font_substitution_char_granularity](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/is_font_substitution_char_granularity) | Indicates whether to only substitute the font of character when the cell font is not compatibility for it. |
| [one_page_per_sheet](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/one_page_per_sheet) | If OnePagePerSheet is true , all content of one sheet will output to only one page in result. <br/>The paper size of pagesetup will be invalid, and the other settings of pagesetup <br/>will still take effect. |
| [all_columns_in_one_page_per_sheet](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/all_columns_in_one_page_per_sheet) | If AllColumnsInOnePagePerSheet is true , all column content of one sheet will output to only one page in result. <br/>The width of paper size of pagesetup will be ignored, and the other settings of pagesetup <br/>will still take effect. |


### Methods
| Method | Description |
| :- | :- |
| [`set_sheet_set(self, sheet_indexes)`](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/set_sheet_set/#list) | Creates a sheet set based on exact sheet indexes. |
| [`set_sheet_set(self, sheet_names)`](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/set_sheet_set/#list) | Creates a sheet set based on exact sheet names. |
| [`set_image_resample(self, desired_ppi, jpeg_quality)`](/cells/python-net/aspose.cellsgridjs/pdfsaveoptions/set_image_resample/#int-int) | Sets desired PPI(pixels per inch) of resample images and jpeg quality.  <br/>All images will be converted to JPEG with the specified quality setting, <br/>and images that are greater than the specified PPI (pixels per inch) will be resampled. |



### See Also
* module [`aspose.cellsgridjs`](..)
