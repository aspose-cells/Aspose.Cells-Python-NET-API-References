---
title: SvgImageOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 150
url: /aspose.cells.rendering/svgimageoptions/
is_root: false
---

## SvgImageOptions class

Options for generating Svg image.



**Inheritance:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/aspose.cells.rendering/imageorprintoptions)



The SvgImageOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells.rendering/svgimageoptions/__init__/#) | Ctor. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/cells/python-net/aspose.cells.rendering/svgimageoptions/save_format) | Gets or sets the output file format type<br/>Support Tiff/XPS |
| [print_with_status_dialog](/cells/python-net/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | If PrintWithStatusDialog = true , there will be a dialog that shows current print status.<br/>else no such dialog will show. |
| [horizontal_resolution](/cells/python-net/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | Gets or sets the horizontal resolution for generated images, in dots per inch. |
| [vertical_resolution](/cells/python-net/aspose.cells.rendering/svgimageoptions/vertical_resolution) | Gets or sets the vertical resolution for generated images, in dots per inch. |
| [tiff_compression](/cells/python-net/aspose.cells.rendering/svgimageoptions/tiff_compression) | Gets or sets the type of compression to apply only when saving pages to the `Tiff` format. |
| [tiff_color_depth](/cells/python-net/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | Gets or sets bit depth to apply only when saving pages to the `Tiff` format. |
| [tiff_binarization_method](/cells/python-net/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | Gets or sets method used while converting images to 1 bpp format <br/>when [`ImageOrPrintOptions.image_type`](/cells/python-net/aspose.cells.rendering/imageorprintoptions#image_type) is Tiff and [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/aspose.cells.rendering/imageorprintoptions#tiff_compression) is equal to Ccitt3 or Ccitt4. |
| [printing_page](/cells/python-net/aspose.cells.rendering/svgimageoptions/printing_page) | Indicates which pages will not be printed. |
| [quality](/cells/python-net/aspose.cells.rendering/svgimageoptions/quality) | Gets or sets a value determining the quality of the generated  images<br/>to apply only when saving pages to the `Jpeg` format. The default value is 100 |
| [image_type](/cells/python-net/aspose.cells.rendering/svgimageoptions/image_type) | Gets or sets the format of the generated images.<br/>default value: PNG. |
| [is_cell_auto_fit](/cells/python-net/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | Indicates whether the width and height of the cells is automatically fitted by cell value. <br/>The default value is false. |
| [one_page_per_sheet](/cells/python-net/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | If OnePagePerSheet is true , all content of one sheet will output to only one page in result. <br/>The paper size of pagesetup will be invalid, and the other settings of pagesetup <br/>will still take effect. |
| [all_columns_in_one_page_per_sheet](/cells/python-net/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | If AllColumnsInOnePagePerSheet is true , all column content of one sheet will output to only one page in result. <br/>The width of paper size of pagesetup will be invalid, and the other settings of pagesetup <br/>will still take effect. |
| [draw_object_event_handler](/cells/python-net/aspose.cells.rendering/svgimageoptions/draw_object_event_handler) | Implements this interface to get DrawObject and Bound when rendering. |
| [chart_image_type](/cells/python-net/aspose.cells.rendering/svgimageoptions/chart_image_type) | Indicate the chart imagetype when converting.<br/>default value: PNG. |
| [embeded_image_name_in_svg](/cells/python-net/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | Indicate the filename of embedded image in svg. <br/>This should be full path with directory like "c:\\xpsEmbedded" |
| [svg_fit_to_view_port](/cells/python-net/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | if this property is true, the generated svg will fit to view port. |
| [svg_css_prefix](/cells/python-net/aspose.cells.rendering/svgimageoptions/svg_css_prefix) | Gets and sets the prefix of the css name in svg,the default value is empty string. |
| [only_area](/cells/python-net/aspose.cells.rendering/svgimageoptions/only_area) | If this property is true , one Area will be output, and no scale will take effect. |
| [text_rendering_hint](/cells/python-net/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | Specifies the quality of text rendering.<br/>The default value is TextRenderingHint.SystemDefault |
| [smoothing_mode](/cells/python-net/aspose.cells.rendering/svgimageoptions/smoothing_mode) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas.<br/>The default value is SmoothingMode.None |
| [transparent](/cells/python-net/aspose.cells.rendering/svgimageoptions/transparent) | Indicates if the background of generated image should be transparent. |
| [pixel_format](/cells/python-net/aspose.cells.rendering/svgimageoptions/pixel_format) | Gets or sets the pixel format for the generated images. |
| [warning_callback](/cells/python-net/aspose.cells.rendering/svgimageoptions/warning_callback) | Gets or sets warning callback. |
| [page_saving_callback](/cells/python-net/aspose.cells.rendering/svgimageoptions/page_saving_callback) | Control/Indicate progress of page saving process. |
| [is_font_substitution_char_granularity](/cells/python-net/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | Indicates whether to only substitute the font of character when the cell font is not compatibility for it. |
| [page_index](/cells/python-net/aspose.cells.rendering/svgimageoptions/page_index) | Gets or sets the 0-based index of the first page to save. |
| [page_count](/cells/python-net/aspose.cells.rendering/svgimageoptions/page_count) | Gets or sets the number of pages to save. |
| [is_optimized](/cells/python-net/aspose.cells.rendering/svgimageoptions/is_optimized) | Indicates whether to optimize the output elements. |
| [default_font](/cells/python-net/aspose.cells.rendering/svgimageoptions/default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters.<br/>If this property is not set, Aspose.Cells will use system default font to show these unicode characters. |
| [check_workbook_default_font](/cells/python-net/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | When characters in the Excel are Unicode and not be set with correct font in cell style,<br/>They may appear as block in pdf,image.<br/>Set this to true to try to use workbook's default font to show these characters first. |
| [output_blank_page_when_nothing_to_print](/cells/python-net/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | Indicates whether to output a blank page when there is nothing to print. |
| [gridline_type](/cells/python-net/aspose.cells.rendering/svgimageoptions/gridline_type) | Gets or sets gridline type. |
| [gridline_color](/cells/python-net/aspose.cells.rendering/svgimageoptions/gridline_color) | Gets or sets gridline colr. |
| [text_cross_type](/cells/python-net/aspose.cells.rendering/svgimageoptions/text_cross_type) | Gets or sets displaying text type when the text width is larger than cell width. |
| [emf_type](/cells/python-net/aspose.cells.rendering/svgimageoptions/emf_type) | Gets or sets an EmfType that specifies the format of the Metafile..<br/>The default value is EmfPlusDual. |
| [default_edit_language](/cells/python-net/aspose.cells.rendering/svgimageoptions/default_edit_language) | Gets or sets default edit language. |
| [sheet_set](/cells/python-net/aspose.cells.rendering/svgimageoptions/sheet_set) | Gets or sets the sheets to render. Default is all visible sheets in the workbook: [`SheetSet.visible`](/cells/python-net/aspose.cells.rendering/sheetset#visible). |
| [emf_render_setting](/cells/python-net/aspose.cells.rendering/svgimageoptions/emf_render_setting) | Setting for rendering Emf metafiles in source file. |
| [custom_render_settings](/cells/python-net/aspose.cells.rendering/svgimageoptions/custom_render_settings) | Gets or sets custom settings during rendering. |
| [fit_to_view_port](/cells/python-net/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | if this property is true, the generated svg will fit to view port. |
| [css_prefix](/cells/python-net/aspose.cells.rendering/svgimageoptions/css_prefix) | Gets and sets the prefix of the css name in svg,the default value is empty string. |
| [embedded_font_type](/cells/python-net/aspose.cells.rendering/svgimageoptions/embedded_font_type) | Gets or sets the type of font that embedded in Svg. |


### Methods
| Method | Description |
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | Sets desired width and height of image. |
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | Sets desired width and height of image. |



### See Also
* module [`aspose.cells.rendering`](..)
* class [`ImageOrPrintOptions`](/cells/python-net/aspose.cells.rendering/imageorprintoptions)
* class [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions)
