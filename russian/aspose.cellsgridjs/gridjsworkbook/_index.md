---
title: GridJsWorkbook класс
second_title: Aspose.Cells.GridJs for Python via .NET API
description:
type: docs
weight: 60
url: /ru/aspose.cellsgridjs/gridjsworkbook/
is_root: false
---
##  GridJsWorkbook класс

Представляет основной входной класс GridJs.



Тип GridJsWorkbook предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/__init__/#) |Создает новый экземпляр GridJsWorkbook.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [settings](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/settings) | Представляет параметры книги.|
| [cache_imp](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/cache_imp) | Пользовательская реализация хранилища кеша. Если вы хотите хранить кеш в потоковом режиме, вам необходимо его установить и реализовать.|
| [calculate_engine](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/calculate_engine) | Пользовательская реализация механизма вычислений. Если вы хотите выполнить собственный расчет, вам необходимо его установить и реализовать.|


###  Методы
| Метод| Описание|
| :- | :- |
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-str-str) | Импортирует файл Excel из пути к файлу и открытого пароля.|
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-str) | Импортирует файл Excel из пути к файлу.|
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str) | Импортирует файл Excel из пути к файлу.|
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str) | Импортирует файл Excel из файлового потока с форматом загрузки и открытым паролем.|
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat) | Импортирует файл Excel из файлового потока.|
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str) | Импортирует файл Excel из файлового потока с форматом загрузки и открытым паролем.|
| [import_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat) | Импортирует файл Excel из потока файлов с форматом загрузки.|
| [export_to_json](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/export_to_json/#str) | Получает строку формата JSON из данных памяти с указанным именем файла.|
| [export_to_json](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/export_to_json/#) | Получает строку формата JSON пустого файла электронной таблицы по умолчанию.|
| [save_to_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_excel_file/#io.RawIOBase) | Сохраняет данные памяти в файл на основе исходного формата файла.|
| [save_to_excel_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_excel_file/#str) |Сохраняет данные памяти в пути к файлу. Если файл имеет расширение, формат сохранения зависит от расширения файла.|
| [save_to_pdf](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_pdf/#str) | Сохраняет данные памяти по пути к файлу, формат сохранения — pdf.|
| [save_to_pdf](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_pdf/#io.RawIOBase) | Сохраняет данные памяти в файл, формат сохранения — pdf.|
| [save_to_xlsx](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_xlsx/#str) | Сохраняет данные памяти по пути к файлу, формат сохранения — xlsx.|
| [save_to_xlsx](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_xlsx/#io.RawIOBase) | Сохраняет данные памяти в файл, формат сохранения — xlsx.|
| [save_to_html](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_html/#str) | Сохраняет данные памяти по пути к файлу, формат сохранения — html.|
| [save_to_html](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_html/#io.RawIOBase) | Сохраняет данные памяти в файл, формат сохранения — html.|
| [get_json_str_by_uid](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/get_json_str_by_uid/#str-str) | Получает строку формата JSON из файлового кэша по указанному уникальному идентификатору.|
| [get_uid_for_file](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/get_uid_for_file/#str) | Получает уникальный идентификатор файлового кэша.|
| [import_excel_file_from_json](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file_from_json/#str) | Импортирует файл Excel из строки формата JSON.|
| [merge_excel_file_from_json](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/merge_excel_file_from_json/#str-str) | Применяет пакетное обновление к данным памяти.|
| [save_to_cache_with_file_name](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/save_to_cache_with_file_name/#str-str-str) | Сохраняет данные памяти в файл кэша с указанным именем файла, а также устанавливает пароль открытия, формат сохранения основан на расширении имени файла.|
| [get_image_stream](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/get_image_stream/#str-str) | Получить поток изображения из данных памяти.|
| [get_ole](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/get_ole/#str-str-int-any) |Получает данные массива байтов внедренного объекта ole.|
| [update_cell](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/update_cell/#str-str) | Применяет операцию обновления.|
| [insert_image](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/insert_image/#str-str-io.RawIOBase-str) |
<br/>или /ячейки/
<br/>Вставляет sh/cells/n, p.type является одним из AutoShapeType |
| [copy_image_or_shape](//cells/ython-net/aspose.cellsgridjs/gridjsworkbook/copy_image_or_shape/#str-str) | Копирует изображение или фигуру.|
| [error_json](/gr/cells/hon-net/aspose.cellsgridjs/gridjsworkbook/error_json/#str) | Получает строку сообщения об ошибке в формате JSON.|
|  [get_grid_load_format/cells/s/python-net/aspose.cellsgridjs/gridjsworkbook/get_grid_load_format/#str)| Получает формат загрузки по расширению файла|
| [get_image_url](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/get_image_url/#str-str-str) | Получает URL-адрес изображения.|
| [set_image_url_base](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook/set_image_url_base/#str) |  |



###  Смотрите также
* модуль [`aspose.cellsgridjs`](..)
