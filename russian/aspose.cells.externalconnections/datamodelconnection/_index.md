---
title: DataModelConnection класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 40
url: /ru/aspose.cells.externalconnections/datamodelconnection/
is_root: false
---
##  DataModelConnection класс
Указывает подключение к модели данных



**Наследование:** [DataModelConnection](/cells/python-net/aspose.cells.externalconnections/datamodelconnection) → 
[ExternalConnection](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection)



Тип DataModelConnection предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [id](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/id) | Получает идентификатор соединения.|
| [power_query_formula](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/power_query_formula) | Получает определение формулы мощного запроса.|
| [type](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/type) | Получает или задает тип источника данных внешнего подключения.|
| [source_file](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/source_file) | Используется, когда внешний источник данных основан на файлах. При подключении к таким данным<br/> источник не работает, приложение для работы с электронными таблицами пытается напрямую подключиться к этому файлу. Может быть<br/> выраженный в URI или системной нотации пути к файлу.|
| [sso_id](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/sso_id) | Идентификатор для единого входа (SSO), используемый для аутентификации между промежуточным<br/> сервер электронной таблицыML и внешний источник данных.|
| [save_password](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/save_password) | Истинно, если пароль должен быть сохранен как часть строки подключения; в противном случае Ложь.|
| [save_data](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/save_data) | Истинно, если внешние данные, полученные через соединение для заполнения таблицы, должны быть сохранены.<br/> с рабочей тетрадью; в противном случае ложно.|
| [refresh_on_load](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/refresh_on_load) | Истинно, если это соединение должно обновляться при открытии файла; в противном случае ложно.|
| [reconnection_method_type](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/reconnection_method_type) | Указывает, что должно делать приложение для работы с электронными таблицами при сбое подключения.<br/>Значение по умолчанию — ReConnectionMethodType.Required.|
| [reconnection_method](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/reconnection_method) | Указывает, что должно делать приложение для работы с электронными таблицами при сбое подключения.<br/>Значение по умолчанию — ReConnectionMethodType.Required.|
| [only_use_connection_file](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/only_use_connection_file) | Указывает, должно ли приложение для работы с электронными таблицами всегда и только использовать<br/> информация о подключении во внешнем файле подключения, указанном атрибутом odcFile<br/> при обновлении соединения. Если false, то приложение для работы с электронными таблицами<br/> должен следовать процедуре, указанной атрибутом reconnectionMethod|
| [odc_file](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/odc_file) | Указывает полный путь к внешнему файлу подключения, из которого это подключение было<br/> созданный. Если во время попытки обновления данных происходит сбой подключения и reconnectionMethod=1,<br/> затем приложение для работы с электронными таблицами попытается снова использовать информацию из файла внешнего подключения.<br/> вместо объекта подключения, встроенного в книгу.|
| [is_new](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/is_new) | Истинно, если соединение не было обновлено в первый раз; в противном случае ложно.<br/> Это состояние может произойти, когда пользователь сохраняет файл до завершения запроса.|
| [name](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/name) | Задает имя соединения. Каждое соединение должно иметь уникальное имя.|
| [keep_alive](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/keep_alive) | Истинно, когда приложение для работы с электронными таблицами должно прилагать усилия для поддержания соединения.<br/>открыть. При значении false приложение должно закрыть соединение после получения<br/> информация.|
| [refresh_internal](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/refresh_internal) | Указывает количество минут между автоматическими обновлениями соединения.|
| [connection_id](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/connection_id) | Указывает уникальный идентификатор этого соединения.|
| [connection_description](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/connection_description) | Указывает описание пользователя для этого соединения.|
| [is_deleted](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/is_deleted) |Указывает, было ли удалено связанное подключение к книге. верно, если<br/> соединение было удалено; в противном случае ложно.|
| [credentials_method_type](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/credentials_method_type) | Указывает метод проверки подлинности, который будет использоваться при установлении (или повторном установлении) соединения.|
| [credentials](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/credentials) | Указывает метод проверки подлинности, который будет использоваться при установлении (или повторном установлении) соединения.|
| [background_refresh](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/background_refresh) | Указывает, можно ли обновить соединение в фоновом режиме (асинхронно).<br/>Значение true, если предпочтительное использование соединения — асинхронное обновление в фоновом режиме;<br/> false, если предпочтительным использованием соединения является синхронное обновление на переднем плане.|
| [parameters](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection/parameters) | Получает [ConnectionParameterCollection](/cells/python-net/ru/aspose.cells.externalconnections/connectionparametercollection) для ODBC или веб-запроса.|



###  Смотрите также
* модуль [aspose.cells.externalconnections](..)
* класс [ConnectionParameterCollection](/cells/python-net/ru/aspose.cells.externalconnections/connectionparametercollection)
* класс [DataModelConnection](/cells/python-net/ru/aspose.cells.externalconnections/datamodelconnection)
* класс [ExternalConnection](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection)
