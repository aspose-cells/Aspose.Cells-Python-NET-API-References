---
title: AbstractTextLoadOptions класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 60
url: /ru/aspose.cells/abstracttextloadoptions/
is_root: false
---
##  AbstractTextLoadOptions класс
Общие параметры загрузки текстовых значений



**Наследование:** [AbstractTextLoadOptions](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[LoadOptions](/cells/python-net/ru/aspose.cells/loadoptions)



Тип AbstractTextLoadOptions предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/password) | Получает и устанавливает пароль книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/parsing_formula_on_open) | Указывает, выполняется ли разбор формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/parsing_pivot_cached_records) | Указывает, выполняется ли разбор сводных кэшированных записей при загрузке файла.<br/> Значение по умолчанию неверно.|
| [language_code](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/language_code) | Получает или задает язык пользовательского интерфейса версии Workbook на основе CountryCode, в котором сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/region) | Получает или задает региональные параметры системы на основе CountryCode на момент загрузки файла.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/default_style_settings) | Получает параметры стиля по умолчанию для инициализации стилей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/standard_font) | Устанавливает стандартное имя шрифта по умолчанию|
| [standard_font_size](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/ignore_not_printed) | Игнорировать данные, которые не печатаются, при прямой печати файла|
| [check_data_valid](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/check_data_valid) |Проверьте правильность данных в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/check_excel_restriction) | Проверять ли ограничение файла excel, когда пользователь изменяет объекты, связанные с ячейками.<br/>Например, Excel не позволяет вводить строковое значение длиннее 32 КБ.<br/>Когда вы вводите значение длиннее 32 КБ, например, Cell.PutValue(строка), если это свойство истинно, вы получите исключение.<br/>Если это свойство имеет значение false, мы примем значение вашей входной строки в качестве значения ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для файлов других форматов, таких как CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/> вы не должны сохранять книгу в формате файла Excel позже. В противном случае может возникнуть непредвиденная ошибка для сгенерированного файла Excel.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/keep_unparsed_data) | Сохранять ли непроанализированные данные в памяти для рабочей книги, когда она загружается из файла шаблона. Значение по умолчанию верно.|
| [load_filter](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/load_filter) | Фильтр для обозначения того, как загружать данные.|
| [light_cells_data_handler](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/light_cells_data_handler) | Обработчик данных для обработки данных ячеек при чтении файла шаблона.|
| [memory_setting](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/memory_setting) | Получает или задает параметры использования памяти.|
| [warning_callback](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/warning_callback) | Получает или задает обратный вызов предупреждения.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/auto_fitter_options) | Получает и задает параметры автоматической установки|
| [auto_filter](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/auto_filter) | Указывает, выполняется ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/font_configs) | Получает и устанавливает отдельные конфигурации шрифтов.<br/> Работает только для [Workbook](/cells/python-net/ru/aspose.cells/workbook), который использует этот [LoadOptions](/cells/python-net/ru/aspose.cells/loadoptions) для загрузки.|
| [encoding](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/encoding) | Получает и задает кодировку по умолчанию. Применяется только для CSV-файла.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/load_style_strategy) |Указывает стратегию применения стиля для проанализированных значений при преобразовании строкового значения в число или дату и время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/convert_numeric_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/convert_date_time_data) | Получает или задает значение, указывающее, преобразуется ли строка в текстовом файле в данные даты.|
| [keep_precision](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/keep_precision) | Указывает, не анализировать ли строковое значение, если длина равна 15.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/set_paper_size/#PaperSizeType) | Устанавливает размер бумаги для печати по умолчанию из настроек принтера по умолчанию.|



###  Смотрите также
* модуль [aspose.cells](..)
* класс [AbstractTextLoadOptions](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [LoadOptions](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [Workbook](/cells/python-net/ru/aspose.cells/workbook)
