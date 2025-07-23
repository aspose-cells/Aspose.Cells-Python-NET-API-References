---
title: WebQueryConnection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells.externalconnections/webqueryconnection/
is_root: false
---
##  WebQueryConnection класс
 Задаёт свойства источника веб-запроса. Веб-запрос будет извлекать данные из таблиц HTML.
 и также может предоставить параметры HTTP "Get", которые будут обработаны веб-сервером при создании HTML
включая параметры и элементы параметров.



**Наследование:** [`WebQueryConnection`](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection)



Тип WebQueryConnection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [id](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/id) |  |
| [connection_id](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/connection_id) |  |
| [class_type](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/class_type) | Получает тип этого объекта ExternalConnection.|
| [power_query_formula](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/power_query_formula) |  |
| [type](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/type) |  |
| [source_type](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/source_type) |  |
| [sso_id](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/sso_id) |  |
| [save_password](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/save_password) |  |
| [save_data](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/save_data) |  |
| [refresh_on_load](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/refresh_on_load) |  |
| [reconnection_method_type](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/reconnection_method_type) |  |
| [reconnection_method](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/reconnection_method) |  |
| [only_use_connection_file](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/only_use_connection_file) |  |
| [odc_file](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/odc_file) |  |
| [source_file](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/source_file) |  |
| [connection_file](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/connection_file) | Получает файл подключения.|
| [is_new](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_new) |  |
| [name](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/name) |  |
| [keep_alive](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/keep_alive) |  |
| [refresh_internal](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/refresh_internal) |  |
| [connection_description](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/connection_description) |  |
| [is_deleted](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_deleted) |  |
| [credentials_method_type](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/credentials_method_type) |  |
| [credentials](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/credentials) |  |
| [background_refresh](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/background_refresh) |  |
| [parameters](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/parameters) |  |
| [command](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/command) |  |
| [command_type](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/command_type) |  |
| [connection_string](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/connection_string) |  |
| [second_command](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/second_command) |  |
| [is_xml](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_xml) | true, если источником веб-запроса является XML (в отличие от HTML), в противном случае false.|
| [is_xl97](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_xl97) | Этот флаг существует для обратной совместимости со старыми существующими файлами электронных таблиц и устанавливается<br/>значение true, если этот веб-запрос был создан в Microsoft Excel 97.<br/> Это необязательный атрибут, который можно игнорировать.|
| [is_xl2000](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_xl2000) | Этот флаг существует для обратной совместимости со старыми существующими файлами электронных таблиц и устанавливается<br/>значение true, если этот веб-запрос был обновлен в приложении для электронных таблиц, которое новее или равно<br/>на Microsoft Excel 2000.<br/> Это необязательный атрибут, который можно игнорировать.|
| [url](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/url) | URL-адрес для обновления внешних данных.|
| [is_text_dates](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_text_dates) | Флаг, указывающий, следует ли импортировать даты в ячейки рабочего листа как текст, а не как даты.|
| [is_xml_source_data](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_xml_source_data) |Флаг, указывающий, что следует импортировать исходные данные XML вместо самой таблицы HTML.|
| [post](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/post) | Возвращает или задает строку, используемую с методом post для ввода данных на веб-сервер.<br/> для возврата данных из веб-запроса.|
| [is_parse_pre](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_parse_pre) | Флаг, указывающий, содержатся ли данные, содержащиеся в тегах PRE HTML на веб-странице<br/> разбивается на столбцы при импорте страницы в таблицу запроса.|
| [is_html_tables](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_html_tables) | Флаг, указывающий, должны ли веб-запросы работать только с таблицами HTML.|
| [html_format](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/html_format) | Как обрабатывать форматирование из источника HTML при переносе данных веб-запроса в<br/> Рабочий лист. Актуально, когда sourceData имеет значение True.|
| [is_same_settings](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_same_settings) | Флаг, указывающий, следует ли анализировать все таблицы внутри блока PRE с одинаковыми настройками ширины.<br/> как в первом ряду.|
| [edit_web_page](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/edit_web_page) | URL-адрес веб-страницы, доступной пользователю, с данными веб-запроса. Этот URL-адрес сохраняется.<br/>в случае, если sourceData="true" и url был перенаправлен для ссылки на XML-файл.<br/>Затем в пользовательском интерфейсе можно отобразить страницу, на которую пользователь смотрит, и извлечь XML-данные.<br/> за кулисами.|
| [edit_page](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/edit_page) | URL-адрес веб-страницы, доступной пользователю, с данными веб-запроса. Этот URL-адрес сохраняется.<br/>в случае, если sourceData="true" и url был перенаправлен для ссылки на XML-файл.<br/>Затем в пользовательском интерфейсе можно отобразить страницу, на которую пользователь смотрит, и извлечь XML-данные.<br/> за кулисами.|
| [is_consecutive](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection/is_consecutive) | Флаг, указывающий, следует ли рассматривать последовательные разделители как один разделитель.|



###  Смотрите также
* модуль [`aspose.cells.externalconnections`](..)
* класс [`WebQueryConnection`](/cells/python-net/ru/aspose.cells.externalconnections/webqueryconnection)
