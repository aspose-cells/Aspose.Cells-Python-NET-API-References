---
title: LowCodeSaveOptionsProviderOfPlaceHolders class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 140
url: /aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---

## LowCodeSaveOptionsProviderOfPlaceHolders class

Implementation to provide save options which save split parts to files
and the path of resultant file are defined with placeholders.



**Inheritance:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders) → 
[`AbstractLowCodeSaveOptionsProvider`](/cells/python-net/aspose.cells.lowcode/abstractlowcodesaveoptionsprovider)



The LowCodeSaveOptionsProviderOfPlaceHolders type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) | Instantiates an instance to provide save options according to specified templates. |


### Properties
| Property | Description |
| :- | :- |
| [sheet_index_offset](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Offset of sheet's index between what used in file path<br/>and its actual value([`SplitPartInfo.sheet_index`](/cells/python-net/aspose.cells.lowcode/splitpartinfo#sheet_index)). |
| [split_part_index_offset](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Offset of split part's index between what used in file path<br/>and its actual value([`SplitPartInfo.part_index`](/cells/python-net/aspose.cells.lowcode/splitpartinfo#part_index)). |
| [build_path_with_sheet_always](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Whether add sheet index or name to file path always.<br/>Default value is false, that is, when there is only one sheet,<br/>the sheet index and name and corresponding prefix([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/>will not be added to the file path. |
| [build_path_with_split_part_always](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Whether add split part index to file path always.<br/>Default value is false, that is, when there is only one split part,<br/>the split part index and corresponding prefix([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/>will not be added to the file path. |
| [sheet_name_prefix](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) | Prefix for the index of worksheet. |
| [sheet_index_prefix](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) | Prefix for the index of worksheet. |
| [split_part_prefix](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Prefix for the index of split part. |
| [save_options_template](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | The template for creating instance of save options in [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options). |


### Methods
| Method | Description |
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Gets the save options from which to get the output settings for currently split part. |
| [`finish(self, part)`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) | Releases resources after processing currently split part. |



### See Also
* module [`aspose.cells.lowcode`](..)
* class [`AbstractLowCodeSaveOptionsProvider`](/cells/python-net/aspose.cells.lowcode/abstractlowcodesaveoptionsprovider)
* class [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
