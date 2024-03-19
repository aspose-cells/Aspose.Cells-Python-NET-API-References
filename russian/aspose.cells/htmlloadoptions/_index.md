---
title: HtmlLoadOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 800
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
| [__init__](/cells/python-net/ru/aspose.cells/htmlloadoptions/__init__/#) | Создает параметры загрузки файла.|
| [__init__](/cells/python-net/ru/aspose.cells/htmlloadoptions/__init__/#aspose.cells.LoadFormat) | Создает параметры загрузки файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/htmlloadoptions/password) | Получает и устанавливает пароль книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Указывает, выполняется ли синтаксический анализ формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Указывает, выполняется ли синтаксический анализ сводных кэшированных записей при загрузке файла.<br/> Значение по умолчанию неверно.|
| [language_code](/cells/python-net/ru/aspose.cells/htmlloadoptions/language_code) | Получает или задает язык пользовательского интерфейса версии книги на основе CountryCode, в котором сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/htmlloadoptions/region) |Получает или задает региональные параметры системы на основе CountryCode на момент загрузки файла.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/htmlloadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/htmlloadoptions/standard_font) | Устанавливает имя стандартного шрифта по умолчанию|
| [standard_font_size](/cells/python-net/ru/aspose.cells/htmlloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/htmlloadoptions/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/htmlloadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются при прямой печати файла.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/htmlloadoptions/check_data_valid) | Проверьте, действительны ли данные в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/htmlloadoptions/check_excel_restriction) | Проверьте, ограничено ли использование файла Excel при изменении пользователем объектов, связанных с ячейками.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32 КБ.<br/>Когда вы вводите значение длиной более 32 КБ, например Cell.PutValue(string), если это свойство истинно, вы получите исключение.<br/>Если это свойство имеет значение false, мы примем значение входной строки в качестве значения ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для файлов других форматов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/> вам не следует сохранять книгу в формате файла Excel позже. В противном случае в созданном файле Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/keep_unparsed_data) | Сохранять ли неанализированные данные в памяти для книги при ее загрузке из файла шаблона. По умолчанию верно.|
| [load_filter](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_filter) | Фильтр, обозначающий способ загрузки данных.|
| [light_cells_data_handler](/cells/python-net/ru/aspose.cells/htmlloadoptions/light_cells_data_handler) | Обработчик данных для обработки данных ячеек при чтении файла шаблона.|
| [memory_setting](/cells/python-net/ru/aspose.cells/htmlloadoptions/memory_setting) | Получает или задает параметры использования памяти.|
| [warning_callback](/cells/python-net/ru/aspose.cells/htmlloadoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_fitter_options) | Получает и устанавливает параметры автоустановщика.|
| [auto_filter](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_filter) | Указывает, выполняется ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/htmlloadoptions/font_configs) | Получает и устанавливает отдельные конфигурации шрифтов.<br/> Работает только для [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), который использует для загрузки этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions).|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Указывает, игнорируются ли бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и разрывы строк, заполняемые между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — ложь.|
| [encoding](/cells/python-net/ru/aspose.cells/htmlloadoptions/encoding) |Получает и задает кодировку по умолчанию. Применяется только для файла csv.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_style_strategy) | Указывает стратегию применения стиля к анализируемым значениям при преобразовании строкового значения в число или дату и время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_numeric_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_date_time_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в данные даты.|
| [keep_precision](/cells/python-net/ru/aspose.cells/htmlloadoptions/keep_precision) | Указывает, следует ли анализировать строковое значение, если длина равна 15.|
| [attached_files_directory](/cells/python-net/ru/aspose.cells/htmlloadoptions/attached_files_directory) | Каталог, в котором будут сохранены прикрепленные файлы.|
| [load_formulas](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_formulas) | Указывает, следует ли импортировать формулы, если исходный HTML-файл содержит формулы.|
| [support_div_tag](/cells/python-net/ru/aspose.cells/htmlloadoptions/support_div_tag) |Указывает, поддерживается ли макет тега `<div>`, если он содержится в html-файле.<br/> Значение по умолчанию неверно.|
| [delete_redundant_spaces](/cells/python-net/ru/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Указывает, следует ли удалять лишние пробелы, когда текст переносит строки с помощью тега `<br>`.<br/> Значение по умолчанию неверно.|
| [auto_fit_cols_and_rows](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Указывает, подгоняются ли столбцы и строки автоматически. Значение по умолчанию неверно.|
| [convert_formulas_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_formulas_data) | если true, преобразовать строку в формулу, когда строковое значение начинается с символа «=», значение по умолчанию — false.|
| [has_formula](/cells/python-net/ru/aspose.cells/htmlloadoptions/has_formula) | Указывает, является ли текст формулой, если он начинается с "=".|
| [stream_provider](/cells/python-net/ru/aspose.cells/htmlloadoptions/stream_provider) | Получает или задает StreamProviderImportHtmlFile для импорта объектов.|
| [prog_id](/cells/python-net/ru/aspose.cells/htmlloadoptions/prog_id) | Получает идентификатор программы, создавшей файл.<br/> Только для файлов MHT.|
| [table_load_options](/cells/python-net/ru/aspose.cells/htmlloadoptions/table_load_options) | Получите экземпляр HtmlTableLoadOptionCollection.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_paper_size](/cells/python-net/ru/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Устанавливает размер бумаги для печати по умолчанию из настроек принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`AbstractTextLoadOptions`](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [`HtmlLoadOptions`](/cells/python-net/ru/aspose.cells/htmlloadoptions)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
