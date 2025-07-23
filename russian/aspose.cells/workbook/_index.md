---
title: Workbook класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1570
url: /ru/aspose.cells/workbook/
is_root: false
---
##  Workbook класс
Представляет корневой объект для создания электронной таблицы Excel.



Тип Workbook предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/workbook/__init__/#) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook).|
| [`__init__(self, file_format_type)`](/cells/python-net/ru/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook).|
| [`__init__(self, file)`](/cells/python-net/ru/aspose.cells/workbook/__init__/#str) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.|
| [`__init__(self, stream)`](/cells/python-net/ru/aspose.cells/workbook/__init__/#io.rawiobase) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.|
| [`__init__(self, file, load_options)`](/cells/python-net/ru/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.|
| [`__init__(self, stream, load_options)`](/cells/python-net/ru/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [settings](/cells/python-net/ru/aspose.cells/workbook/settings) | Представляет параметры книги.|
| [worksheets](/cells/python-net/ru/aspose.cells/workbook/worksheets) | Получает коллекцию [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection) в электронной таблице.|
| [is_licensed](/cells/python-net/ru/aspose.cells/workbook/is_licensed) | Указывает, установлена ли лицензия.|
| [colors](/cells/python-net/ru/aspose.cells/workbook/colors) | Возвращает цвета в палитре электронной таблицы.|
| [count_of_styles_in_pool](/cells/python-net/ru/aspose.cells/workbook/count_of_styles_in_pool) | Возвращает количество стилей в пуле стилей.|
| [default_style](/cells/python-net/ru/aspose.cells/workbook/default_style) | Возвращает или задает объект [`Style`](/cells/python-net/ru/aspose.cells/style) по умолчанию для рабочей книги.|
| [is_digitally_signed](/cells/python-net/ru/aspose.cells/workbook/is_digitally_signed) | Указывает, имеет ли данная электронная таблица цифровую подпись.|
| [is_workbook_protected_with_password](/cells/python-net/ru/aspose.cells/workbook/is_workbook_protected_with_password) | Указывает, защищена ли структура или окно паролем.|
| [vba_project](/cells/python-net/ru/aspose.cells/workbook/vba_project) |Получает [`Workbook.vba_project`](/cells/python-net/ru/aspose.cells/workbook#vba_project) в электронной таблице.|
| [has_macro](/cells/python-net/ru/aspose.cells/workbook/has_macro) | Указывает, содержит ли эта электронная таблица макрос/VBA.|
| [has_revisions](/cells/python-net/ru/aspose.cells/workbook/has_revisions) | Проверяет, есть ли в книге отслеживаемые изменения.|
| [file_name](/cells/python-net/ru/aspose.cells/workbook/file_name) | Получает и задает текущее имя файла.|
| [cells_data_table_factory](/cells/python-net/ru/aspose.cells/workbook/cells_data_table_factory) | Получает фабрику для построения ICellsDataTable из пользовательских объектов.|
| [data_sorter](/cells/python-net/ru/aspose.cells/workbook/data_sorter) | Получает объект DataSorter для сортировки данных.|
| [theme](/cells/python-net/ru/aspose.cells/workbook/theme) | Получает имя темы.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells/workbook/built_in_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells/workbook/custom_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все пользовательские свойства документа электронной таблицы.|
| [file_format](/cells/python-net/ru/aspose.cells/workbook/file_format) | Получает и задает формат файла.|
| [has_custom_function](/cells/python-net/ru/aspose.cells/workbook/has_custom_function) | Определяет, используется ли в этой книге пользовательская функция,<br/> например, в формуле ячейки, в определенных именах...|
| [content_type_properties](/cells/python-net/ru/aspose.cells/workbook/content_type_properties) | Получает список из [`ContentTypeProperty`](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty) объектов в рабочей книге.|
| [custom_xml_parts](/cells/python-net/ru/aspose.cells/workbook/custom_xml_parts) | Представляет собой часть хранилища пользовательских XML-данных (пользовательские XML-данные в пакете).|
| [data_mashup](/cells/python-net/ru/aspose.cells/workbook/data_mashup) | Получает данные мэшапа.|
| [ribbon_xml](/cells/python-net/ru/aspose.cells/workbook/ribbon_xml) | Получает и задает XML-файл, определяющий пользовательский интерфейс Ribbon.|
| [absolute_path](/cells/python-net/ru/aspose.cells/workbook/absolute_path) | Получает и задает абсолютный путь к файлу.|
| [data_connections](/cells/python-net/ru/aspose.cells/workbook/data_connections) |Получает коллекцию ExternalConnection.|
| [data_model](/cells/python-net/ru/aspose.cells/workbook/data_model) | Получает модель данных в рабочей книге.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/ru/aspose.cells/workbook/save/#str-aspose.cells.saveformat) | Сохраняет книгу на диск.|
| [`save(self, file_name)`](/cells/python-net/ru/aspose.cells/workbook/save/#str) | Сохраните книгу на диске.|
| [`save(self, file_name, save_options)`](/cells/python-net/ru/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) | Сохраняет книгу на диск.|
| [`save(self, stream, save_format)`](/cells/python-net/ru/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) | Сохраняет книгу в потоке.|
| [`save(self, stream, save_options)`](/cells/python-net/ru/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) | Сохраняет книгу в потоке.|
| [`create_style(self)`](/cells/python-net/ru/aspose.cells/workbook/create_style/#) | Создаёт новый стиль.|
| [`create_style(self, clone_default_style)`](/cells/python-net/ru/aspose.cells/workbook/create_style/#bool) | Создаёт новый стиль.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-str) | Заменяет значение ячейки новой строкой.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-int) | Заменяет значение ячейки новым целым числом.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-float) | Заменяет значение ячейки новым числом двойной точности.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значение ячейки новым строковым массивом.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значения ячеек целочисленным массивом.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значения ячеек двойным массивом.|
| [`replace(self, bool_value, new_value)`](/cells/python-net/ru/aspose.cells/workbook/replace/#bool-any) | Заменяет значения ячеек новыми данными.|
| [`replace(self, int_value, new_value)`](/cells/python-net/ru/aspose.cells/workbook/replace/#int-any) | Заменяет значения ячеек новыми данными.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/ru/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) | Заменяет значение ячейки новой строкой.|
| [`copy(self, source, copy_options)`](/cells/python-net/ru/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) | Копирует другой объект Workbook.|
| [`copy(self, source)`](/cells/python-net/ru/aspose.cells/workbook/copy/#aspose.cells.workbook) | Копирует данные из исходного объекта Workbook.|
| [`calculate_formula(self)`](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#) | Вычисляет результат формул.|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#bool) | Вычисляет результат формул.|
| [`calculate_formula(self, options)`](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) | Расчетные формулы в этой рабочей тетради.|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/ru/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Обновляет динамические формулы массива (переносит в новый диапазон соседних ячеек в соответствии с текущими данными)<br/> Другие формулы в рабочей книге не будут вычисляться рекурсивно, даже если они использовались в формулах динамического массива.|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/ru/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |Обновляет динамические формулы массива (переносит в новый диапазон соседних ячеек в соответствии с текущими данными)|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/ru/aspose.cells/workbook/import_xml/#str-str-int-int) | Импортирует/обновляет XML-файл данных в рабочую книгу.|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/ru/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) | Импортирует/обновляет XML-файл данных в рабочую книгу.|
| [`export_xml(self, map_name, path)`](/cells/python-net/ru/aspose.cells/workbook/export_xml/#str-str) | Экспорт XML-данных, связанных с указанной XML-картой.|
| [`export_xml(self, map_name, stream)`](/cells/python-net/ru/aspose.cells/workbook/export_xml/#str-io.rawiobase) | Экспорт XML-данных.|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/ru/aspose.cells/workbook/parse_formulas/#bool) | Анализирует все формулы, которые не были проанализированы при загрузке из файла шаблона или установке в ячейку.|
| [`start_access_cache(self, opts)`](/cells/python-net/ru/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) | Запускает сеанс, использующий кэши для доступа к данным.|
| [`close_access_cache(self, opts)`](/cells/python-net/ru/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) | Закрывает сеанс, использующий кэши для доступа к данным.|
| [`remove_unused_styles(self)`](/cells/python-net/ru/aspose.cells/workbook/remove_unused_styles/#) | Удалите все неиспользуемые стили.|
| [`create_builtin_style(self, type)`](/cells/python-net/ru/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) | Создает встроенный стиль по заданному типу.|
| [`create_cells_color(self)`](/cells/python-net/ru/aspose.cells/workbook/create_cells_color/#) | Создает объект [`CellsColor`](/cells/python-net/ru/aspose.cells/cellscolor).|
| [`combine(self, second_workbook)`](/cells/python-net/ru/aspose.cells/workbook/combine/#aspose.cells.workbook) | Объединяет другой объект Workbook.|
| [`get_style_in_pool(self, index)`](/cells/python-net/ru/aspose.cells/workbook/get_style_in_pool/#int) | Получает стиль из пула стилей.<br/>Все стили в рабочей книге будут объединены в пул.<br/> В ячейках имеется только простой справочный индекс.|
| [`get_fonts(self)`](/cells/python-net/ru/aspose.cells/workbook/get_fonts/#) | Получает все шрифты в пуле стилей.|
| [`get_named_style(self, name)`](/cells/python-net/ru/aspose.cells/workbook/get_named_style/#str) | Получает именованный стиль в пуле стилей.|
| [`merge_named_styles(self, source)`](/cells/python-net/ru/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) | Объединяет именованные стили из другого файла Excel.|
| [`change_palette(self, color, index)`](/cells/python-net/ru/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) | Изменяет палитру для электронной таблицы в указанном индексе.|
| [`is_color_in_palette(self, color)`](/cells/python-net/ru/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) | Проверяет, присутствует ли цвет в палитре электронной таблицы.|
| [`get_matching_color(self, raw_color)`](/cells/python-net/ru/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |Найдите наиболее подходящий цвет в текущей палитре.|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/ru/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) | Установите параметры шифрования.|
| [`protect(self, protection_type, password)`](/cells/python-net/ru/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) | Защищает рабочую книгу.|
| [`protect_shared_workbook(self, password)`](/cells/python-net/ru/aspose.cells/workbook/protect_shared_workbook/#str) | Защищает общую книгу.|
| [`unprotect(self, password)`](/cells/python-net/ru/aspose.cells/workbook/unprotect/#str) | Снимает защиту с книги.|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/ru/aspose.cells/workbook/unprotect_shared_workbook/#str) | Снимает защиту с общей книги.|
| [`remove_macro(self)`](/cells/python-net/ru/aspose.cells/workbook/remove_macro/#) | Удаляет VBA/макрос из этой электронной таблицы.|
| [`remove_digital_signature(self)`](/cells/python-net/ru/aspose.cells/workbook/remove_digital_signature/#) | Удаляет цифровую подпись из этой электронной таблицы.|
| [`accept_all_revisions(self)`](/cells/python-net/ru/aspose.cells/workbook/accept_all_revisions/#) | Принимает все отслеживаемые изменения в рабочей книге.|
| [`remove_external_links(self)`](/cells/python-net/ru/aspose.cells/workbook/remove_external_links/#) | Удаляет все внешние ссылки в книге.|
| [`get_theme_color(self, type)`](/cells/python-net/ru/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) | Получает цвет темы.|
| [`set_theme_color(self, type, color)`](/cells/python-net/ru/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) | Устанавливает цвет темы|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/ru/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) | Таможня тема.|
| [`copy_theme(self, source)`](/cells/python-net/ru/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) | Копирует тему из другой рабочей книги.|
| [`has_exernal_links(self)`](/cells/python-net/ru/aspose.cells/workbook/has_exernal_links/#) | Указывает, содержит ли эта книга внешние ссылки на другие источники данных.|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/ru/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) | Обновляет определение пользовательских функций.|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/ru/aspose.cells/workbook/update_linked_data_source/#list) | Если эта рабочая книга содержит внешние ссылки на другие источники данных,<br/> Aspose.Cells попытается получить последние данные из указанных источников.|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/ru/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Устанавливает цифровую подпись для файла электронной таблицы (Excel2007 и более поздние версии).|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/ru/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Добавляет цифровую подпись в файл электронной таблицы OOXML (Excel2007 и более поздние версии).|
| [`get_digital_signature(self)`](/cells/python-net/ru/aspose.cells/workbook/get_digital_signature/#) |Получает цифровую подпись из файла.|
| [`remove_personal_information(self)`](/cells/python-net/ru/aspose.cells/workbook/remove_personal_information/#) | Удаляет персональные данные.|
| [`close(self)`](/cells/python-net/ru/aspose.cells/workbook/close/#) | Dispose() пропускается оболочкой с протокола Python|



###  Примечания

Класс Workbook обозначает электронную таблицу Excel. Каждая таблица может содержать несколько рабочих листов.
Основная функция класса — открытие и сохранение собственных файлов Excel.
Класс обладает некоторыми расширенными функциями, такими как копирование данных из других рабочих книг, объединение двух рабочих книг, преобразование Excel в PDF, преобразование Excel в изображение и защита электронной таблицы Excel.

###  Пример

В следующем примере загружается Workbook из файла Excel с именем designer.xls и делаются невидимыми горизонтальные и вертикальные полосы прокрутки.
 Затем он заменяет два строковых значения целочисленным значением и строковым значением соответственно в электронной таблице и, наконец, сохраняет книгу как файл Excel xlsx.

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

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`CellsColor`](/cells/python-net/ru/aspose.cells/cellscolor)
* класс [`ContentTypeProperty`](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty)
* класс [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty)
* класс [`Style`](/cells/python-net/ru/aspose.cells/style)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
