---
title: CopyOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 340
url: /zh/aspose.cells/copyoptions/
is_root: false
---
## CopyOptions类
代表复制选项。



CopyOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/copyoptions/__init__/#) | CopyOptions 构造函数。|


### 属性
|属性|描述|
| :- | :- |
| [keep_macros](/cells/python-net/zh/aspose.cells/copyoptions/keep_macros) |表示是否保留宏；|
| [extend_to_adjacent_range](/cells/python-net/zh/aspose.cells/copyoptions/extend_to_adjacent_range) |指示在将范围复制到相邻范围时是否扩展范围。|
| [copy_names](/cells/python-net/zh/aspose.cells/copyoptions/copy_names) |表示是否复制名称。|
| [copy_invalid_formulas_as_values](/cells/python-net/zh/aspose.cells/copyoptions/copy_invalid_formulas_as_values) |如果公式对于目标无效，则仅复制值。|
| [column_character_width](/cells/python-net/zh/aspose.cells/copyoptions/column_character_width) |指示是否以字符为单位复制列宽。|
| [refer_to_sheet_with_same_name](/cells/python-net/zh/aspose.cells/copyoptions/refer_to_sheet_with_same_name) |在 ms excel 中，将一个工作表复制到另一个工作表时，复制引用其他工作表的公式时，<br/>复制的公式应参考源工作簿。<br/>然而，在某些情况下，用户可能需要复制的公式引用具有相同名称的工作表<br/>在同一工作簿中，例如在执行此复制操作之前已复制过这些工作表，<br/>那么这个属性应该保持为真。|
| [refer_to_destination_sheet](/cells/python-net/zh/aspose.cells/copyoptions/refer_to_destination_sheet) |当复制同一文件中的范围并且图表引用源工作表时，<br/>False 表示复制的图表的数据源不会改变。<br/> True 表示复制的图表的数据源指的是目标工作表。|



### 也可以看看
* 模块[`aspose.cells`](..)
