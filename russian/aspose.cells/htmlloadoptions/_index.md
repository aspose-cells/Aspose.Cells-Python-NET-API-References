---
title: HtmlLoadOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 780
url: /ru/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions класс
Представляет параметры при импорте HTML-файла.



**Наследование:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)



Тип HtmlLoadOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/htmlloadoptions/__init__/#) | Создает варианты загрузки файла.|
| [`__init__(self, load_format)`](/cells/python-net/ru/aspose.cells/htmlloadoptions/__init__/#aspose.cells.loadformat) | Создает варианты загрузки файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/htmlloadoptions/password) | Получает и задает пароль для рабочей книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Указывает, производится ли разбор формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Указывает, кэшируются ли записи при разборе сводной таблицы при загрузке файла.<br/> Значение по умолчанию — false.|
| [language_code](/cells/python-net/ru/aspose.cells/htmlloadoptions/language_code) | Возвращает или задает язык пользовательского интерфейса версии рабочей книги на основе кода страны, в которой сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/htmlloadoptions/region) | Возвращает или задает региональные настройки, используемые для рабочей книги, которая будет загружена.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/htmlloadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей рабочей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/htmlloadoptions/standard_font) | Задает имя стандартного шрифта по умолчанию.|
| [standard_font_size](/cells/python-net/ru/aspose.cells/htmlloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/htmlloadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются, если файл печатается напрямую.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/htmlloadoptions/check_data_valid) | Проверьте корректность данных в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/htmlloadoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/>При вводе значения длиной более 32 КБ, например Cell.PutValue(string), если это свойство имеет значение true, вы получите исключение.<br/>Если это свойство ложно, мы примем ваше входное строковое значение как значение ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для других форматов файлов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/>Не сохраняйте книгу в формате Excel. В противном случае при создании файла Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/keep_unparsed_data) | Сохранять ли неразобранные данные в памяти рабочей книги при её загрузке из файла шаблона. Значение по умолчанию — true.|
| [load_filter](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_filter) | Фильтр, указывающий способ загрузки данных.|
| [memory_setting](/cells/python-net/ru/aspose.cells/htmlloadoptions/memory_setting) | Возвращает или задает режим памяти для загруженной книги.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_fitter_options) | Получает и задает параметры автоподбора|
| [auto_filter](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_filter) | Указывает, производится ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/htmlloadoptions/font_configs) | Получает и задает индивидуальные конфигурации шрифтов.<br/> Работает только для модели [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), которая использует этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions) для загрузки.|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Указывает, следует ли игнорировать бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и переносы строк, которые находятся между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — false.|
| [encoding](/cells/python-net/ru/aspose.cells/htmlloadoptions/encoding) | Получает и задаёт кодировку по умолчанию. Применимо только к CSV-файлу.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_style_strategy) | Указывает стратегию применения стиля к проанализированным значениям при преобразовании строкового значения в число или дату-время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_numeric_data) |Возвращает или задает значение, указывающее, преобразована ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_date_time_data) | Возвращает или задает значение, указывающее, преобразована ли строка в текстовом файле в данные о дате.|
| [keep_precision](/cells/python-net/ru/aspose.cells/htmlloadoptions/keep_precision) | Указывает, следует ли не анализировать строковое значение, если его длина равна 15.|
| [attached_files_directory](/cells/python-net/ru/aspose.cells/htmlloadoptions/attached_files_directory) | Каталог, в котором будут сохранены прикрепленные файлы.|
| [load_formulas](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_formulas) | Указывает, импортируются ли формулы, если исходный HTML-файл содержит формулы.|
| [support_div_tag](/cells/python-net/ru/aspose.cells/htmlloadoptions/support_div_tag) | Указывает, поддерживается ли макет тега `<div>`, если HTML-файл его содержит.<br/> Значение по умолчанию — false.|
| [delete_redundant_spaces](/cells/python-net/ru/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Указывает, следует ли удалять лишние пробелы при переносе строк текста с помощью тега `<br>`.<br/> Значение по умолчанию — false.|
| [auto_fit_cols_and_rows](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Указывает, следует ли использовать автоподбор столбцов и строк. Значение по умолчанию — false.|
| [convert_formulas_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_formulas_data) |если true, преобразовать строку в формулу, когда строковое значение начинается с символа «=», значение по умолчанию — false.|
| [has_formula](/cells/python-net/ru/aspose.cells/htmlloadoptions/has_formula) | Указывает, является ли текст формулой, если он начинается с «=».|
| [prog_id](/cells/python-net/ru/aspose.cells/htmlloadoptions/prog_id) | Получает идентификатор программы, создавшей файл.<br/> Только для MHT-файлов.|
| [table_load_options](/cells/python-net/ru/aspose.cells/htmlloadoptions/table_load_options) | Получить экземпляр HtmlTableLoadOptionCollection|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ru/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Устанавливает размер бумаги для печати по умолчанию в соответствии с настройками принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`AbstractTextLoadOptions`](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [`HtmlLoadOptions`](/cells/python-net/ru/aspose.cells/htmlloadoptions)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
