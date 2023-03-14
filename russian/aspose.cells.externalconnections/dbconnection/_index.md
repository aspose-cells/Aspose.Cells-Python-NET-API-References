---
title: DBConnection класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 30
url: /ru/aspose.cells.externalconnections/dbconnection/
is_root: false
---
##  DBConnection класс
Задает все свойства, связанные с подключением к внешним данным ODBC или OLE DB.



**Наследование:** [DBConnection](/cells/python-net/aspose.cells.externalconnections/dbconnection) → 
[ExternalConnection](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection)



Тип DBConnection предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [id](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/id) | Получает идентификатор соединения.|
| [power_query_formula](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/power_query_formula) | Получает определение формулы мощного запроса.|
| [type](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/type) | Получает или задает тип источника данных внешнего подключения.|
| [source_file](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/source_file) | Используется, когда внешний источник данных основан на файлах. При подключении к таким данным<br/> источник не работает, приложение для работы с электронными таблицами пытается напрямую подключиться к этому файлу. Может быть<br/> выраженный в URI или системной нотации пути к файлу.|
| [sso_id](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/sso_id) | Идентификатор для единого входа (SSO), используемый для аутентификации между промежуточным<br/> сервер электронной таблицыML и внешний источник данных.|
| [save_password](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/save_password) | Истинно, если пароль должен быть сохранен как часть строки подключения; в противном случае Ложь.|
| [save_data](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/save_data) | Истинно, если внешние данные, полученные через соединение для заполнения таблицы, должны быть сохранены.<br/> с рабочей тетрадью; в противном случае ложно.|
| [refresh_on_load](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/refresh_on_load) | Истинно, если это соединение должно обновляться при открытии файла; в противном случае ложно.|
| [reconnection_method_type](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/reconnection_method_type) | Указывает, что должно делать приложение для работы с электронными таблицами при сбое подключения.<br/>Значение по умолчанию — ReConnectionMethodType.Required.|
| [reconnection_method](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/reconnection_method) | Указывает, что должно делать приложение для работы с электронными таблицами при сбое подключения.<br/>Значение по умолчанию — ReConnectionMethodType.Required.|
| [only_use_connection_file](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/only_use_connection_file) | Указывает, должно ли приложение для работы с электронными таблицами всегда и только использовать<br/> информация о подключении во внешнем файле подключения, указанном атрибутом odcFile<br/> при обновлении соединения. Если false, то приложение для работы с электронными таблицами<br/> должен следовать процедуре, указанной атрибутом reconnectionMethod|
| [odc_file](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/odc_file) | Указывает полный путь к внешнему файлу подключения, из которого это подключение было<br/> созданный. Если во время попытки обновления данных происходит сбой подключения и reconnectionMethod=1,<br/> затем приложение для работы с электронными таблицами попытается снова использовать информацию из файла внешнего подключения.<br/> вместо объекта подключения, встроенного в книгу.|
| [is_new](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/is_new) | Истинно, если соединение не было обновлено в первый раз; в противном случае ложно.<br/> Это состояние может произойти, когда пользователь сохраняет файл до завершения запроса.|
| [name](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/name) | Задает имя соединения. Каждое соединение должно иметь уникальное имя.|
| [keep_alive](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/keep_alive) | Истинно, когда приложение для работы с электронными таблицами должно прилагать усилия для поддержания соединения.<br/>открыть. При значении false приложение должно закрыть соединение после получения<br/> информация.|
| [refresh_internal](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/refresh_internal) | Указывает количество минут между автоматическими обновлениями соединения.|
| [connection_id](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/connection_id) | Указывает уникальный идентификатор этого соединения.|
| [connection_description](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/connection_description) | Указывает описание пользователя для этого соединения.|
| [is_deleted](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/is_deleted) |Указывает, было ли удалено связанное подключение к книге. верно, если<br/> соединение было удалено; в противном случае ложно.|
| [credentials_method_type](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/credentials_method_type) | Указывает метод проверки подлинности, который будет использоваться при установлении (или повторном установлении) соединения.|
| [credentials](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/credentials) | Указывает метод проверки подлинности, который будет использоваться при установлении (или повторном установлении) соединения.|
| [background_refresh](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/background_refresh) | Указывает, можно ли обновить соединение в фоновом режиме (асинхронно).<br/>Значение true, если предпочтительное использование соединения — асинхронное обновление в фоновом режиме;<br/> false, если предпочтительным использованием соединения является синхронное обновление на переднем плане.|
| [parameters](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/parameters) | Получает [ConnectionParameterCollection](/cells/python-net/ru/aspose.cells.externalconnections/connectionparametercollection) для ODBC или веб-запроса.|
| [connection_info](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/connection_info) | Строка информации о подключении используется для связи с источником данных OLE DB или ODBC.|
| [command_type](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/command_type) | Указывает тип команды OLE DB.<br/>1. Запрос указывает имя куба<br/>2. Запрос указывает оператор SQL<br/>3. Запрос указывает имя таблицы<br/>4. Запрос указывает, что была предоставлена информация по умолчанию, а как ее интерпретировать, зависит от провайдера.<br/> 5. Запрос относится к веб-поставщику данных списка.|
| [command](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/command) | Строка, содержащая команду базы данных для передачи поставщику данных API, который<br/> взаимодействовать с внешним источником для получения данных|
| [sever_command](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection/sever_command) |Задает вторую текстовую строку команды, которая сохраняется при использовании сводной таблицы на основе сервера.<br/> поля страницы используются.<br/> Для соединений ODBC serverCommand обычно является более широким запросом, чем команда (не<br/>предложение WHERE присутствует в первом). Основываясь на этих двух командах (Command и ServerCommand),<br/> Пользовательский интерфейс параметров может быть заполнен, и могут быть созданы параметризованные запросы.|



###  Смотрите также
* модуль [aspose.cells.externalconnections](..)
* класс [ConnectionParameterCollection](/cells/python-net/ru/aspose.cells.externalconnections/connectionparametercollection)
* класс [DBConnection](/cells/python-net/ru/aspose.cells.externalconnections/dbconnection)
* класс [ExternalConnection](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection)
