---
title: LowCodeSaveOptionsProviderOfAssembling类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
## LowCodeSaveOptionsProviderOfAssembling类
实现提供保存选项，将分割部分保存到文件中
并且结果文件的路径命名为（可能包含目录）：
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+工作表索引（或工作表名称）
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail)。



**继承：** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



LowCodeSaveOptionsProviderOfAssembling 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) |构造一个新的 LowCodeSaveOptionsProviderOfAssembling 实例|


### 属性
|属性|描述|
| :- | :- |
| [path_header](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) |文件路径的标题部分（在工作表添加的内容和拆分部分之前）。|
| [path_tail](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) |文件路径的尾部（序列号之后）。<br/>它应该包括文件名的扩展名。|
| [use_sheet_name](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) |是否使用工作表名称而非工作表索引构建文件路径。默认值为 false。|
| [sheet_prefix](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |工作表索引的前缀。|
| [split_part_prefix](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) |分割部分索引的前缀。|
| [sheet_index_offset](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) |文件路径中使用的工作表索引之间的偏移量<br/>及其实际值（[`SplitPartInfo.sheet_index`](/cells/python-net/zh/aspose.cells.lowcode/splitpartinfo#sheet_index)）。|
| [split_part_index_offset](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) |分割部分索引与文件路径中使用的索引之间的偏移量<br/>及其实际值（[`SplitPartInfo.part_index`](/cells/python-net/zh/aspose.cells.lowcode/splitpartinfo#part_index)）。|
| [build_path_with_sheet_always](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) |是否始终将工作表索引或名称添加到文件路径。<br/>默认值为 false，即当只有一张 Sheet 时，<br/>工作表索引（或名称）和相应的前缀将不会添加到文件路径中。|
| [build_path_with_split_part_always](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) |是否始终将分割部分索引添加到文件路径。<br/>默认值为 false，即当只有一个分割部分时，<br/>分割部分索引和相应的前缀将不会添加到文件路径中。|
| [save_options_template](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options) 中创建保存选项实例的模板。|


### 方法
|方法|描述|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) |获取保存选项，从中获取当前分割部分的输出设置。|
| [`finish(self, part)`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



### 也可以看看
* 模块[`aspose.cells.lowcode`](..)
* 类 [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/zh/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
