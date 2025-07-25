---
title: LowCodeSaveOptionsProviderOfPlaceHolders类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
## LowCodeSaveOptionsProviderOfPlaceHolders类
实现提供保存选项，将分割部分保存到文件中
并且结果文件的路径是用占位符定义的。



**继承：** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



LowCodeSaveOptionsProviderOfPlaceHolders 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |实例化一个实例以根据指定的模板提供保存选项。|


### 属性
|属性|描述|
| :- | :- |
| [sheet_index_offset](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) |文件路径中使用的工作表索引之间的偏移量<br/>及其实际值（[`SplitPartInfo.sheet_index`](/cells/python-net/zh/aspose.cells.lowcode/splitpartinfo#sheet_index)）。|
| [split_part_index_offset](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) |分割部分索引与文件路径中使用的索引之间的偏移量<br/>及其实际值（[`SplitPartInfo.part_index`](/cells/python-net/zh/aspose.cells.lowcode/splitpartinfo#part_index)）。|
| [build_path_with_sheet_always](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) |是否始终将工作表索引或名称添加到文件路径。<br/>默认值为 false，即当只有一张 Sheet 时，<br/>工作表索引和名称以及相应的前缀（[`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix)）<br/>将不会添加到文件路径。|
| [build_path_with_split_part_always](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) |是否始终将分割部分索引添加到文件路径。<br/>默认值为 false，即当只有一个分割部分时，<br/>分割部分索引和相应的前缀（[`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix)）<br/>将不会添加到文件路径。|
| [sheet_name_prefix](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |工作表索引的前缀。|
| [sheet_index_prefix](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |工作表索引的前缀。|
| [split_part_prefix](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) |分割部分索引的前缀。|
| [save_options_template](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options) 中创建保存选项实例的模板。|


### 方法
|方法|描述|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) |获取保存选项，从中获取当前分割部分的输出设置。|
| [`finish(self, part)`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



### 也可以看看
* 模块[`aspose.cells.lowcode`](..)
* 类 [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
