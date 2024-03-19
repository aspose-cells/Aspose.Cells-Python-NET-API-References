---
title: TxtLoadOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1580
url: /ru/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions класс
Представляет параметры загрузки текстового файла.



**Наследование:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)



Тип TxtLoadOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/txtloadoptions/__init__/#) | Создает параметры для загрузки текстового файла.|
| [__init__](/cells/python-net/ru/aspose.cells/txtloadoptions/__init__/#aspose.cells.LoadFormat) | Создает параметры для загрузки текстового файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/txtloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/txtloadoptions/password) | Получает и устанавливает пароль книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/txtloadoptions/parsing_formula_on_open) | Указывает, выполняется ли синтаксический анализ формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Указывает, выполняется ли синтаксический анализ сводных кэшированных записей при загрузке файла.<br/> Значение по умолчанию неверно.|
| [language_code](/cells/python-net/ru/aspose.cells/txtloadoptions/language_code) | Получает или задает язык пользовательского интерфейса версии книги на основе CountryCode, в котором сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/txtloadoptions/region) |Получает или задает региональные параметры системы на основе CountryCode на момент загрузки файла.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/txtloadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/txtloadoptions/standard_font) | Устанавливает имя стандартного шрифта по умолчанию|
| [standard_font_size](/cells/python-net/ru/aspose.cells/txtloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/txtloadoptions/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/txtloadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются при прямой печати файла.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/txtloadoptions/check_data_valid) | Проверьте, действительны ли данные в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/txtloadoptions/check_excel_restriction) | Проверьте, ограничено ли использование файла Excel при изменении пользователем объектов, связанных с ячейками.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32 КБ.<br/>Когда вы вводите значение длиной более 32 КБ, например Cell.PutValue(string), если это свойство истинно, вы получите исключение.<br/>Если это свойство имеет значение false, мы примем значение входной строки в качестве значения ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для файлов других форматов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/> вам не следует сохранять книгу в формате файла Excel позже. В противном случае в созданном файле Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/txtloadoptions/keep_unparsed_data) | Сохранять ли неанализированные данные в памяти для книги при ее загрузке из файла шаблона. По умолчанию верно.|
| [load_filter](/cells/python-net/ru/aspose.cells/txtloadoptions/load_filter) | Фильтр, обозначающий способ загрузки данных.|
| [light_cells_data_handler](/cells/python-net/ru/aspose.cells/txtloadoptions/light_cells_data_handler) | Обработчик данных для обработки данных ячеек при чтении файла шаблона.|
| [memory_setting](/cells/python-net/ru/aspose.cells/txtloadoptions/memory_setting) | Получает или задает параметры использования памяти.|
| [warning_callback](/cells/python-net/ru/aspose.cells/txtloadoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/txtloadoptions/auto_fitter_options) | Получает и устанавливает параметры автоустановщика.|
| [auto_filter](/cells/python-net/ru/aspose.cells/txtloadoptions/auto_filter) | Указывает, выполняется ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/txtloadoptions/font_configs) | Получает и устанавливает отдельные конфигурации шрифтов.<br/> Работает только для [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), который использует для загрузки этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions).|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/txtloadoptions/ignore_useless_shapes) | Указывает, игнорируются ли бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и разрывы строк, заполняемые между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — ложь.|
| [encoding](/cells/python-net/ru/aspose.cells/txtloadoptions/encoding) |Получает и задает кодировку по умолчанию. Применяется только для файла csv.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/txtloadoptions/load_style_strategy) | Указывает стратегию применения стиля к анализируемым значениям при преобразовании строкового значения в число или дату и время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/txtloadoptions/convert_numeric_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/txtloadoptions/convert_date_time_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в данные даты.|
| [keep_precision](/cells/python-net/ru/aspose.cells/txtloadoptions/keep_precision) | Указывает, следует ли анализировать строковое значение, если длина равна 15.|
| [separator](/cells/python-net/ru/aspose.cells/txtloadoptions/separator) | Получает и устанавливает разделитель символов текстового файла.|
| [separator_string](/cells/python-net/ru/aspose.cells/txtloadoptions/separator_string) | Получает и устанавливает строковое значение в качестве разделителя.|
| [is_multi_encoded](/cells/python-net/ru/aspose.cells/txtloadoptions/is_multi_encoded) |True означает, что файл содержит несколько кодировок.|
| [preferred_parsers](/cells/python-net/ru/aspose.cells/txtloadoptions/preferred_parsers) | Получает и задает анализаторы предпочтительных значений для загрузки текстового файла.|
| [has_formula](/cells/python-net/ru/aspose.cells/txtloadoptions/has_formula) | Указывает, является ли текст формулой, если он начинается с "=".|
| [has_text_qualifier](/cells/python-net/ru/aspose.cells/txtloadoptions/has_text_qualifier) | Имеется ли текстовый квалификатор для значения ячейки. По умолчанию верно.|
| [text_qualifier](/cells/python-net/ru/aspose.cells/txtloadoptions/text_qualifier) | Указывает текстовый квалификатор для значений ячеек. Квалификатор по умолчанию — '"'.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/ru/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Следует ли рассматривать последовательные разделители как один.|
| [treat_quote_prefix_as_value](/cells/python-net/ru/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Указывает, следует ли считать начальную одинарную кавычку частью значения одной ячейки.<br/>По умолчанию верно. Если оно ложно, лидирующая одинарная кавычка будет удалена из значения соответствующей ячейки.<br/> и [`Style.quote_prefix`](/cells/python-net/ru/aspose.cells/style#quote_prefix) будет установлено как истинное для ячейки.|
| [extend_to_next_sheet](/cells/python-net/ru/aspose.cells/txtloadoptions/extend_to_next_sheet) | Расширяет ли данные на следующий лист, когда количество строк или столбцов данных превышает лимит.<br/> По умолчанию — ложь.|
| [header_rows_count](/cells/python-net/ru/aspose.cells/txtloadoptions/header_rows_count) | Число строк заголовков, которые будут повторяться для расширенных листов.|
| [header_columns_count](/cells/python-net/ru/aspose.cells/txtloadoptions/header_columns_count) | Число столбцов заголовков, которые будут повторяться для расширенных листов.|
| [max_row_count](/cells/python-net/ru/aspose.cells/txtloadoptions/max_row_count) | Максимальное количество строк, которые можно импортировать на один лист.|
| [max_column_count](/cells/python-net/ru/aspose.cells/txtloadoptions/max_column_count) | Максимальное количество столбцов, которые можно импортировать на один лист.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_paper_size](/cells/python-net/ru/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Устанавливает размер бумаги для печати по умолчанию из настроек принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`AbstractTextLoadOptions`](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`TxtLoadOptions`](/cells/python-net/ru/aspose.cells/txtloadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
