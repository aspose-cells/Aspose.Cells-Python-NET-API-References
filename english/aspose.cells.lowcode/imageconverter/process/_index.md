---
title: process method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.lowcode/imageconverter/process/
is_root: false
---

## process(, template_file, result_file) {#str-str}

Converts template file to images.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| template_file | str | The template file to be converted to images. |
| result_file | str | The resultant file(name pattern) for generated images. |
### Remarks

The output files will be build from the specified result file
by appending sequence number of the sheet and split part.
For example, if the specified output file is Image.png, then the generated image
files will be Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

## process(, load_options, save_options) {#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}

Converts template file to images



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions) | Options for input and loading |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions) | Options for output and saving |
### Remarks

When converting to image of format that supports multiple pages(such as tiff),
the specified [`LowCodeSaveOptions.output_file`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions#output_file)
or [`LowCodeSaveOptions.output_stream`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions#output_stream) will be used directly for the resultant image.


For other types of image, if the save options has specified Stream as output,
then all resultant images will be saved to the same Stream.
Otherwise, the output files will be build from the specified output file
of the save options by appending sequence number of the sheet and split part.
For example, if the specified output file is Image.png, then the generated image
files will be Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

## process(, load_options, save_options, provider) {#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeSaveOptionsProvider}

Converts template file to images



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions) | Options for input and loading |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions) | Options for saving.<br/>Its output([`LowCodeSaveOptions.output_file`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions#output_file) or [`LowCodeSaveOptions.output_stream`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions#output_stream))<br/>takes no effect because all outputs will be specified by the "provider" parameter |
| provider | [`AbstractLowCodeSaveOptionsProvider`](/cells/python-net/aspose.cells.lowcode/abstractlowcodesaveoptionsprovider) | Provider of save options for saving the generated images |



### See Also
* module [`aspose.cells.lowcode`](../../)
* class [`ImageConverter`](/cells/python-net/aspose.cells.lowcode/imageconverter)
