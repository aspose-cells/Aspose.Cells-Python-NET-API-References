---
title: FontConfigs класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 670
url: /ru/aspose.cells/fontconfigs/
is_root: false
---
##  FontConfigs класс
Задает настройки шрифта



Тип FontConfigs предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/fontconfigs/__init__/#) | Создает новый экземпляр FontConfigs|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [default_font_name](/cells/python-net/ru/aspose.cells/fontconfigs/default_font_name) | Получает или задает имя шрифта по умолчанию.|
| [prefer_system_font_substitutes](/cells/python-net/ru/aspose.cells/fontconfigs/prefer_system_font_substitutes) | Укажите, следует ли сначала использовать системные заменители шрифтов или нет, если шрифт не представлен и заменитель этого шрифта не установлен.<br/>Например, в Ubuntu шрифт «Arial» обычно заменяется на «Liberation Sans».<br/> Значение по умолчанию — false.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/ru/aspose.cells/fontconfigs/is_font_available/#str) | Укажите, доступен ли шрифт.|
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/ru/aspose.cells/fontconfigs/get_font_file_data_info/#str-bool-bool-bool) | Получить информацию о данных файла шрифта.|
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/ru/aspose.cells/fontconfigs/set_font_substitutes/#str-list) | Заменяющие названия шрифтов для заданного исходного названия шрифта.|
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/ru/aspose.cells/fontconfigs/get_font_substitutes/#str) |Возвращает массив, содержащий имена заменителей шрифтов, которые будут использоваться, если исходный шрифт не представлен.|
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/ru/aspose.cells/fontconfigs/set_font_folder/#str-bool) | Устанавливает папку шрифтов|
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/ru/aspose.cells/fontconfigs/set_font_folders/#list-bool) | Устанавливает папки шрифтов|
| [`set_font_sources(, sources)`](/cells/python-net/ru/aspose.cells/fontconfigs/set_font_sources/#list) |  |
| [`get_font_sources()`](/cells/python-net/ru/aspose.cells/fontconfigs/get_font_sources/#) | Получает копию массива, содержащего список источников.|



###  Смотрите также
* модуль [`aspose.cells`](..)
