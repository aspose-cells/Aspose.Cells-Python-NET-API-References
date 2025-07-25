---
title: EbookLoadOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 520
url: /ru/aspose.cells/ebookloadoptions/
is_root: false
---
##  EbookLoadOptions класс
Представляет параметры при импорте файла электронной книги.



**Наследование:** [`EbookLoadOptions`](/cells/python-net/aspose.cells/ebookloadoptions) → 
[`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)



Тип EbookLoadOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/ebookloadoptions/__init__/#) | Создает параметры загрузки файла электронной книги.|
| [`__init__(self, load_format)`](/cells/python-net/ru/aspose.cells/ebookloadoptions/__init__/#aspose.cells.loadformat) | Создает параметры загрузки файла электронной книги.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/ebookloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/ebookloadoptions/password) | Получает и задает пароль для рабочей книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/ebookloadoptions/parsing_formula_on_open) | Указывает, производится ли разбор формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/ebookloadoptions/parsing_pivot_cached_records) | Указывает, кэшируются ли записи при разборе сводной таблицы при загрузке файла.<br/> Значение по умолчанию — false.|
| [language_code](/cells/python-net/ru/aspose.cells/ebookloadoptions/language_code) | Возвращает или задает язык пользовательского интерфейса версии рабочей книги на основе кода страны, в которой сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/ebookloadoptions/region) | Возвращает или задает региональные настройки, используемые для рабочей книги, которая будет загружена.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/ebookloadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей рабочей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/ebookloadoptions/standard_font) | Задает имя стандартного шрифта по умолчанию.|
| [standard_font_size](/cells/python-net/ru/aspose.cells/ebookloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/ebookloadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются, если файл печатается напрямую.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/ebookloadoptions/check_data_valid) | Проверьте корректность данных в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/ebookloadoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/>При вводе значения длиной более 32 КБ, например Cell.PutValue(string), если это свойство имеет значение true, вы получите исключение.<br/>Если это свойство ложно, мы примем ваше входное строковое значение как значение ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для других форматов файлов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/>Не сохраняйте книгу в формате Excel. В противном случае при создании файла Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/ebookloadoptions/keep_unparsed_data) | Сохранять ли неразобранные данные в памяти рабочей книги при её загрузке из файла шаблона. Значение по умолчанию — true.|
| [load_filter](/cells/python-net/ru/aspose.cells/ebookloadoptions/load_filter) | Фильтр, указывающий способ загрузки данных.|
| [memory_setting](/cells/python-net/ru/aspose.cells/ebookloadoptions/memory_setting) | Возвращает или задает режим памяти для загруженной книги.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/ebookloadoptions/auto_fitter_options) | Получает и задает параметры автоподбора|
| [auto_filter](/cells/python-net/ru/aspose.cells/ebookloadoptions/auto_filter) | Указывает, производится ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/ebookloadoptions/font_configs) | Получает и задает индивидуальные конфигурации шрифтов.<br/> Работает только для модели [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), которая использует этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions) для загрузки.|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/ebookloadoptions/ignore_useless_shapes) | Указывает, следует ли игнорировать бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/ebookloadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и переносы строк, которые находятся между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — false.|
| [encoding](/cells/python-net/ru/aspose.cells/ebookloadoptions/encoding) | Получает и задаёт кодировку по умолчанию. Применимо только к CSV-файлу.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/ebookloadoptions/load_style_strategy) | Указывает стратегию применения стиля к проанализированным значениям при преобразовании строкового значения в число или дату-время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/ebookloadoptions/convert_numeric_data) |Возвращает или задает значение, указывающее, преобразована ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/ebookloadoptions/convert_date_time_data) | Возвращает или задает значение, указывающее, преобразована ли строка в текстовом файле в данные о дате.|
| [keep_precision](/cells/python-net/ru/aspose.cells/ebookloadoptions/keep_precision) | Указывает, следует ли не анализировать строковое значение, если его длина равна 15.|
| [attached_files_directory](/cells/python-net/ru/aspose.cells/ebookloadoptions/attached_files_directory) | Каталог, в котором будут сохранены прикрепленные файлы.|
| [load_formulas](/cells/python-net/ru/aspose.cells/ebookloadoptions/load_formulas) | Указывает, импортируются ли формулы, если исходный HTML-файл содержит формулы.|
| [support_div_tag](/cells/python-net/ru/aspose.cells/ebookloadoptions/support_div_tag) | Указывает, поддерживается ли макет тега `<div>`, если HTML-файл его содержит.<br/> Значение по умолчанию — false.|
| [delete_redundant_spaces](/cells/python-net/ru/aspose.cells/ebookloadoptions/delete_redundant_spaces) | Указывает, следует ли удалять лишние пробелы при переносе строк текста с помощью тега `<br>`.<br/> Значение по умолчанию — false.|
| [auto_fit_cols_and_rows](/cells/python-net/ru/aspose.cells/ebookloadoptions/auto_fit_cols_and_rows) | Указывает, следует ли использовать автоподбор столбцов и строк. Значение по умолчанию — false.|
| [convert_formulas_data](/cells/python-net/ru/aspose.cells/ebookloadoptions/convert_formulas_data) |если true, преобразовать строку в формулу, когда строковое значение начинается с символа «=», значение по умолчанию — false.|
| [has_formula](/cells/python-net/ru/aspose.cells/ebookloadoptions/has_formula) | Указывает, является ли текст формулой, если он начинается с «=».|
| [prog_id](/cells/python-net/ru/aspose.cells/ebookloadoptions/prog_id) | Получает идентификатор программы, создавшей файл.<br/> Только для MHT-файлов.|
| [table_load_options](/cells/python-net/ru/aspose.cells/ebookloadoptions/table_load_options) | Получить экземпляр HtmlTableLoadOptionCollection|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ru/aspose.cells/ebookloadoptions/set_paper_size/#aspose.cells.papersizetype) | Устанавливает размер бумаги для печати по умолчанию в соответствии с настройками принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`AbstractTextLoadOptions`](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [`EbookLoadOptions`](/cells/python-net/ru/aspose.cells/ebookloadoptions)
* класс [`HtmlLoadOptions`](/cells/python-net/ru/aspose.cells/htmlloadoptions)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
