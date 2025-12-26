---
title: IGridJsService class
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 150
url: /aspose.cellsgridjs/igridjsservice/
is_root: false
---

## IGridJsService class

Reprensents the basic operation apis interface used in controller actions.



The IGridJsService type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [`update_cell(self, p, uid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/update_cell/#system.string-system.string) | Applies the update operation. |
| [`check_in_cache_for_collaborative(self, uid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/check_in_cache_for_collaborative/#system.string) | Check wether workbook instance is in memory cache .this method is apply for Collaborative mode only. |
| [`detail_stream_json_with_uid(self, stream, file_path, uid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/detail_stream_json_with_uid/#io.rawiobase-system.string-system.string) | Write the JSON string  for the file to the stream  by the specified unique id. |
| [`detail_stream_json(self, stream, file_path)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/detail_stream_json/#io.rawiobase-system.string) | Write the JSON string  for the Workbook to the stream |
| [`lazy_loading_stream_json(self, stream, sheet_name, uid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/lazy_loading_stream_json/#io.rawiobase-system.string-system.string) | Writes the JSON string of the specified sheet in the file from the cache using the specified unique id  to the stream.. |
| [`add_image(self, p, uid, iscontrol, file_input_stream)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/add_image/#system.string-system.string-system.string-io.rawiobase) | Applies the add image from local file operation. |
| [`add_image_by_url(self, p, uid, imageurl)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/add_image_by_url/#system.string-system.string-system.string) | Applies the add image from remote URL operation. |
| [`copy_image(self, p, uid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/copy_image/#system.string-system.string) | Applies the copy image operation. |
| [`load(self, uid, filename)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/load/#system.string-system.string) | Gets the JSON  string  of the file from the cache using the specified unique id,set the output filename in the JSON. |
| [`image(self, uid, picid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/image/#system.string-system.string) | Get Stream of image. |
| [`ole(self, uid, sheetname, oleid, label)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/ole/#system.string-system.string-int-any) | Gets the byte array data of the  embedded ole object . |
| [`image_url(self, base_url, picid, uid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/image_url/#system.string-system.string-system.string) | Gets the image URL. |
| [`get_file(self, fileid)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/get_file/#system.string) | Get file stream |
| [`download(self, p, uid, filename)`](/cells/python-net/aspose.cellsgridjs/igridjsservice/download/#system.string-system.string-system.string) | Applies the download file operation |



### See Also
* module [`aspose.cellsgridjs`](..)
