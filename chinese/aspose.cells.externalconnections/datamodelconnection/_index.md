---
title: DataModelConnection类
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 40
url: /zh/aspose.cells.externalconnections/datamodelconnection/
is_root: false
---
## DataModelConnection类
指定数据模型连接



**继承：** [DataModelConnection](/cells/python-net/aspose.cells.externalconnections/datamodelconnection) → 
[ExternalConnection](/cells/python-net/zh/aspose.cells.externalconnections/externalconnection)



DataModelConnection 类型公开了以下成员：

### 特性
|属性|描述|
| :- | :- |
| [id](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/id) |获取连接的 ID。|
| [power_query_formula](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/power_query_formula) |获取幂查询公式的定义。|
| [type](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/type) |获取或设置外部连接数据源类型。|
| [source_file](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/source_file) |当外部数据源是基于文件的时使用。当连接到这样的数据时<br/>source 失败，电子表格应用程序尝试直接连接到该文件。或许<br/>以 URI 或系统特定的文件路径表示法表示。|
| [sso_id](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/sso_id) |用于中间体之间身份验证的单点登录 (SSO) 标识符<br/>spreadsheetML 服务器和外部数据源。|
| [save_password](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/save_password) |如果要将密码保存为连接字符串的一部分，则为真；否则为真。否则，假。|
| [save_data](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/save_data) |如果要保存通过连接获取的用于填充表的外部数据，则为真<br/>与工作簿；否则，假的。|
| [refresh_on_load](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/refresh_on_load) |如果在打开文件时应刷新此连接，则为真；否则为真。否则，假的。|
| [reconnection_method_type](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/reconnection_method_type) |指定当连接失败时电子表格应用程序应该做什么。<br/>默认值为 ReConnectionMethodType.Required。|
| [reconnection_method](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/reconnection_method) |指定当连接失败时电子表格应用程序应该做什么。<br/>默认值为 ReConnectionMethodType.Required。|
| [only_use_connection_file](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/only_use_connection_file) |指示电子表格应用程序是否应始终且仅使用<br/>odcFile 属性指示的外部连接文件中的连接信息<br/>刷新连接时。如果为假，则电子表格应用程序<br/>应遵循 reconnectionMethod 属性指示的过程|
| [odc_file](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/odc_file) |指定此连接来自的外部连接文件的完整路径<br/>创建。如果在尝试刷新数据时连接失败，并且 reconnectionMethod=1，<br/>然后电子表格应用程序将使用来自外部连接文件的信息重试<br/>而不是工作簿中嵌入的连接对象。|
| [is_new](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/is_new) |如果第一次没有刷新连接则为真；否则，假的。<br/>当用户在查询完成返回之前保存文件时，就会发生这种状态。|
| [name](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/name) |指定连接的名称。每个连接都必须有一个唯一的名称。|
| [keep_alive](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/keep_alive) |当电子表格应用程序应努力保持连接时为真<br/>打开。为 false 时，应用程序应在检索到<br/>信息。|
| [refresh_internal](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/refresh_internal) |指定连接自动刷新之间的分钟数。|
| [connection_id](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/connection_id) |指定此连接的唯一标识符。|
| [connection_description](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/connection_description) |指定此连接的用户描述|
| [is_deleted](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/is_deleted) |指示关联的工作簿连接是否已删除。如果<br/>连接已被删除；否则，假的。|
| [credentials_method_type](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/credentials_method_type) |指定建立（或重新建立）连接时要使用的身份验证方法。|
| [credentials](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/credentials) |指定建立（或重新建立）连接时要使用的身份验证方法。|
| [background_refresh](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/background_refresh) |指示是否可以在后台（异步）刷新连接。<br/>如果连接的首选用法是在后台异步刷新，则为真；<br/>如果连接的首选用法是在前台同步刷新，则为 false。|
| [parameters](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection/parameters) |为 ODBC 或 Web 查询获取 [ConnectionParameterCollection](/cells/python-net/zh/aspose.cells.externalconnections/connectionparametercollection)。|



### 也可以看看
* 模块 [aspose.cells.externalconnections](..)
* 类 [ConnectionParameterCollection](/cells/python-net/zh/aspose.cells.externalconnections/connectionparametercollection)
* 类 [DataModelConnection](/cells/python-net/zh/aspose.cells.externalconnections/datamodelconnection)
* 类 [ExternalConnection](/cells/python-net/zh/aspose.cells.externalconnections/externalconnection)
