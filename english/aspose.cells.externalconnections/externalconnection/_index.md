---
title: ExternalConnection class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.cells.externalconnections/externalconnection/
is_root: false
---

## ExternalConnection class

Specifies an external data connection



The ExternalConnection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [id](/cells/python-net/aspose.cells.externalconnections/externalconnection/id) | Gets the id of the connection. |
| [connection_id](/cells/python-net/aspose.cells.externalconnections/externalconnection/connection_id) | Specifies The unique identifier of this connection. |
| [class_type](/cells/python-net/aspose.cells.externalconnections/externalconnection/class_type) | Gets the type of this [`ExternalConnection`](/cells/python-net/aspose.cells.externalconnections/externalconnection) object. |
| [power_query_formula](/cells/python-net/aspose.cells.externalconnections/externalconnection/power_query_formula) | Gets the definition of power query formula. |
| [type](/cells/python-net/aspose.cells.externalconnections/externalconnection/type) | Gets or Sets the external connection DataSource type. |
| [source_type](/cells/python-net/aspose.cells.externalconnections/externalconnection/source_type) | Gets or Sets the external connection DataSource type. |
| [sso_id](/cells/python-net/aspose.cells.externalconnections/externalconnection/sso_id) | Identifier for Single Sign On (SSO) used for authentication between an intermediate <br/>spreadsheetML server and the external data source. |
| [save_password](/cells/python-net/aspose.cells.externalconnections/externalconnection/save_password) | True if the password is to be saved as part of the connection string; otherwise, False. |
| [save_data](/cells/python-net/aspose.cells.externalconnections/externalconnection/save_data) | True if the external data fetched over the connection to populate a table is to be saved<br/>with the workbook; otherwise, false. |
| [refresh_on_load](/cells/python-net/aspose.cells.externalconnections/externalconnection/refresh_on_load) | True if this connection should be refreshed when opening the file; otherwise, false. |
| [reconnection_method_type](/cells/python-net/aspose.cells.externalconnections/externalconnection/reconnection_method_type) | Specifies what the spreadsheet application should do when a connection fails.<br/>The default value is ReConnectionMethodType.Required. |
| [reconnection_method](/cells/python-net/aspose.cells.externalconnections/externalconnection/reconnection_method) | Specifies what the spreadsheet application should do when a connection fails.<br/>The default value is ReConnectionMethodType.Required. |
| [only_use_connection_file](/cells/python-net/aspose.cells.externalconnections/externalconnection/only_use_connection_file) | Indicates whether the spreadsheet application should always and only use the <br/>connection information in the external connection file indicated by the odcFile attribute <br/>when the connection is refreshed.  If false, then the spreadsheet application <br/>should follow the procedure indicated by the reconnectionMethod attribute |
| [odc_file](/cells/python-net/aspose.cells.externalconnections/externalconnection/odc_file) | Specifies the full path to external connection file from which this connection was <br/>created. If a connection fails during an attempt to refresh data, and reconnectionMethod=1, <br/>then the spreadsheet application will try again using information from the external connection file <br/>instead of the connection object embedded within the workbook. |
| [source_file](/cells/python-net/aspose.cells.externalconnections/externalconnection/source_file) | Used when the external data source is file-based. <br/>When a connection to such a data source fails, the spreadsheet application attempts to connect directly to this file. May be <br/>expressed in URI or system-specific file path notation. |
| [connection_file](/cells/python-net/aspose.cells.externalconnections/externalconnection/connection_file) | Gets the connection file. |
| [is_new](/cells/python-net/aspose.cells.externalconnections/externalconnection/is_new) | True if the connection has not been refreshed for the first time; otherwise, false. <br/>This state can happen when the user saves the file before a query has finished returning. |
| [name](/cells/python-net/aspose.cells.externalconnections/externalconnection/name) | Specifies the name of the connection. Each connection must have a unique name. |
| [keep_alive](/cells/python-net/aspose.cells.externalconnections/externalconnection/keep_alive) | True when the spreadsheet application should make efforts to keep the connection <br/>open. When false, the application should close the connection after retrieving the <br/>information. |
| [refresh_internal](/cells/python-net/aspose.cells.externalconnections/externalconnection/refresh_internal) | Specifies the number of minutes between automatic refreshes of the connection. |
| [connection_description](/cells/python-net/aspose.cells.externalconnections/externalconnection/connection_description) | Specifies the user description for this connection |
| [is_deleted](/cells/python-net/aspose.cells.externalconnections/externalconnection/is_deleted) | Indicates whether the associated workbook connection has been deleted.  true if the<br/>connection has been deleted; otherwise, false. |
| [credentials_method_type](/cells/python-net/aspose.cells.externalconnections/externalconnection/credentials_method_type) | Specifies the authentication method to be used when establishing (or re-establishing) the connection. |
| [credentials](/cells/python-net/aspose.cells.externalconnections/externalconnection/credentials) | Specifies the authentication method to be used when establishing (or re-establishing) the connection. |
| [background_refresh](/cells/python-net/aspose.cells.externalconnections/externalconnection/background_refresh) | Indicates whether the connection can be refreshed in the background (asynchronously). <br/>true if preferred usage of the connection is to refresh asynchronously in the background; <br/>false if preferred usage of the connection is to refresh synchronously in the foreground. |
| [parameters](/cells/python-net/aspose.cells.externalconnections/externalconnection/parameters) | Gets [`ConnectionParameterCollection`](/cells/python-net/aspose.cells.externalconnections/connectionparametercollection) for an ODBC or web query. |
| [command](/cells/python-net/aspose.cells.externalconnections/externalconnection/command) | The string containing the database command to pass to the data provider API that will <br/>interact with the external source in order to retrieve data |
| [command_type](/cells/python-net/aspose.cells.externalconnections/externalconnection/command_type) | Specifies the OLE DB command type. <br/>1. Query specifies a cube name<br/>2. Query specifies a SQL statement<br/>3. Query specifies a table name<br/>4. Query specifies that default information has been given, and it is up to the provider how to interpret.<br/>5. Query is against a web based List Data Provider. |
| [connection_string](/cells/python-net/aspose.cells.externalconnections/externalconnection/connection_string) | The connection information string is used to make contact with an OLE DB or ODBC data source. |
| [second_command](/cells/python-net/aspose.cells.externalconnections/externalconnection/second_command) | Specifies a second command text string that is persisted when PivotTable server-based <br/>page fields are in use. <br/>For ODBC connections, serverCommand is usually a broader query than command (no <br/>WHERE clause is present in the former). Based on these 2 commands(Command and ServerCommand),<br/>parameter UI can be populated and parameterized queries can be constructed |



### See Also
* module [`aspose.cells.externalconnections`](..)
* class [`ConnectionParameterCollection`](/cells/python-net/aspose.cells.externalconnections/connectionparametercollection)
* class [`ExternalConnection`](/cells/python-net/aspose.cells.externalconnections/externalconnection)
