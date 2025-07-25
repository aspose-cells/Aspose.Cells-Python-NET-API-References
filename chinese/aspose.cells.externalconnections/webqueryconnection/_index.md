---
title: WebQueryConnection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells.externalconnections/webqueryconnection/
is_root: false
---
## WebQueryConnection类
指定 Web 查询源的属性。Web 查询将从 HTML 个表中检索数据。
还可以提供 HTTP“Get”参数，供 Web 服务器处理，从而生成 HTML
包括参数和参数元素。



**继承：** [`WebQueryConnection`](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection)



WebQueryConnection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [id](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/id) |  |
| [connection_id](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/connection_id) |  |
| [class_type](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/class_type) |获取此 ExternalConnection 对象的类型。|
| [power_query_formula](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/power_query_formula) |  |
| [type](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/type) |  |
| [source_type](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/source_type) |  |
| [sso_id](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/sso_id) |  |
| [save_password](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/save_password) |  |
| [save_data](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/save_data) |  |
| [refresh_on_load](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/refresh_on_load) |  |
| [reconnection_method_type](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/reconnection_method_type) |  |
| [reconnection_method](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/reconnection_method) |  |
| [only_use_connection_file](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/only_use_connection_file) |  |
| [odc_file](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/odc_file) |  |
| [source_file](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/source_file) |  |
| [connection_file](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/connection_file) |获取连接文件。|
| [is_new](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_new) |  |
| [name](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/name) |  |
| [keep_alive](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/keep_alive) |  |
| [refresh_internal](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/refresh_internal) |  |
| [connection_description](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/connection_description) |  |
| [is_deleted](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_deleted) |  |
| [credentials_method_type](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/credentials_method_type) |  |
| [credentials](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/credentials) |  |
| [background_refresh](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/background_refresh) |  |
| [parameters](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/parameters) |  |
| [command](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/command) |  |
| [command_type](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/command_type) |  |
| [connection_string](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/connection_string) |  |
| [second_command](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/second_command) |  |
| [is_xml](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_xml) |如果 Web 查询源是 XML（与 HTML 相对）则为 true，否则为 false。|
| [is_xl97](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_xl97) |此标志是为了向后兼容旧的现有电子表格文件而存在的，并且设置为<br/>如果此 Web 查询是在 Microsoft Excel 97 中创建的，则为 true。<br/>这是一个可选属性，可以忽略。|
| [is_xl2000](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_xl2000) |此标志是为了向后兼容旧的现有电子表格文件而存在的，并且设置为<br/>如果此 Web 查询在电子表格应用程序中刷新的时间大于或等于<br/>至 Microsoft Excel 2000。<br/>这是一个可选属性，可以忽略。|
| [url](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/url) |用于刷新外部数据的 URL。|
| [is_text_dates](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_text_dates) |标志指示是否应将日期作为文本而不是日期导入工作表中的单元格。|
| [is_xml_source_data](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_xml_source_data) |标志表明应该导入 XML 源数据而不是 HTML 表本身。|
| [post](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/post) |返回或设置用于将数据输入到 Web 服务器的 post 方法的字符串<br/>从网络查询返回数据。|
| [is_parse_pre](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_parse_pre) |指示网页中 HTML PRE 标签内包含的数据是否<br/>当您将页面导入查询表时，解析为列。|
| [is_html_tables](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_html_tables) |标志指示网络查询是否仅对 HTML 表起作用。|
| [html_format](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/html_format) |将 Web 查询数据导入时如何处理 HTML 源的格式<br/>工作表。当 sourceData 为 True 时相关。|
| [is_same_settings](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_same_settings) |指示是否使用相同的宽度设置解析 PRE 块内的所有表的标志<br/>作为第一行。|
| [edit_web_page](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/edit_web_page) |显示 Web 查询数据的面向用户的网页的 URL。此 URL 会持久保存<br/>在 sourceData="true" 和 url 已被重定向以引用 XML 文件的情况下。<br/>然后，可以在 UI 中显示面向用户的页面，并且可以检索 XML 数据<br/>幕后。|
| [edit_page](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/edit_page) |显示 Web 查询数据的面向用户的网页的 URL。此 URL 会持久保存<br/>在 sourceData="true" 和 url 已被重定向以引用 XML 文件的情况下。<br/>然后，可以在 UI 中显示面向用户的页面，并且可以检索 XML 数据<br/>幕后。|
| [is_consecutive](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection/is_consecutive) |标志指示连续的分隔符是否应被视为一个分隔符。|



### 也可以看看
* 模块[`aspose.cells.externalconnections`](..)
* 类 [`WebQueryConnection`](/cells/python-net/zh/aspose.cells.externalconnections/webqueryconnection)
