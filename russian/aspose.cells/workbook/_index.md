---
title: Workbook класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1660
url: /ru/aspose.cells/workbook/
is_root: false
---
##  Workbook класс
Представляет корневой объект для создания электронной таблицы Excel.



Тип Workbook предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/workbook/__init__/#) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook).|
| [__init__](/cells/python-net/ru/aspose.cells/workbook/__init__/#aspose.cells.FileFormatType) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook).|
| [__init__](/cells/python-net/ru/aspose.cells/workbook/__init__/#str) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.|
| [__init__](/cells/python-net/ru/aspose.cells/workbook/__init__/#io.RawIOBase) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.|
| [__init__](/cells/python-net/ru/aspose.cells/workbook/__init__/#str-aspose.cells.LoadOptions) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.|
| [__init__](/cells/python-net/ru/aspose.cells/workbook/__init__/#io.RawIOBase-aspose.cells.LoadOptions) | Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [settings](/cells/python-net/ru/aspose.cells/workbook/settings) | Представляет параметры книги.|
| [worksheets](/cells/python-net/ru/aspose.cells/workbook/worksheets) | Получает коллекцию [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection) в электронной таблице.|
| [is_licensed](/cells/python-net/ru/aspose.cells/workbook/is_licensed) | Указывает, установлена ли лицензия.|
| [colors](/cells/python-net/ru/aspose.cells/workbook/colors) | Возвращает цвета в палитре электронной таблицы.|
| [count_of_styles_in_pool](/cells/python-net/ru/aspose.cells/workbook/count_of_styles_in_pool) | Получает количество стилей в пуле стилей.|
| [default_style](/cells/python-net/ru/aspose.cells/workbook/default_style) |Получает или задает объект книги по умолчанию [`Style`](/cells/python-net/ru/aspose.cells/style).|
| [is_digitally_signed](/cells/python-net/ru/aspose.cells/workbook/is_digitally_signed) | Указывает, имеет ли эта таблица цифровую подпись.|
| [is_workbook_protected_with_password](/cells/python-net/ru/aspose.cells/workbook/is_workbook_protected_with_password) | Указывает, защищена ли структура или окно паролем.|
| [vba_project](/cells/python-net/ru/aspose.cells/workbook/vba_project) | Получает [`Workbook.vba_project`](/cells/python-net/ru/aspose.cells/workbook#vba_project) в электронной таблице.|
| [has_macro](/cells/python-net/ru/aspose.cells/workbook/has_macro) | Указывает, содержит ли эта электронная таблица макрос/VBA.|
| [has_revisions](/cells/python-net/ru/aspose.cells/workbook/has_revisions) | Проверяет, есть ли в книге отслеживаемые изменения.|
| [file_name](/cells/python-net/ru/aspose.cells/workbook/file_name) | Получает и задает текущее имя файла.|
| [cells_data_table_factory](/cells/python-net/ru/aspose.cells/workbook/cells_data_table_factory) | Получает фабрику для построения ICellsDataTable из пользовательских объектов.|
| [data_sorter](/cells/python-net/ru/aspose.cells/workbook/data_sorter) | Получает объект DataSorter для сортировки данных.|
| [theme](/cells/python-net/ru/aspose.cells/workbook/theme) | Получает имя темы.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells/workbook/built_in_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells/workbook/custom_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все настраиваемые свойства документа электронной таблицы.|
| [file_format](/cells/python-net/ru/aspose.cells/workbook/file_format) | Получает и задает формат файла.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/workbook/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [content_type_properties](/cells/python-net/ru/aspose.cells/workbook/content_type_properties) | Получает список объектов [`ContentTypeProperty`](/cells/python-net/ru/aspose.cells.properties/contenttypeproperty) в книге.|
| [custom_xml_parts](/cells/python-net/ru/aspose.cells/workbook/custom_xml_parts) | Представляет часть хранилища настраиваемых XML-данных (настраиваемые XML-данные в пакете).|
| [data_mashup](/cells/python-net/ru/aspose.cells/workbook/data_mashup) | Получает данные гибридного веб-приложения.|
| [ribbon_xml](/cells/python-net/ru/aspose.cells/workbook/ribbon_xml) |Получает и задает XML-файл, определяющий пользовательский интерфейс ленты.|
| [absolute_path](/cells/python-net/ru/aspose.cells/workbook/absolute_path) | Получает и задает абсолютный путь к файлу.|
| [data_connections](/cells/python-net/ru/aspose.cells/workbook/data_connections) | Получает коллекцию [`ExternalConnection`](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection).|


###  Методы
| Метод| Описание|
| :- | :- |
| [save](/cells/python-net/ru/aspose.cells/workbook/save/#str-aspose.cells.SaveFormat) | Сохраняет книгу на диск.|
| [save](/cells/python-net/ru/aspose.cells/workbook/save/#str) | Сохраните книгу на диск.|
| [save](/cells/python-net/ru/aspose.cells/workbook/save/#str-aspose.cells.SaveOptions) | Сохраняет книгу на диск.|
| [save](/cells/python-net/ru/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveFormat) | Сохраняет книгу в поток.|
| [save](/cells/python-net/ru/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveOptions) | Сохраняет книгу в поток.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-str) | Заменяет значение ячейки новой строкой.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-int) | Заменяет значение ячейки новым целым числом.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-float) | Заменяет значение ячейки новым двойным числом.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значение ячейки новым массивом строк.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значения ячеек целочисленным массивом.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-list-bool) | Заменяет значения ячеек двойным массивом.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#bool-any) | Заменяет значения ячеек новыми данными.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#int-any) | Заменяет значения ячеек новыми данными.|
| [replace](/cells/python-net/ru/aspose.cells/workbook/replace/#str-str-aspose.cells.ReplaceOptions) | Заменяет значение ячейки новой строкой.|
| [copy](/cells/python-net/ru/aspose.cells/workbook/copy/#aspose.cells.Workbook-aspose.cells.CopyOptions) | Копирует другой объект Workbook.|
| [copy](/cells/python-net/ru/aspose.cells/workbook/copy/#aspose.cells.Workbook) | Копирует данные из исходного объекта Workbook.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#) | Вычисляет результат по формулам.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#bool) | Вычисляет результат по формулам.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/workbook/calculate_formula/#aspose.cells.CalculationOptions) | Расчетные формулы в этой рабочей тетради.|
| [refresh_dynamic_array_formulas](/cells/python-net/ru/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Обновляет формулы динамического массива (перетекает в новый диапазон соседних ячеек в соответствии с текущими данными)<br/>Другие формулы в книге не будут рассчитываться рекурсивно, даже если они использовались формулами динамических массивов.|
| [refresh_dynamic_array_formulas](/cells/python-net/ru/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.CalculationOptions) | Обновляет формулы динамического массива (перетекает в новый диапазон соседних ячеек в соответствии с текущими данными)|
| [import_xml](/cells/python-net/ru/aspose.cells/workbook/import_xml/#str-str-int-int) | Импортирует/обновляет файл данных XML в книгу.|
| [import_xml](/cells/python-net/ru/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) | Импортирует/обновляет файл данных XML в книгу.|
| [export_xml](/cells/python-net/ru/aspose.cells/workbook/export_xml/#str-str) | Экспортируйте данные XML, связанные указанной картой XML.|
| [export_xml](/cells/python-net/ru/aspose.cells/workbook/export_xml/#str-io.RawIOBase) | Экспортируйте XML-данные.|
| [parse_formulas](/cells/python-net/ru/aspose.cells/workbook/parse_formulas/#bool) | Анализирует все формулы, которые не были проанализированы при загрузке из файла шаблона или установке в ячейку.|
| [start_access_cache](/cells/python-net/ru/aspose.cells/workbook/start_access_cache/#aspose.cells.AccessCacheOptions) | Запускает сеанс, который использует кэши для доступа к данным.|
| [close_access_cache](/cells/python-net/ru/aspose.cells/workbook/close_access_cache/#aspose.cells.AccessCacheOptions) | Закрывает сеанс, использующий кэши для доступа к данным.|
| [remove_unused_styles](/cells/python-net/ru/aspose.cells/workbook/remove_unused_styles/#) | Удалите все неиспользуемые стили.|
| [create_style](/cells/python-net/ru/aspose.cells/workbook/create_style/#) | Создает новый стиль.|
| [create_builtin_style](/cells/python-net/ru/aspose.cells/workbook/create_builtin_style/#aspose.cells.BuiltinStyleType) | Создает встроенный стиль по заданному типу.|
| [create_cells_color](/cells/python-net/ru/aspose.cells/workbook/create_cells_color/#) | Создает объект [`CellsColor`](/cells/python-net/ru/aspose.cells/cellscolor).|
| [combine](/cells/python-net/ru/aspose.cells/workbook/combine/#aspose.cells.Workbook) | Объединяет другой объект Workbook.|
| [get_style_in_pool](/cells/python-net/ru/aspose.cells/workbook/get_style_in_pool/#int) | Получает стиль из пула стилей.<br/>Все стили в книге будут собраны в пул.<br/> В ячейках имеется только простой ссылочный индекс.|
| [get_fonts](/cells/python-net/ru/aspose.cells/workbook/get_fonts/#) | Получает все шрифты из пула стилей.|
| [get_named_style](/cells/python-net/ru/aspose.cells/workbook/get_named_style/#str) | Получает именованный стиль из пула стилей.|
| [change_palette](/cells/python-net/ru/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) |Изменяет палитру электронной таблицы по указанному индексу.|
| [is_color_in_palette](/cells/python-net/ru/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) | Проверяет, присутствует ли цвет в палитре электронной таблицы.|
| [get_matching_color](/cells/python-net/ru/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) | Найдите наиболее подходящий цвет в текущей палитре.|
| [set_encryption_options](/cells/python-net/ru/aspose.cells/workbook/set_encryption_options/#aspose.cells.EncryptionType-int) | Установите параметры шифрования.|
| [protect](/cells/python-net/ru/aspose.cells/workbook/protect/#aspose.cells.ProtectionType-str) | Защищает книгу.|
| [protect_shared_workbook](/cells/python-net/ru/aspose.cells/workbook/protect_shared_workbook/#str) | Защищает общую книгу.|
| [unprotect](/cells/python-net/ru/aspose.cells/workbook/unprotect/#str) | Снимает защиту с книги.|
| [unprotect_shared_workbook](/cells/python-net/ru/aspose.cells/workbook/unprotect_shared_workbook/#str) | Снимает защиту с общей книги.|
| [remove_macro](/cells/python-net/ru/aspose.cells/workbook/remove_macro/#) | Удаляет VBA/макрос из этой таблицы.|
| [remove_digital_signature](/cells/python-net/ru/aspose.cells/workbook/remove_digital_signature/#) | Удаляет цифровую подпись из этой таблицы.|
| [accept_all_revisions](/cells/python-net/ru/aspose.cells/workbook/accept_all_revisions/#) | Принимает все отслеживаемые изменения в книге.|
| [remove_external_links](/cells/python-net/ru/aspose.cells/workbook/remove_external_links/#) | Удаляет все внешние ссылки в книге.|
| [get_theme_color](/cells/python-net/ru/aspose.cells/workbook/get_theme_color/#aspose.cells.ThemeColorType) | Получает цвет темы.|
| [set_theme_color](/cells/python-net/ru/aspose.cells/workbook/set_theme_color/#aspose.cells.ThemeColorType-aspose.pydrawing.Color) | Устанавливает цвет темы|
| [custom_theme](/cells/python-net/ru/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) | Таможенная тема.|
| [copy_theme](/cells/python-net/ru/aspose.cells/workbook/copy_theme/#aspose.cells.Workbook) | Копирует тему из другой книги.|
| [has_exernal_links](/cells/python-net/ru/aspose.cells/workbook/has_exernal_links/#) | Указывает, содержит ли эта книга внешние ссылки на другие источники данных.|
| [update_custom_function_definition](/cells/python-net/ru/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.CustomFunctionDefinition) | Обновляет определение пользовательских функций.|
| [update_linked_data_source](/cells/python-net/ru/aspose.cells/workbook/update_linked_data_source/#list) | Если эта книга содержит внешние ссылки на другой источник данных,<br/> Aspose.Cells попытается получить последние данные из указанных источников.|
| [set_digital_signature](/cells/python-net/ru/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) |Устанавливает цифровую подпись для файла электронной таблицы (Excel2007 и более поздних версий).|
| [add_digital_signature](/cells/python-net/ru/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Добавляет цифровую подпись в файл электронной таблицы OOXML (Excel2007 и более поздние версии).|
| [get_digital_signature](/cells/python-net/ru/aspose.cells/workbook/get_digital_signature/#) | Получает цифровую подпись из файла.|
| [remove_personal_information](/cells/python-net/ru/aspose.cells/workbook/remove_personal_information/#) | Удаляет личную информацию.|



###  Примечания

Класс Workbook обозначает электронную таблицу Excel. Каждая электронная таблица может содержать несколько рабочих листов.
Основная функция класса — открытие и сохранение собственных файлов Excel.
Класс имеет некоторые расширенные функции, такие как копирование данных из других книг, объединение двух книг, преобразование Excel в PDF, преобразование Excel в изображение и защита электронной таблицы Excel.

###  Пример

В следующем примере загружается Workbook из файла Excel с именем Designer.xls и делается невидимыми горизонтальная и вертикальная полосы прокрутки.
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
* класс [`ExternalConnection`](/cells/python-net/ru/aspose.cells.externalconnections/externalconnection)
* класс [`Style`](/cells/python-net/ru/aspose.cells/style)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
