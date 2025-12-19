---
title: GridJsWorkbook class
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 110
url: /aspose.cellsgridjs/gridjsworkbook/
is_root: false
---

## GridJsWorkbook class

Represents the main entry class for GridJs



The GridJsWorkbook type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/__init__/#) | Constructs a new instance of GridJsWorkbook |


### Properties
| Property | Description |
| :- | :- |
| [settings](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/settings) | Represents the workbook settings. |
| [cache_imp](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/cache_imp) | Custom  implemention for cache storage,If you want to store cache in stream way ,you  need to set and implement it. |
| [calculate_engine](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/calculate_engine) | Custom  implemention for calculation engine ,If you want to do custom calculation, you  need to set and implement it. |
| [update_monitor](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/update_monitor) | Gets/Sets the update monitor to track update operation |
| [PICTURE_TYPE](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/picture_type) | const value for the type of the image |


### Methods
| Method | Description |
| :- | :- |
| [`import_excel_file(self, uid, file_name, password)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#system.string-system.string-system.string) | Imports the excel file from file path and open password. |
| [`import_excel_file(self, uid, file_name)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#system.string-system.string) | Imports the excel file from the file path. |
| [`import_excel_file(self, file_name)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#system.string) | Imports the excel file from the file path. |
| [`import_excel_file(self, uid, filestream, format, password)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#system.string-io.rawiobase-aspose.cellsgridjs.gridloadformat-system.string) | Imports the excel file from  file stream with load format and open password. |
| [`import_excel_file(self, uid, filestream, format)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#system.string-io.rawiobase-aspose.cellsgridjs.gridloadformat) | Imports the excel file from file stream. |
| [`import_excel_file(self, filestream, format, password)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#io.rawiobase-aspose.cellsgridjs.gridloadformat-system.string) | Imports the excel file from file stream with load format and open password. |
| [`import_excel_file(self, filestream, format)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#io.rawiobase-aspose.cellsgridjs.gridloadformat) | Imports the excel file from file stream with load format. |
| [`export_to_json(self, filename)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/export_to_json/#system.string) | Gets JSON  string from memory data,set the output filename in the JSON. |
| [`export_to_json(self)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/export_to_json/#) | Gets JSON string from memory data, the default filename in the JSON is: book1. |
| [`save_to_excel_file(self, stream)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_excel_file/#io.rawiobase) | Saves the memory data to the sream, baseed on the origin file format. |
| [`save_to_excel_file(self, path)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_excel_file/#system.string) | Saves the memory data to the file path,if the file has extension ,save format is baseed on the file extension . |
| [`save_to_pdf(self, path)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_pdf/#system.string) | Saves the memory data to the file path,the save format is pdf. |
| [`save_to_pdf(self, stream)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_pdf/#io.rawiobase) | Saves the memory data to the sream,the save format is pdf. |
| [`save_to_xlsx(self, path)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_xlsx/#system.string) | Saves the memory data to the file path,the save format is xlsx. |
| [`save_to_xlsx(self, stream)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_xlsx/#io.rawiobase) | Saves the memory data to the sream,the save format is xlsx. |
| [`save_to_html(self, path)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_html/#system.string) | Saves the memory data to the file path,the save format is html. |
| [`save_to_html(self, stream)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_html/#io.rawiobase) | Saves the memory data to the sream,the save format is html |
| [`json_to_stream_by_uid(self, stream, uid, filename)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/json_to_stream_by_uid/#io.rawiobase-system.string-system.string) | Retrieve the JSON string of the file from the cache using the specified unique id,set the output filename in the JSON,and write it to the stream. |
| [`json_to_stream(self, stream, filename)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/json_to_stream/#io.rawiobase-system.string) | Retrieve the JSON string from memory data,set the output filename in the JSON, and write it to the stream. |
| [`lazy_loading_stream(self, stream, uid, sheet_name)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/lazy_loading_stream/#io.rawiobase-system.string-system.string) | Retrieve the JSON string of the specified sheet in the file from the cache using the specified unique id, and write it to the stream. |
| [`get_json_str_by_uid(self, uid, filename)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/get_json_str_by_uid/#system.string-system.string) | Gets the JSON  string  of the file from the cache using the specified unique id,set the output filename in the JSON. |
| [`lazy_loading_json_str(self, uid, sheet_name)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/lazy_loading_json_str/#system.string-system.string) | Gets the JSON string of the specified sheet in the file from the cache using the specified unique id. |
| [`get_uid_for_file(, file_name)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/get_uid_for_file/#system.string) | Generates a new unique id for the file cache using the given file name. |
| [`import_excel_file_from_json(self, json)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/import_excel_file_from_json/#system.string) | Imports the excel file from JSON format string. |
| [`merge_excel_file_from_json(self, uid, json)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/merge_excel_file_from_json/#system.string-system.string) | Applies a batch update to the memory data. |
| [`save_to_cache_with_file_name(self, uid, filename, password)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/save_to_cache_with_file_name/#system.string-system.string-system.string) | Saves the memory data to the cache file with the specified filename and also set the open password, the save format is baseed on the file extension of the filename  . |
| [`get_image_stream(, uid, picid)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/get_image_stream/#system.string-system.string) | Get Stream of image. |
| [`get_ole(self, uid, sheetname, oleid, label)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/get_ole/#system.string-system.string-int-any) | Gets the byte array data of the  embedded ole object . |
| [`check_in_cache_for_collaborative(self, uid)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/check_in_cache_for_collaborative/#system.string) | Check wether workbook instance is in memory cache .this method is apply for Collaborative mode only. |
| [`update_cell(self, p, uid)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/update_cell/#system.string-system.string) | Applies the update operation. |
| [`insert_image(self, uid, p, s, image_url)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/insert_image/#system.string-system.string-io.rawiobase-system.string) | Inserts image in the worksheet from file stream or the URL,(either the file stream or the URL shall be provided)<br/>or<br/>Inserts shape ,when the p.type is one of AutoShapeType |
| [`copy_image_or_shape(self, uid, p)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/copy_image_or_shape/#system.string-system.string) | Copys image or shape. |
| [`error_json(self, msg)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/error_json/#system.string) | Gets the error message string in JSON format. |
| [`get_grid_load_format(, extension)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/get_grid_load_format/#system.string) | Gets the load format by file extension |
| [`get_image_url(, uid, picid, delimiter)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/get_image_url/#system.string-system.string-system.string) | Gets the image URL. |
| [`set_image_url_base(, base_image_url)`](/cells/python-net/aspose.cellsgridjs/gridjsworkbook/set_image_url_base/#system.string) | Set the base image get action URL from controller . |



### See Also
* module [`aspose.cellsgridjs`](..)
