---
title: ExportTableOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 580
url: /zh/aspose.cells/exporttableoptions/
is_root: false
---
## ExportTableOptions类
代表所有导出表选项。



ExportTableOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/exporttableoptions/__init__/#) |构造 ExportTableOptions 的新实例|


### 特性
|属性|描述|
| :- | :- |
| [export_column_name](/cells/python-net/zh/aspose.cells/exporttableoptions/export_column_name) |是否将第一行的数据导出到DataTable的列名。<br/>默认值为 false。|
| [skip_error_value](/cells/python-net/zh/aspose.cells/exporttableoptions/skip_error_value) |指示是否跳过列的无效值。<br/>例如，如果列类型为decimal，则该值大于decimal.MaxValue<br/>并且这个属性是true，我们不会再抛出异常。<br/>默认值为 false。|
| [plot_visible_cells](/cells/python-net/zh/aspose.cells/exporttableoptions/plot_visible_cells) |仅导出可见单元格。|
| [plot_visible_rows](/cells/python-net/zh/aspose.cells/exporttableoptions/plot_visible_rows) |仅导出可见行。|
| [plot_visible_columns](/cells/python-net/zh/aspose.cells/exporttableoptions/plot_visible_columns) |仅导出可见列。|
| [export_as_string](/cells/python-net/zh/aspose.cells/exporttableoptions/export_as_string) |将单元格的字符串值导出到数据表。|
| [export_as_html_string](/cells/python-net/zh/aspose.cells/exporttableoptions/export_as_html_string) |将单元格的 html 字符串值导出到 DataTable。|
| [format_strategy](/cells/python-net/zh/aspose.cells/exporttableoptions/format_strategy) |获取和设置将值导出为字符串值时的格式策略。|
| [check_mixed_value_type](/cells/python-net/zh/aspose.cells/exporttableoptions/check_mixed_value_type) | False，Aspose.Cells 将根据第一行的值类型设置 DataColumn 的类型以提高性能。<br/> True, Aspose.Cells 在设置DataColumn的类型之前会检查列中的值类型是否混合<br/>并且值类型是混合的，DataColumn 的类型将为字符串。|
| [allow_db_null](/cells/python-net/zh/aspose.cells/exporttableoptions/allow_db_null) |该值指示该表中是否允许 DBNull。|
| [is_vertical](/cells/python-net/zh/aspose.cells/exporttableoptions/is_vertical) |如果工作簿文件中的一行代表数据表中的一行，则为 True。如果工作簿文件中的列代表数据表中的行，则为 False。|
| [indexes](/cells/python-net/zh/aspose.cells/exporttableoptions/indexes) |应导出的列/行的索引。|
| [rename_strategy](/cells/python-net/zh/aspose.cells/exporttableoptions/rename_strategy) |列重复名称的策略。|


### 方法
|方法|描述|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/zh/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) |预处理要导出的当前单元格的值。|



### 评论

如果导出有一些特殊要求，例如忽略错误值，用户可以扩展此类
重写相应的api来达到目的。

### 也可以看看
* 模块[`aspose.cells`](..)
