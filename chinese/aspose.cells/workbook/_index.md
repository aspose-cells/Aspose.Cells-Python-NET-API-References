---
title: Workbook类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1660
url: /zh/aspose.cells/workbook/
is_root: false
---
## Workbook类
表示创建 Excel 电子表格的根对象。



Workbook 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/workbook/__init__/#) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例。|
| [__init__](/cells/python-net/zh/aspose.cells/workbook/__init__/#aspose.cells.FileFormatType) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例。|
| [__init__](/cells/python-net/zh/aspose.cells/workbook/__init__/#str) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例并打开文件。|
| [__init__](/cells/python-net/zh/aspose.cells/workbook/__init__/#io.RawIOBase) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例并打开一个流。|
| [__init__](/cells/python-net/zh/aspose.cells/workbook/__init__/#str-aspose.cells.LoadOptions) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例并打开文件。|
| [__init__](/cells/python-net/zh/aspose.cells/workbook/__init__/#io.RawIOBase-aspose.cells.LoadOptions) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例并打开流。|


### 特性
|属性|描述|
| :- | :- |
| [settings](/cells/python-net/zh/aspose.cells/workbook/settings) |代表工作簿设置。|
| [worksheets](/cells/python-net/zh/aspose.cells/workbook/worksheets) |获取电子表格中的 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection) 集合。|
| [is_licensed](/cells/python-net/zh/aspose.cells/workbook/is_licensed) |指示是否设置了许可证。|
| [colors](/cells/python-net/zh/aspose.cells/workbook/colors) |返回电子表格调色板中的颜色。|
| [count_of_styles_in_pool](/cells/python-net/zh/aspose.cells/workbook/count_of_styles_in_pool) |获取样式池中的样式数量。|
| [default_style](/cells/python-net/zh/aspose.cells/workbook/default_style) |获取或设置工作簿的默认 [`Style`](/cells/python-net/zh/aspose.cells/style) 对象。|
| [is_digitally_signed](/cells/python-net/zh/aspose.cells/workbook/is_digitally_signed) |指示此电子表格是否经过数字签名。|
| [is_workbook_protected_with_password](/cells/python-net/zh/aspose.cells/workbook/is_workbook_protected_with_password) |指示结构或窗口是否受密码保护。|
| [vba_project](/cells/python-net/zh/aspose.cells/workbook/vba_project) |获取电子表格中的 [`Workbook.vba_project`](/cells/python-net/zh/aspose.cells/workbook#vba_project)。|
| [has_macro](/cells/python-net/zh/aspose.cells/workbook/has_macro) |指示此电子表格是否包含宏/VBA。|
| [has_revisions](/cells/python-net/zh/aspose.cells/workbook/has_revisions) |获取工作簿是否有任何跟踪的更改|
| [file_name](/cells/python-net/zh/aspose.cells/workbook/file_name) |获取和设置当前文件名。|
| [cells_data_table_factory](/cells/python-net/zh/aspose.cells/workbook/cells_data_table_factory) |获取用于从自定义对象构建 ICellsDataTable 的工厂|
| [data_sorter](/cells/python-net/zh/aspose.cells/workbook/data_sorter) |获取 DataSorter 对象以对数据进行排序。|
| [theme](/cells/python-net/zh/aspose.cells/workbook/theme) |获取主题名称。|
| [built_in_document_properties](/cells/python-net/zh/aspose.cells/workbook/built_in_document_properties) |返回 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合表示电子表格的所有内置文档属性。|
| [custom_document_properties](/cells/python-net/zh/aspose.cells/workbook/custom_document_properties) |返回 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合表示电子表格的所有自定义文档属性。|
| [file_format](/cells/python-net/zh/aspose.cells/workbook/file_format) |获取和设置文件格式。|
| [interrupt_monitor](/cells/python-net/zh/aspose.cells/workbook/interrupt_monitor) |获取和设置中断监视器。|
| [content_type_properties](/cells/python-net/zh/aspose.cells/workbook/content_type_properties) |获取工作簿中 [`ContentTypeProperty`](/cells/python-net/zh/aspose.cells.properties/contenttypeproperty) 对象的列表。|
| [custom_xml_parts](/cells/python-net/zh/aspose.cells/workbook/custom_xml_parts) |表示自定义 XML 数据存储部件（包内的自定义 XML 数据）。|
| [data_mashup](/cells/python-net/zh/aspose.cells/workbook/data_mashup) |获取混搭数据。|
| [ribbon_xml](/cells/python-net/zh/aspose.cells/workbook/ribbon_xml) |获取和设置定义功能区 UI 的 XML 文件。|
| [absolute_path](/cells/python-net/zh/aspose.cells/workbook/absolute_path) |获取和设置文件的绝对路径。|
| [data_connections](/cells/python-net/zh/aspose.cells/workbook/data_connections) |获取 [`ExternalConnection`](/cells/python-net/zh/aspose.cells.externalconnections/externalconnection) 集合。|


### 方法
|方法|描述|
| :- | :- |
| [save](/cells/python-net/zh/aspose.cells/workbook/save/#str-aspose.cells.SaveFormat) |将工作簿保存到磁盘。|
| [save](/cells/python-net/zh/aspose.cells/workbook/save/#str) |将工作簿保存到磁盘。|
| [save](/cells/python-net/zh/aspose.cells/workbook/save/#str-aspose.cells.SaveOptions) |将工作簿保存到磁盘。|
| [save](/cells/python-net/zh/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveFormat) |将工作簿保存到流中。|
| [save](/cells/python-net/zh/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveOptions) |将工作簿保存到流中。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-str) |用新字符串替换单元格的值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-int) |将单元格的值替换为新整数。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-float) |将单元格的值替换为新的双精度值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-list-bool) |用新的字符串数组替换单元格的值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-list-bool) |用整数数组替换单元格的值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-list-bool) |用双精度数组替换单元格的值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#bool-any) |用新数据替换单元格的值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#int-any) |用新数据替换单元格的值。|
| [replace](/cells/python-net/zh/aspose.cells/workbook/replace/#str-str-aspose.cells.ReplaceOptions) |用新字符串替换单元格的值。|
| [copy](/cells/python-net/zh/aspose.cells/workbook/copy/#aspose.cells.Workbook-aspose.cells.CopyOptions) |复制另一个 Workbook 对象。|
| [copy](/cells/python-net/zh/aspose.cells/workbook/copy/#aspose.cells.Workbook) |从源 Workbook 对象复制数据。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/workbook/calculate_formula/#) |计算公式的结果。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/workbook/calculate_formula/#bool) |计算公式的结果。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/workbook/calculate_formula/#aspose.cells.CalculationOptions) |计算本工作簿中的公式。|
| [refresh_dynamic_array_formulas](/cells/python-net/zh/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) |刷新动态数组公式（根据当前数据溢出到新的相邻单元格范围）<br/>工作簿中的其他公式即使被动态数组公式使用，也不会进行递归计算。|
| [refresh_dynamic_array_formulas](/cells/python-net/zh/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.CalculationOptions) |刷新动态数组公式（根据当前数据溢出到新的相邻单元格范围）|
| [import_xml](/cells/python-net/zh/aspose.cells/workbook/import_xml/#str-str-int-int) |将 XML 数据文件导入/更新到工作簿中。|
| [import_xml](/cells/python-net/zh/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) |将 XML 数据文件导入/更新到工作簿中。|
| [export_xml](/cells/python-net/zh/aspose.cells/workbook/export_xml/#str-str) |导出由指定 XML 映射链接的 XML 数据。|
| [export_xml](/cells/python-net/zh/aspose.cells/workbook/export_xml/#str-io.RawIOBase) |导出 XML 数据。|
| [parse_formulas](/cells/python-net/zh/aspose.cells/workbook/parse_formulas/#bool) |解析从模板文件加载或设置到单元格时尚未解析的所有公式。|
| [start_access_cache](/cells/python-net/zh/aspose.cells/workbook/start_access_cache/#aspose.cells.AccessCacheOptions) |启动使用缓存访问数据的会话。|
| [close_access_cache](/cells/python-net/zh/aspose.cells/workbook/close_access_cache/#aspose.cells.AccessCacheOptions) |关闭使用缓存访问数据的会话。|
| [remove_unused_styles](/cells/python-net/zh/aspose.cells/workbook/remove_unused_styles/#) |删除所有未使用的样式。|
| [create_style](/cells/python-net/zh/aspose.cells/workbook/create_style/#) |创造了新的风格。|
| [create_builtin_style](/cells/python-net/zh/aspose.cells/workbook/create_builtin_style/#aspose.cells.BuiltinStyleType) |按给定类型创建内置样式。|
| [create_cells_color](/cells/python-net/zh/aspose.cells/workbook/create_cells_color/#) |创建一个 [`CellsColor`](/cells/python-net/zh/aspose.cells/cellscolor) 对象。|
| [combine](/cells/python-net/zh/aspose.cells/workbook/combine/#aspose.cells.Workbook) |组合另一个 Workbook 对象。|
| [get_style_in_pool](/cells/python-net/zh/aspose.cells/workbook/get_style_in_pool/#int) |获取样式池中的样式。<br/>工作簿中的所有样式都将收集到一个池中。<br/>单元格中只有一个简单的参考索引。|
| [get_fonts](/cells/python-net/zh/aspose.cells/workbook/get_fonts/#) |获取样式池中的所有字体。|
| [get_named_style](/cells/python-net/zh/aspose.cells/workbook/get_named_style/#str) |获取样式池中指定的样式。|
| [change_palette](/cells/python-net/zh/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) |更改指定索引中电子表格的调色板。|
| [is_color_in_palette](/cells/python-net/zh/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) |检查某种颜色是否在电子表格的调色板中。|
| [get_matching_color](/cells/python-net/zh/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) |在当前调色板中查找最匹配的颜色。|
| [set_encryption_options](/cells/python-net/zh/aspose.cells/workbook/set_encryption_options/#aspose.cells.EncryptionType-int) |设置加密选项。|
| [protect](/cells/python-net/zh/aspose.cells/workbook/protect/#aspose.cells.ProtectionType-str) |保护工作簿。|
| [protect_shared_workbook](/cells/python-net/zh/aspose.cells/workbook/protect_shared_workbook/#str) |保护共享工作簿。|
| [unprotect](/cells/python-net/zh/aspose.cells/workbook/unprotect/#str) |取消对工作簿的保护。|
| [unprotect_shared_workbook](/cells/python-net/zh/aspose.cells/workbook/unprotect_shared_workbook/#str) |取消对共享工作簿的保护。|
| [remove_macro](/cells/python-net/zh/aspose.cells/workbook/remove_macro/#) |从此电子表格中删除 VBA/宏。|
| [remove_digital_signature](/cells/python-net/zh/aspose.cells/workbook/remove_digital_signature/#) |从此电子表格中删除数字签名。|
| [accept_all_revisions](/cells/python-net/zh/aspose.cells/workbook/accept_all_revisions/#) |接受工作簿中所有跟踪的更改。|
| [remove_external_links](/cells/python-net/zh/aspose.cells/workbook/remove_external_links/#) |删除工作簿中的所有外部链接。|
| [get_theme_color](/cells/python-net/zh/aspose.cells/workbook/get_theme_color/#aspose.cells.ThemeColorType) |获取主题颜色。|
| [set_theme_color](/cells/python-net/zh/aspose.cells/workbook/set_theme_color/#aspose.cells.ThemeColorType-aspose.pydrawing.Color) |设置主题颜色|
| [custom_theme](/cells/python-net/zh/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) |海关主题。|
| [copy_theme](/cells/python-net/zh/aspose.cells/workbook/copy_theme/#aspose.cells.Workbook) |从另一个工作簿复制主题。|
| [has_exernal_links](/cells/python-net/zh/aspose.cells/workbook/has_exernal_links/#) |指示此工作簿是否包含指向其他数据源的外部链接。|
| [update_custom_function_definition](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.CustomFunctionDefinition) |更新自定义函数的定义。|
| [update_linked_data_source](/cells/python-net/zh/aspose.cells/workbook/update_linked_data_source/#list) |如果此工作簿包含其他数据源的外部链接，<br/> Aspose.Cells 将尝试从给定来源检索最新数据。|
| [set_digital_signature](/cells/python-net/zh/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) |为电子表格文件（Excel2007 及更高版本）设置数字签名。|
| [add_digital_signature](/cells/python-net/zh/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) |将数字签名添加到 OOXML 电子表格文件（Excel2007 及更高版本）。|
| [get_digital_signature](/cells/python-net/zh/aspose.cells/workbook/get_digital_signature/#) |从文件中获取数字签名。|
| [remove_personal_information](/cells/python-net/zh/aspose.cells/workbook/remove_personal_information/#) |删除个人信息。|



### 评论

Workbook 类表示 Excel 电子表格。每个电子表格可以包含多个工作表。
该类的基本功能是打开和保存本机 Excel 文件。
该类具有一些高级功能，例如从其他工作簿复制数据、合并两个工作簿、将 Excel 转换为 PDF、将 Excel 渲染为图像以及保护 Excel 电子表格。

### 例子

以下示例从名为 Designer.xls 的 Excel 文件加载 Workbook 并使水平和垂直滚动条不可见。
然后，它在电子表格中分别用整数值和字符串值替换两个字符串值，最后将工作簿保存为 Excel xlsx 文件。

```python
from aspose.cells import Workbook

# Open a designer file
designerFile = "designer.xls"
workbook = Workbook(designerFile)
# Set scroll bars
workbook.settings.is_h_scroll_bar_visible = False
workbook.settings.is_v_scroll_bar_visible = False
# Replace the placeholder string with new values
newInt = 100
workbook.replace("OldInt", newInt)
newString = "Hello!"
workbook.replace("OldString", newString)
workbook.save("result.xlsx")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`CellsColor`](/cells/python-net/zh/aspose.cells/cellscolor)
* 类 [`ContentTypeProperty`](/cells/python-net/zh/aspose.cells.properties/contenttypeproperty)
* 类 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty)
* 类 [`ExternalConnection`](/cells/python-net/zh/aspose.cells.externalconnections/externalconnection)
* 类 [`Style`](/cells/python-net/zh/aspose.cells/style)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
* 类 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection)
