---
title: AccessCacheOptions枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1810
url: /zh/aspose.cells/accesscacheoptions/
is_root: false
---
## AccessCacheOptions枚举
用于数据访问的缓存选项。可以与 | 结合使用多个选项一起使用的运算符。



AccessCacheOptions 类型公开以下成员：

### 领域
|场地|描述|
| :- | :- |
| NONE |没有用于任何数据访问的缓存。|
| ALL |对工作簿中的各种数据访问应用所有可能的优化。<br/>在优化访问期间不应更改所有设置和数据。|
| POSITION_AND_SIZE |应用可能的优化来获取对象（例如形状）的位置和大小。<br/>优化访问期间不应更改行高和列宽设置。|
| CELLS_DATA |应用可能的优化来获取单元格的值。<br/>Cells 数据（Cell 行的数据和设置）在执行期间不应更改<br/>优化访问，也不应该创建新的 Cell/Row 对象（例如<br/>由[索引器]）。|
| CELL_DISPLAY |应用可能的优化以获得与显示相关的结果<br/>细胞（[`Cell.display_string_value`](/cells/python-net/zh/aspose.cells/cell#display_string_value)、[`Cell.get_style`](/cells/python-net/zh/aspose.cells/cell/get_style)、[`Cell.get_display_style`](/cells/python-net/zh/aspose.cells/cell/get_display_style) 等）。<br/>Cells 数据和样式相关的对象（Cell/行/列样式、列宽等）不应更改<br/>在优化访问期间。|
| GET_FORMULA |应用可能的优化来获取公式。<br/>所有可能影响公式表达式的数据和设置（工作表的名称、名称的文本、<br/>表的列等）在优化访问期间不应更改。|
| SET_FORMULA |对设置公式应用可能的优化。<br/>所有可能影响公式表达式的数据和设置（工作表的名称、名称的文本、<br/>表的列等）在优化访问期间不应更改。|
| CALCULATE_FORMULA |对计算公式应用可能的优化。<br/>Cells 优化访问期间不应更改数据，不新建对象（Cell、Row 等）<br/>应该创建（例如通过 [indexer]）。|
| CONDITIONAL_FORMATTING |应用可能的优化来获取条件格式的格式结果。<br/>所有可能影响条件格式结果的数据和设置（<br/>条件格式、从属单元格值等）在优化访问期间不应更改。|
| VALIDATION |应用可能的优化以获得验证结果。<br/>所有可能影响验证结果的数据和设置（验证的设置，<br/>相关单元格值等）在优化访问期间不应更改。|



### 评论

对于某些特征，访问大数据集需要大量重复且复杂的操作
例如搜索、计算等，这些操作会花费很多额外的时间。
对于常见情况，所有依赖数据在访问过程中都保持不变，因此可以构建一些缓存并用于
提高访问性能。
为此，我们提供了这个API，以便用户可以指定哪种数据访问需求
通过可能的缓存机制进行优化。


请注意，对于不同的选项，可能需要不同的数据集为“只读”。
而访问数据的性能取决于很多方面，缓存机制的使用
不保证性能会得到改善。对于某些情况，
例如要访问的数据集很小，使用缓存可能会导致更多的时间，因为
缓存本身也需要一定的额外时间。

### 也可以看看
* 模块[`aspose.cells`](..)
