---
title: ExportTableOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 560
url: /zh/aspose.cells/exporttableoptions/
is_root: false
---
## ExportTableOptions类
代表所有导出表选项。



ExportTableOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/exporttableoptions/__init__/#) |构造 ExportTableOptions 的新实例|


### 属性
|属性|描述|
| :- | :- |
| [export_column_name](/cells/python-net/zh/aspose.cells/exporttableoptions/export_column_name) |指示是否将第一行的数据导出到DataTable的列名中。<br/>默认值为 false。|
| [skip_error_value](/cells/python-net/zh/aspose.cells/exporttableoptions/skip_error_value) |指示是否跳过列的无效值。<br/>例如，如果列类型为 decimal，则该值大于 decimal.MaxValue<br/>并且此属性为真，我们不会再次抛出异常。<br/>默认值为 false。|
| [plot_visible_cells](/cells/python-net/zh/aspose.cells/exporttableoptions/plot_visible_cells) |仅导出可见单元格。|
| [plot_visible_rows](/cells/python-net/zh/aspose.cells/exporttableoptions/plot_visible_rows) |仅导出可见的行。|
| [plot_visible_columns](/cells/python-net/zh/aspose.cells/exporttableoptions/plot_visible_columns) |仅导出可见的列。|
| [export_as_string](/cells/python-net/zh/aspose.cells/exporttableoptions/export_as_string) |将单元格的字符串值导出到数据表。|
| [export_as_html_string](/cells/python-net/zh/aspose.cells/exporttableoptions/export_as_html_string) |将单元格的 html 字符串值导出到 DataTable。|
| [format_strategy](/cells/python-net/zh/aspose.cells/exporttableoptions/format_strategy) |获取并设置将值导出为字符串值时的格式策略。|
| [check_mixed_value_type](/cells/python-net/zh/aspose.cells/exporttableoptions/check_mixed_value_type) | False，Aspose.Cells 将通过第一行的值类型设置 DataColumn 的类型以提高性能。<br/>正确，Aspose.Cells 将在设置 DataColumn 的类型之前检查列中的值类型是否混合<br/>并且值类型混合，DataColumn 的类型将为字符串。|
| [allow_db_null](/cells/python-net/zh/aspose.cells/exporttableoptions/allow_db_null) |该值指示此表是否允许 DBNulls。|
| [is_vertical](/cells/python-net/zh/aspose.cells/exporttableoptions/is_vertical) |如果 Workbook 文件中的一行代表 DataTable 中的一行，则为 True。如果 Workbook 文件中的列代表 DataTable 中的一行，则为 False。|
| [indexes](/cells/python-net/zh/aspose.cells/exporttableoptions/indexes) |应导出的列/行的索引。|
| [rename_strategy](/cells/python-net/zh/aspose.cells/exporttableoptions/rename_strategy) |列重复名称的策略。|


### 方法
|方法|描述|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/zh/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) |对当前要导出的单元格的值进行预处理。|



### 注意事项

如果对导出有一些特殊要求，例如忽略错误值，用户可以扩展此类
覆盖相应的api来达到目的。

### 也可以看看
* 模块[`aspose.cells`](..)
