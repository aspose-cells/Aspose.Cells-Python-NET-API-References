---
title: LoadOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1060
url: /ru/aspose.cells/loadoptions/
is_root: false
---
##  LoadOptions класс
Представляет параметры загрузки файла.



Тип LoadOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/loadoptions/__init__/#) | Создает параметры загрузки файла.|
| [__init__](/cells/python-net/ru/aspose.cells/loadoptions/__init__/#aspose.cells.LoadFormat) | Создает параметры загрузки файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/loadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/loadoptions/password) | Получает и устанавливает пароль книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/loadoptions/parsing_formula_on_open) | Указывает, выполняется ли синтаксический анализ формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/loadoptions/parsing_pivot_cached_records) | Указывает, выполняется ли синтаксический анализ сводных кэшированных записей при загрузке файла.<br/> Значение по умолчанию неверно.|
| [language_code](/cells/python-net/ru/aspose.cells/loadoptions/language_code) | Получает или задает язык пользовательского интерфейса версии книги на основе CountryCode, в котором сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/loadoptions/region) |Получает или задает региональные параметры системы на основе CountryCode на момент загрузки файла.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/loadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/loadoptions/standard_font) | Устанавливает имя стандартного шрифта по умолчанию|
| [standard_font_size](/cells/python-net/ru/aspose.cells/loadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [interrupt_monitor](/cells/python-net/ru/aspose.cells/loadoptions/interrupt_monitor) | Получает и устанавливает монитор прерываний.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/loadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются при прямой печати файла.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/loadoptions/check_data_valid) | Проверьте, действительны ли данные в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/loadoptions/check_excel_restriction) | Проверьте, ограничено ли использование файла Excel при изменении пользователем объектов, связанных с ячейками.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32 КБ.<br/>Когда вы вводите значение длиной более 32 КБ, например Cell.PutValue(string), если это свойство истинно, вы получите исключение.<br/>Если это свойство имеет значение false, мы примем значение входной строки в качестве значения ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для файлов других форматов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/> вам не следует сохранять книгу в формате файла Excel позже. В противном случае в созданном файле Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/loadoptions/keep_unparsed_data) | Сохранять ли неанализированные данные в памяти для книги при ее загрузке из файла шаблона. По умолчанию верно.|
| [load_filter](/cells/python-net/ru/aspose.cells/loadoptions/load_filter) | Фильтр, обозначающий способ загрузки данных.|
| [light_cells_data_handler](/cells/python-net/ru/aspose.cells/loadoptions/light_cells_data_handler) | Обработчик данных для обработки данных ячеек при чтении файла шаблона.|
| [memory_setting](/cells/python-net/ru/aspose.cells/loadoptions/memory_setting) | Получает или задает параметры использования памяти.|
| [warning_callback](/cells/python-net/ru/aspose.cells/loadoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/loadoptions/auto_fitter_options) | Получает и устанавливает параметры автоустановщика.|
| [auto_filter](/cells/python-net/ru/aspose.cells/loadoptions/auto_filter) | Указывает, выполняется ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/loadoptions/font_configs) | Получает и устанавливает отдельные конфигурации шрифтов.<br/> Работает только для [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), который использует для загрузки этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions).|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/loadoptions/ignore_useless_shapes) | Указывает, игнорируются ли бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/loadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и разрывы строк, заполняемые между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — ложь.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_paper_size](/cells/python-net/ru/aspose.cells/loadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Устанавливает размер бумаги для печати по умолчанию из настроек принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
