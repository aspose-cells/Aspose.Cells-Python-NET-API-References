---
title: Workbook класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 1590
url: /ru/aspose.cells/workbook/
is_root: false
---
##  Workbook класс
Представляет корневой объект для создания электронной таблицы Excel.



Тип Workbook предоставляет следующие члены:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [Workbook()](/cells/python-net/ru/aspose.cells/workbook/__init__/#) | Инициализирует новый экземпляр класса [Workbook](/cells/python-net/ru/aspose.cells/workbook).|
| [Workbook(file_format_type)](/cells/python-net/ru/aspose.cells/workbook/__init__/#FileFormatType) | Инициализирует новый экземпляр класса [Workbook](/cells/python-net/ru/aspose.cells/workbook).|
| [Workbook(file)](/cells/python-net/ru/aspose.cells/workbook/__init__/#str) | Инициализирует новый экземпляр класса [Workbook](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.|
| [Workbook(stream)](/cells/python-net/ru/aspose.cells/workbook/__init__/#io.RawIOBase) | Инициализирует новый экземпляр класса [Workbook](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.|
| [Workbook(file, load_options)](/cells/python-net/ru/aspose.cells/workbook/__init__/#str-LoadOptions) | Инициализирует новый экземпляр класса [Workbook](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.|
| [Workbook(stream, load_options)](/cells/python-net/ru/aspose.cells/workbook/__init__/#io.RawIOBase-LoadOptions) | Инициализирует новый экземпляр класса [Workbook](/cells/python-net/ru/aspose.cells/workbook) и открытый поток.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [settings](/cells/python-net/ru/aspose.cells/workbook/settings) | Представляет параметры книги.|
| [worksheets](/cells/python-net/ru/aspose.cells/workbook/worksheets) | Получает коллекцию [WorksheetCollection](/cells/python-net/ru/aspose.cells/worksheetcollection) в электронной таблице.|
| [is_licensed](/cells/python-net/ru/aspose.cells/workbook/is_licensed) | Указывает, установлена ли лицензия.|
| [colors](/cells/python-net/ru/aspose.cells/workbook/colors) | Возвращает цвета в палитре электронной таблицы.|
| [count_of_styles_in_pool](/cells/python-net/ru/aspose.cells/workbook/count_of_styles_in_pool) | Получает количество стилей в пуле стилей.|
| [default_style](/cells/python-net/ru/aspose.cells/workbook/default_style) | Получает или задает объект книги по умолчанию [Style](/cells/python-net/ru/aspose.cells/style).|
| [is_digitally_signed](/cells/python-net/ru/aspose.cells/workbook/is_digitally_signed) | Указывает, имеет ли эта электронная таблица цифровую подпись.|
| [is_workbook_protected_with_password](/cells/python-net/ru/aspose.cells/workbook/is_workbook_protected_with_password) | Указывает, защищены ли структура или окно паролем.|
| [vba_project](/cells/python-net/ru/aspose.cells/workbook/vba_project) | Получает [Workbook.vba_project](/cells/python-net/ru/aspose.cells/workbook#vba_project) в электронной таблице.|
| [has_macro](/cells/python-net/ru/aspose.cells/workbook/has_macro) | Указывает, содержит ли эта электронная таблица макрос/VBA.|
| [has_revisions](/cells/python-net/ru/aspose.cells/workbook/has_revisions) | Получает, есть ли в книге какие-либо отслеживаемые изменения|
| [file_name](/cells/python-net/ru/aspose.cells/workbook/file_name) |Получает и задает текущее имя файла.|
| [cells_data_table_factory](/cells/python-net/ru/aspose.cells/workbook/cells_data_table_factory) | Получает фабрику для построения ICellsDataTable из пользовательских объектов.|
| [data_sorter](/cells/python-net/ru/aspose.cells/workbook/data_sorter) | Получает объект DataSorter для сортировки данных.|
| [theme](/cells/python-net/ru/aspose.cells/workbook/theme) | Получает имя темы.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells/workbook/built_in_document_properties) | Возвращает коллекцию [DocumentProperty](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells/workbook/custom_document_properties) | Возвращает коллекцию [DocumentProperty](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все настраиваемые свойства документа электронной таблицы.|
| [file_format](/cells/python-net/ru/aspose.cells/workbook/file_format) | Получает и задает формат файла.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/workbook/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [content_type_properties](/cells/python-net/ru/aspose.cells/workbook/content_type_properties) | Получает список [ContentTypeProperty](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty) объектов в книге.|
| [custom_xml_parts](/cells/python-net/ru/aspose.cells/workbook/custom_xml_parts) | Представляет часть хранилища пользовательских данных XML (пользовательские данные XML в пакете).|
| [data_mashup](/cells/python-net/ru/aspose.cells/workbook/data_mashup) | Получает данные мэшапа.|
| [ribbon_xml](/cells/python-net/ru/aspose.cells/workbook/ribbon_xml) | Получает и задает XML-файл, определяющий пользовательский интерфейс ленты.|
| [absolute_path](/cells/python-net/ru/aspose.cells/workbook/absolute_path) | Получает и задает абсолютный путь к файлу.|
| [data_connections](/cells/python-net/ru/aspose.cells/workbook/data_connections) | Получает коллекцию [ExternalConnection](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection).|


###  Методы
| Метод| Описание|
| :- | :- |
| [save(file_name, save_format)](/cells/python-net/ru/aspose.cells/workbook/save/#str-SaveFormat) | Сохраняет книгу на диск.|
| [save(file_name)](/cells/python-net/ru/aspose.cells/workbook/save/#str) | Сохраните книгу на диск.|
| [save(file_name, save_options)](/cells/python-net/ru/aspose.cells/workbook/save/#str-SaveOptions) | Сохраняет книгу на диск.|
| [save(stream, save_format)](/cells/python-net/ru/aspose.cells/workbook/save/#io.RawIOBase-SaveFormat) | Сохраняет книгу в потоке.|
| [save(stream, save_options)](/cells/python-net/ru/aspose.cells/workbook/save/#io.RawIOBase-SaveOptions) | Сохраняет книгу в потоке.|
| [replace(place_holder, new_value)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-str) | Заменяет значение ячейки новой строкой.|
| [replace(place_holder, new_value)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-int) | Заменяет значение ячейки новым целым числом.|
| [replace(place_holder, new_value)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-float) |Заменяет значение ячейки новым двойным значением.|
| [replace(place_holder, new_values, is_vertical)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значение ячейки новым массивом строк.|
| [replace(place_holder, new_values, is_vertical)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значения ячеек целочисленным массивом.|
| [replace(place_holder, new_values, is_vertical)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значения ячеек двойным массивом.|
| [replace(bool_value, new_value)](/cells/python-net/ru/aspose.cells/workbook/replace/#bool-any) | Заменяет значения ячеек новыми данными.|
| [replace(int_value, new_value)](/cells/python-net/ru/aspose.cells/workbook/replace/#int-any) | Заменяет значения ячеек новыми данными.|
| [replace(place_holder, new_value, options)](/cells/python-net/ru/aspose.cells/workbook/replace/#str-str-ReplaceOptions) | Заменяет значение ячейки новой строкой.|
| [copy(source, copy_options)](/cells/python-net/ru/aspose.cells/workbook/copy/#Workbook-CopyOptions) | Копирует данные из исходного объекта Workbook.|
| [copy(source)](/cells/python-net/ru/aspose.cells/workbook/copy/#Workbook) | Копирует данные из исходного объекта Workbook.|
| [calculate_formula()](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#) | Вычисляет результат формул.|
| [calculate_formula(ignore_error)](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#bool) | Вычисляет результат формул.|
| [calculate_formula(ignore_error, custom_function)](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#bool-ICustomFunction) | Вычисляет результат формул.|
| [calculate_formula(options)](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#CalculationOptions) | Расчетные формулы в этой рабочей тетради.|
| [refresh_dynamic_array_formulas(calculate)](/cells/python-net/ru/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Обновляет формулы динамического массива (перетекает в новый диапазон соседних ячеек в соответствии с текущими данными)<br/> Другие формулы в рабочей книге не будут вычисляться рекурсивно, даже если они использовались формулами динамического массива.|
| [refresh_dynamic_array_formulas(calculate, copts)](/cells/python-net/ru/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-CalculationOptions) | Обновляет формулы динамического массива (перетекает в новый диапазон соседних ячеек в соответствии с текущими данными)|
| [import_xml(url, sheet_name, row, col)](/cells/python-net/ru/aspose.cells/workbook/import_xml/#str-str-int-int) | Импортирует/обновляет файл данных XML в книгу.|
| [import_xml(stream, sheet_name, row, col)](/cells/python-net/ru/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) | Импортирует/обновляет файл данных XML в книгу.|
| [export_xml(map_name, path)](/cells/python-net/ru/aspose.cells/workbook/export_xml/#str-str) | Экспорт данных XML, связанных указанной картой XML.|
| [export_xml(map_name, stream)](/cells/python-net/ru/aspose.cells/workbook/export_xml/#str-io.RawIOBase) | Экспорт XML-данных.|
| [parse_formulas(ignore_error)](/cells/python-net/ru/aspose.cells/workbook/parse_formulas/#bool) | Анализирует все формулы, которые не были проанализированы, когда они были загружены из файла шаблона или установлены в ячейку.|
| [start_access_cache(opts)](/cells/python-net/ru/aspose.cells/workbook/start_access_cache/#AccessCacheOptions) |Запускает сеанс, который использует кэши для доступа к данным.|
| [close_access_cache(opts)](/cells/python-net/ru/aspose.cells/workbook/close_access_cache/#AccessCacheOptions) | Закрывает сеанс, который использует кэши для доступа к данным.|
| [remove_unused_styles()](/cells/python-net/ru/aspose.cells/workbook/remove_unused_styles/#) | Удалите все неиспользуемые стили.|
| [create_style()](/cells/python-net/ru/aspose.cells/workbook/create_style/#) | Создает новый стиль.|
| [create_builtin_style(type)](/cells/python-net/ru/aspose.cells/workbook/create_builtin_style/#BuiltinStyleType) | Создает встроенный стиль по заданному типу.|
| [create_cells_color()](/cells/python-net/ru/aspose.cells/workbook/create_cells_color/#) | Создает объект [CellsColor](/cells/python-net/ru/aspose.cells/cellscolor).|
| [combine(second_workbook)](/cells/python-net/ru/aspose.cells/workbook/combine/#Workbook) | Объединяет другой объект Workbook.|
| [get_style_in_pool(index)](/cells/python-net/ru/aspose.cells/workbook/get_style_in_pool/#int) | Получает стиль из пула стилей.<br/>Все стили в книге будут собраны в пул.<br/> В ячейках есть только простой ссылочный индекс.|
| [get_fonts()](/cells/python-net/ru/aspose.cells/workbook/get_fonts/#) | Получает все шрифты в пуле стилей.|
| [get_named_style(name)](/cells/python-net/ru/aspose.cells/workbook/get_named_style/#str) | Получает именованный стиль в пуле стилей.|
| [change_palette(color, index)](/cells/python-net/ru/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) | Изменяет палитру электронной таблицы в указанном индексе.|
| [is_color_in_palette(color)](/cells/python-net/ru/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) | Проверяет наличие цвета в палитре электронной таблицы.|
| [get_matching_color(raw_color)](/cells/python-net/ru/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) | Найдите наиболее подходящий цвет в текущей палитре.|
| [set_encryption_options(encryption_type, key_length)](/cells/python-net/ru/aspose.cells/workbook/set_encryption_options/#EncryptionType-int) | Установите параметры шифрования.|
| [protect(protection_type, password)](/cells/python-net/ru/aspose.cells/workbook/protect/#ProtectionType-str) | Защищает рабочую книгу.|
| [protect_shared_workbook(password)](/cells/python-net/ru/aspose.cells/workbook/protect_shared_workbook/#str) | Защищает общую книгу.|
| [unprotect(password)](/cells/python-net/ru/aspose.cells/workbook/unprotect/#str) | Снимает защиту с книги.|
| [unprotect_shared_workbook(password)](/cells/python-net/ru/aspose.cells/workbook/unprotect_shared_workbook/#str) | Снимает защиту с общей книги.|
| [remove_macro()](/cells/python-net/ru/aspose.cells/workbook/remove_macro/#) | Удаляет VBA/макрос из этой электронной таблицы.|
| [remove_digital_signature()](/cells/python-net/ru/aspose.cells/workbook/remove_digital_signature/#) | Удаляет цифровую подпись из этой электронной таблицы.|
| [accept_all_revisions()](/cells/python-net/ru/aspose.cells/workbook/accept_all_revisions/#) | Принимает все отслеживаемые изменения в книге.|
| [remove_external_links()](/cells/python-net/ru/aspose.cells/workbook/remove_external_links/#) |Удаляет все внешние ссылки в книге.|
| [get_theme_color(type)](/cells/python-net/ru/aspose.cells/workbook/get_theme_color/#ThemeColorType) | Получает цвет темы.|
| [set_theme_color(type, color)](/cells/python-net/ru/aspose.cells/workbook/set_theme_color/#ThemeColorType-aspose.pydrawing.Color) | Устанавливает цвет темы|
| [custom_theme(theme_name, colors)](/cells/python-net/ru/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) | Таможня тема.|
| [copy_theme(source)](/cells/python-net/ru/aspose.cells/workbook/copy_theme/#Workbook) | Копирует тему из другой книги.|
| [has_exernal_links()](/cells/python-net/ru/aspose.cells/workbook/has_exernal_links/#) | Указывает, содержит ли эта книга внешние ссылки на другие источники данных.|
| [update_linked_data_source(external_workbooks)](/cells/python-net/ru/aspose.cells/workbook/update_linked_data_source/#list) | Если эта рабочая книга содержит внешние ссылки на другой источник данных,<br/> Aspose.Cells попытается получить последние данные.|
| [set_digital_signature(digital_signature_collection)](/cells/python-net/ru/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Устанавливает цифровую подпись для файла электронной таблицы (Excel2007 и более поздние версии).|
| [add_digital_signature(digital_signature_collection)](/cells/python-net/ru/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Добавляет цифровую подпись в файл электронной таблицы OOXML (Excel2007 и более поздние версии).|
| [get_digital_signature()](/cells/python-net/ru/aspose.cells/workbook/get_digital_signature/#) | Получает цифровую подпись из файла.|
| [remove_personal_information()](/cells/python-net/ru/aspose.cells/workbook/remove_personal_information/#) | Удаляет личную информацию.|



###  Примечания

Класс Workbook обозначает электронную таблицу Excel. Каждая электронная таблица может содержать несколько рабочих листов.
Основная функция класса — открывать и сохранять собственные файлы Excel.
У класса есть некоторые дополнительные функции, такие как копирование данных из других рабочих книг, объединение двух рабочих книг и защита электронной таблицы Excel.

###  Пример

Следующий пример загружает Workbook из файла с именем Designer.xls и делает горизонтальную и вертикальную полосы прокрутки невидимыми для Workbook. Затем он заменяет два строковых значения целочисленным значением и строковым значением соответственно в электронной таблице и, наконец, отправляет обновленный файл в браузер клиента.

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
workbook.save("result.xls")

```

###  Смотрите также
* модуль [aspose.cells](..)
* класс [CellsColor](/cells/python-net/ru/aspose.cells/cellscolor)
* класс [ContentTypeProperty](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty)
* класс [DocumentProperty](/cells/python-net/ru/aspose.cells.properties/documentproperty)
* класс [ExternalConnection](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection)
* класс [Style](/cells/python-net/ru/aspose.cells/style)
* класс [Workbook](/cells/python-net/ru/aspose.cells/workbook)
* класс [WorksheetCollection](/cells/python-net/ru/aspose.cells/worksheetcollection)
