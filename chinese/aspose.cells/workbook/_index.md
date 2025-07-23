---
title: Workbook类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1570
url: /zh/aspose.cells/workbook/
is_root: false
---
## Workbook类
表示创建 Excel 电子表格的根对象。



Workbook 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/workbook/__init__/#) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例。|
| [`__init__(self, file_format_type)`](/cells/python-net/zh/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) |初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例。|
| [`__init__(self, file)`](/cells/python-net/zh/aspose.cells/workbook/__init__/#str) |初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开一个文件。|
| [`__init__(self, stream)`](/cells/python-net/zh/aspose.cells/workbook/__init__/#io.rawiobase) |初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开一个流。|
| [`__init__(self, file, load_options)`](/cells/python-net/zh/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) |初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开一个文件。|
| [`__init__(self, stream, load_options)`](/cells/python-net/zh/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) |初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开流。|


### 属性
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
| [vba_project](/cells/python-net/zh/aspose.cells/workbook/vba_project) |在电子表格中获取 [`Workbook.vba_project`](/cells/python-net/zh/aspose.cells/workbook#vba_project)。|
| [has_macro](/cells/python-net/zh/aspose.cells/workbook/has_macro) |指示此电子表格是否包含宏/VBA。|
| [has_revisions](/cells/python-net/zh/aspose.cells/workbook/has_revisions) |获取工作簿是否有任何跟踪更改|
| [file_name](/cells/python-net/zh/aspose.cells/workbook/file_name) |获取并设置当前文件名。|
| [cells_data_table_factory](/cells/python-net/zh/aspose.cells/workbook/cells_data_table_factory) |获取从自定义对象构建 ICellsDataTable 的工厂|
| [data_sorter](/cells/python-net/zh/aspose.cells/workbook/data_sorter) |获取 DataSorter 对象来对数据进行排序。|
| [theme](/cells/python-net/zh/aspose.cells/workbook/theme) |获取主题名称。|
| [built_in_document_properties](/cells/python-net/zh/aspose.cells/workbook/built_in_document_properties) |返回一个 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合代表电子表格的所有内置文档属性。|
| [custom_document_properties](/cells/python-net/zh/aspose.cells/workbook/custom_document_properties) |返回代表电子表格的所有自定义文档属性的 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合。|
| [file_format](/cells/python-net/zh/aspose.cells/workbook/file_format) |获取并设置文件格式。|
| [has_custom_function](/cells/python-net/zh/aspose.cells/workbook/has_custom_function) |检测此工作簿中是否使用了自定义函数，<br/>例如在单元格的公式中、在定义的名称中……|
| [content_type_properties](/cells/python-net/zh/aspose.cells/workbook/content_type_properties) |获取工作簿中 [`ContentTypeProperty`](/cells/python-net/zh/aspose.cells.properties/contenttypeproperty) 对象的列表。|
| [custom_xml_parts](/cells/python-net/zh/aspose.cells/workbook/custom_xml_parts) |表示自定义 XML 数据存储部分（包内的自定义 XML 数据）。|
| [data_mashup](/cells/python-net/zh/aspose.cells/workbook/data_mashup) |获取混搭数据。|
| [ribbon_xml](/cells/python-net/zh/aspose.cells/workbook/ribbon_xml) |获取并设置定义 Ribbon UI 的 XML 文件。|
| [absolute_path](/cells/python-net/zh/aspose.cells/workbook/absolute_path) |获取并设置文件的绝对路径。|
| [data_connections](/cells/python-net/zh/aspose.cells/workbook/data_connections) |获取 ExternalConnection 集合。|
| [data_model](/cells/python-net/zh/aspose.cells/workbook/data_model) |获取工作簿中的数据模型。|


### 方法
|方法|描述|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/zh/aspose.cells/workbook/save/#str-aspose.cells.saveformat) |将工作簿保存到磁盘。|
| [`save(self, file_name)`](/cells/python-net/zh/aspose.cells/workbook/save/#str) |将工作簿保存到磁盘。|
| [`save(self, file_name, save_options)`](/cells/python-net/zh/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) |将工作簿保存到磁盘。|
| [`save(self, stream, save_format)`](/cells/python-net/zh/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) |将工作簿保存到流中。|
| [`save(self, stream, save_options)`](/cells/python-net/zh/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) |将工作簿保存到流中。|
| [`create_style(self)`](/cells/python-net/zh/aspose.cells/workbook/create_style/#) |創造出新的風格。|
| [`create_style(self, clone_default_style)`](/cells/python-net/zh/aspose.cells/workbook/create_style/#bool) |創造出新的風格。|
| [`replace(self, place_holder, new_value)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-str) |用新字符串替换单元格的值。|
| [`replace(self, place_holder, new_value)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-int) |用新的整数替换单元格的值。|
| [`replace(self, place_holder, new_value)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-float) |用新的双精度值替换单元格的值。|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-list-bool) |用新的字符串数组替换单元格的值。|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-list-bool) |用整数数组替换单元格的值。|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-list-bool) |用双精度数组替换单元格的值。|
| [`replace(self, bool_value, new_value)`](/cells/python-net/zh/aspose.cells/workbook/replace/#bool-any) |用新数据替换单元格的值。|
| [`replace(self, int_value, new_value)`](/cells/python-net/zh/aspose.cells/workbook/replace/#int-any) |用新数据替换单元格的值。|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/zh/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) |用新字符串替换单元格的值。|
| [`copy(self, source, copy_options)`](/cells/python-net/zh/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) |复制另一个 Workbook 对象。|
| [`copy(self, source)`](/cells/python-net/zh/aspose.cells/workbook/copy/#aspose.cells.workbook) |从源 Workbook 对象复制数据。|
| [`calculate_formula(self)`](/cells/python-net/zh/aspose.cells/workbook/calculate_formula/#) |计算公式的结果。|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/zh/aspose.cells/workbook/calculate_formula/#bool) |计算公式的结果。|
| [`calculate_formula(self, options)`](/cells/python-net/zh/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) |本工作簿中的计算公式。|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/zh/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) |刷新动态数组公式（根据当前数据溢出到相邻单元格的新范围）<br/>工作簿中的其他公式即使被动态数组公式使用，也不会被递归计算。|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/zh/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |刷新动态数组公式（根据当前数据溢出到相邻单元格的新范围）|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/zh/aspose.cells/workbook/import_xml/#str-str-int-int) |将 XML 数据文件导入/更新到工作簿。|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/zh/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) |将 XML 数据文件导入/更新到工作簿。|
| [`export_xml(self, map_name, path)`](/cells/python-net/zh/aspose.cells/workbook/export_xml/#str-str) |导出由指定的 XML 映射链接的 XML 数据。|
| [`export_xml(self, map_name, stream)`](/cells/python-net/zh/aspose.cells/workbook/export_xml/#str-io.rawiobase) |导出 XML 数据。|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/zh/aspose.cells/workbook/parse_formulas/#bool) |解析从模板文件加载或设置到单元格时尚未解析的所有公式。|
| [`start_access_cache(self, opts)`](/cells/python-net/zh/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) |启动使用缓存访问数据的会话。|
| [`close_access_cache(self, opts)`](/cells/python-net/zh/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) |关闭使用缓存访问数据的会话。|
| [`remove_unused_styles(self)`](/cells/python-net/zh/aspose.cells/workbook/remove_unused_styles/#) |删除所有未使用的样式。|
| [`create_builtin_style(self, type)`](/cells/python-net/zh/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) |根据给定类型创建内置样式。|
| [`create_cells_color(self)`](/cells/python-net/zh/aspose.cells/workbook/create_cells_color/#) |创建一个 [`CellsColor`](/cells/python-net/zh/aspose.cells/cellscolor) 对象。|
| [`combine(self, second_workbook)`](/cells/python-net/zh/aspose.cells/workbook/combine/#aspose.cells.workbook) |合并另一个 Workbook 对象。|
| [`get_style_in_pool(self, index)`](/cells/python-net/zh/aspose.cells/workbook/get_style_in_pool/#int) |获取样式池中的样式。<br/>工作簿中的所有样式都将聚集到一个池中。<br/>单元格中只有一个简单的参考索引。|
| [`get_fonts(self)`](/cells/python-net/zh/aspose.cells/workbook/get_fonts/#) |获取样式池中的所有字体。|
| [`get_named_style(self, name)`](/cells/python-net/zh/aspose.cells/workbook/get_named_style/#str) |获取样式池中的命名样式。|
| [`merge_named_styles(self, source)`](/cells/python-net/zh/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) |合并来自其他 Excel 文件的命名样式。|
| [`change_palette(self, color, index)`](/cells/python-net/zh/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) |更改指定索引中的电子表格的调色板。|
| [`is_color_in_palette(self, color)`](/cells/python-net/zh/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) |检查颜色是否存在于电子表格的调色板中。|
| [`get_matching_color(self, raw_color)`](/cells/python-net/zh/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |在当前调色板中查找最匹配的颜色。|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/zh/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) |设置加密选项。|
| [`protect(self, protection_type, password)`](/cells/python-net/zh/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) |保护工作簿。|
| [`protect_shared_workbook(self, password)`](/cells/python-net/zh/aspose.cells/workbook/protect_shared_workbook/#str) |保护共享工作簿。|
| [`unprotect(self, password)`](/cells/python-net/zh/aspose.cells/workbook/unprotect/#str) |取消保护工作簿。|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/zh/aspose.cells/workbook/unprotect_shared_workbook/#str) |取消保护共享工作簿。|
| [`remove_macro(self)`](/cells/python-net/zh/aspose.cells/workbook/remove_macro/#) |从此电子表格中删除 VBA/宏。|
| [`remove_digital_signature(self)`](/cells/python-net/zh/aspose.cells/workbook/remove_digital_signature/#) |从此电子表格中删除数字签名。|
| [`accept_all_revisions(self)`](/cells/python-net/zh/aspose.cells/workbook/accept_all_revisions/#) |接受工作簿中的所有修订。|
| [`remove_external_links(self)`](/cells/python-net/zh/aspose.cells/workbook/remove_external_links/#) |删除工作簿中的所有外部链接。|
| [`get_theme_color(self, type)`](/cells/python-net/zh/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) |获取主题颜色。|
| [`set_theme_color(self, type, color)`](/cells/python-net/zh/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) |设置主题颜色|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/zh/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) |风俗为主题。|
| [`copy_theme(self, source)`](/cells/python-net/zh/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) |从另一个工作簿复制主题。|
| [`has_exernal_links(self)`](/cells/python-net/zh/aspose.cells/workbook/has_exernal_links/#) |指示此工作簿是否包含指向其他数据源的外部链接。|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/zh/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) |更新自定义函数的定义。|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/zh/aspose.cells/workbook/update_linked_data_source/#list) |如果此工作簿包含指向其他数据源的外部链接，<br/> Aspose.Cells 将尝试从给定来源检索最新数据。|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/zh/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) |为电子表格文件设置数字签名（Excel2007及更高版本）。|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/zh/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) |向 OOXML 电子表格文件（Excel2007 及更高版本）添加数字签名。|
| [`get_digital_signature(self)`](/cells/python-net/zh/aspose.cells/workbook/get_digital_signature/#) |从文件获取数字签名。|
| [`remove_personal_information(self)`](/cells/python-net/zh/aspose.cells/workbook/remove_personal_information/#) |删除个人信息。|
| [`close(self)`](/cells/python-net/zh/aspose.cells/workbook/close/#) |自 Python 协议以来，包装器跳过了 Dispose()|



### 注意事项

Workbook 类表示一个 Excel 电子表格。每个电子表格可以包含多个工作表。
该类的基本功能是打开和保存原生的excel文件。
该类具有一些高级功能，例如从其他工作簿复制数据、合并两个工作簿、将 Excel 转换为 PDF、将 Excel 渲染为图像以及保护 Excel 电子表格。

### 例子

以下示例从名为 designer.xls 的 Excel 文件加载 Workbook，并使水平和垂直滚动条不可见。
然后，它分别用电子表格中的整数值和字符串值替换两个字符串值，最后将工作簿保存为 Excel xlsx 文件。

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
* 类 [`Style`](/cells/python-net/zh/aspose.cells/style)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
* 类 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection)
