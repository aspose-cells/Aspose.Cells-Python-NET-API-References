---
title: HtmlLoadOptions класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 770
url: /ru/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions класс
Представляет параметры при импорте html-файла.



**Наследование:** [HtmlLoadOptions](/cells/python-net/aspose.cells/htmlloadoptions) → 
[AbstractTextLoadOptions](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[LoadOptions](/cells/python-net/ru/aspose.cells/loadoptions)



Тип HtmlLoadOptions предоставляет следующие члены:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [HtmlLoadOptions()](/cells/python-net/ru/aspose.cells/htmlloadoptions/__init__/#) | Создает опции загрузки файла.|
| [HtmlLoadOptions(load_format)](/cells/python-net/ru/aspose.cells/htmlloadoptions/__init__/#LoadFormat) | Создает опции загрузки файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/htmlloadoptions/password) | Получает и устанавливает пароль книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Указывает, выполняется ли разбор формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Указывает, выполняется ли разбор сводных кэшированных записей при загрузке файла.<br/> Значение по умолчанию неверно.|
| [language_code](/cells/python-net/ru/aspose.cells/htmlloadoptions/language_code) | Получает или задает язык пользовательского интерфейса версии Workbook на основе CountryCode, в котором сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/htmlloadoptions/region) | Получает или задает региональные параметры системы на основе CountryCode на момент загрузки файла.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/htmlloadoptions/default_style_settings) | Получает параметры стиля по умолчанию для инициализации стилей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/htmlloadoptions/standard_font) | Устанавливает стандартное имя шрифта по умолчанию|
| [standard_font_size](/cells/python-net/ru/aspose.cells/htmlloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/htmlloadoptions/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/htmlloadoptions/ignore_not_printed) | Игнорировать данные, которые не печатаются, при прямой печати файла|
| [check_data_valid](/cells/python-net/ru/aspose.cells/htmlloadoptions/check_data_valid) |Проверьте правильность данных в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/htmlloadoptions/check_excel_restriction) | Проверять ли ограничение файла excel, когда пользователь изменяет объекты, связанные с ячейками.<br/>Например, Excel не позволяет вводить строковое значение длиннее 32 КБ.<br/>Когда вы вводите значение длиннее 32 КБ, например, Cell.PutValue(строка), если это свойство истинно, вы получите исключение.<br/>Если это свойство имеет значение false, мы примем значение вашей входной строки в качестве значения ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для файлов других форматов, таких как CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/> вы не должны сохранять книгу в формате файла Excel позже. В противном случае может возникнуть непредвиденная ошибка для сгенерированного файла Excel.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/keep_unparsed_data) | Сохранять ли непроанализированные данные в памяти для рабочей книги, когда она загружается из файла шаблона. Значение по умолчанию верно.|
| [load_filter](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_filter) | Фильтр для обозначения того, как загружать данные.|
| [light_cells_data_handler](/cells/python-net/ru/aspose.cells/htmlloadoptions/light_cells_data_handler) | Обработчик данных для обработки данных ячеек при чтении файла шаблона.|
| [memory_setting](/cells/python-net/ru/aspose.cells/htmlloadoptions/memory_setting) | Получает или задает параметры использования памяти.|
| [warning_callback](/cells/python-net/ru/aspose.cells/htmlloadoptions/warning_callback) | Получает или задает обратный вызов предупреждения.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_fitter_options) | Получает и задает параметры автоматической установки|
| [auto_filter](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_filter) | Указывает, выполняется ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/htmlloadoptions/font_configs) | Получает и устанавливает отдельные конфигурации шрифтов.<br/> Работает только для [Workbook](/cells/python-net/ru/aspose.cells/workbook), который использует этот [LoadOptions](/cells/python-net/ru/aspose.cells/loadoptions) для загрузки.|
| [encoding](/cells/python-net/ru/aspose.cells/htmlloadoptions/encoding) | Получает и задает кодировку по умолчанию. Применяется только для CSV-файла.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_style_strategy) |Указывает стратегию применения стиля для проанализированных значений при преобразовании строкового значения в число или дату и время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_numeric_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_date_time_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в данные даты.|
| [keep_precision](/cells/python-net/ru/aspose.cells/htmlloadoptions/keep_precision) | Указывает, не анализировать ли строковое значение, если длина равна 15.|
| [attached_files_directory](/cells/python-net/ru/aspose.cells/htmlloadoptions/attached_files_directory) | Каталог, в который будут сохранены вложенные файлы.|
| [load_formulas](/cells/python-net/ru/aspose.cells/htmlloadoptions/load_formulas) | Указывает, следует ли импортировать формулы, если исходный html-файл содержит формулы|
| [support_div_tag](/cells/python-net/ru/aspose.cells/htmlloadoptions/support_div_tag) | Указывает, поддерживает ли макет<div> тег, когда файл html содержит<div> теги. Значение по умолчанию неверно.|
| [delete_redundant_spaces](/cells/python-net/ru/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Указывает, следует ли удалять лишние пробелы, когда текст переносит строки с помощью<br> тег. Значение по умолчанию — false.|
| [auto_fit_cols_and_rows](/cells/python-net/ru/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Указывает, будут ли автоматически подбираться столбцы и строки. Значение по умолчанию неверно.|
| [convert_formulas_data](/cells/python-net/ru/aspose.cells/htmlloadoptions/convert_formulas_data) | если true, преобразовать строку в формулу, когда строковое значение начинается с символа '=', значение по умолчанию - false.|
| [stream_provider](/cells/python-net/ru/aspose.cells/htmlloadoptions/stream_provider) | Получает или задает StreamProviderImportHtmlFile для импорта объектов.|
| [prog_id](/cells/python-net/ru/aspose.cells/htmlloadoptions/prog_id) | Получает идентификатор программы создания файла.<br/> Только для файлов MHT.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/ru/aspose.cells/htmlloadoptions/set_paper_size/#PaperSizeType) | Устанавливает размер бумаги для печати по умолчанию из настроек принтера по умолчанию.|



###  Смотрите также
* модуль [aspose.cells](..)
* класс [AbstractTextLoadOptions](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [HtmlLoadOptions](/cells/python-net/ru/aspose.cells/htmlloadoptions)
* класс [LoadOptions](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [Workbook](/cells/python-net/ru/aspose.cells/workbook)
