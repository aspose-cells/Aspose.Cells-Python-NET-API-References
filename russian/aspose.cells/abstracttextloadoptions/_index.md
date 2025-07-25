---
title: AbstractTextLoadOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/abstracttextloadoptions/
is_root: false
---
##  AbstractTextLoadOptions класс
Распространенные варианты загрузки текстовых значений



**Наследование:** [`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)



Тип AbstractTextLoadOptions предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/password) | Получает и задает пароль для рабочей книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/parsing_formula_on_open) | Указывает, производится ли разбор формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/parsing_pivot_cached_records) | Указывает, кэшируются ли записи при разборе сводной таблицы при загрузке файла.<br/> Значение по умолчанию — false.|
| [language_code](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/language_code) | Возвращает или задает язык пользовательского интерфейса версии рабочей книги на основе кода страны, в которой сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/region) | Возвращает или задает региональные настройки, используемые для рабочей книги, которая будет загружена.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей рабочей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/standard_font) | Задает имя стандартного шрифта по умолчанию.|
| [standard_font_size](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются, если файл печатается напрямую.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/check_data_valid) | Проверьте корректность данных в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/>При вводе значения длиной более 32 КБ, например Cell.PutValue(string), если это свойство имеет значение true, вы получите исключение.<br/>Если это свойство ложно, мы примем ваше входное строковое значение как значение ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для других форматов файлов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/>Не сохраняйте книгу в формате Excel. В противном случае при создании файла Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/keep_unparsed_data) | Сохранять ли неразобранные данные в памяти рабочей книги при её загрузке из файла шаблона. Значение по умолчанию — true.|
| [load_filter](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/load_filter) | Фильтр, указывающий способ загрузки данных.|
| [memory_setting](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/memory_setting) | Возвращает или задает режим памяти для загруженной книги.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/auto_fitter_options) | Получает и задает параметры автоподбора|
| [auto_filter](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/auto_filter) | Указывает, производится ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/font_configs) | Получает и задает индивидуальные конфигурации шрифтов.<br/> Работает только для модели [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), которая использует этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions) для загрузки.|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/ignore_useless_shapes) | Указывает, следует ли игнорировать бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и переносы строк, которые находятся между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — false.|
| [encoding](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/encoding) | Получает и задаёт кодировку по умолчанию. Применимо только к CSV-файлу.|
| [load_style_strategy](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/load_style_strategy) | Указывает стратегию применения стиля к проанализированным значениям при преобразовании строкового значения в число или дату-время.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/convert_numeric_data) |Возвращает или задает значение, указывающее, преобразована ли строка в текстовом файле в числовые данные.|
| [convert_date_time_data](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/convert_date_time_data) | Возвращает или задает значение, указывающее, преобразована ли строка в текстовом файле в данные о дате.|
| [keep_precision](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/keep_precision) | Указывает, следует ли не анализировать строковое значение, если его длина равна 15.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ru/aspose.cells/abstracttextloadoptions/set_paper_size/#aspose.cells.papersizetype) | Устанавливает размер бумаги для печати по умолчанию в соответствии с настройками принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`AbstractTextLoadOptions`](/cells/python-net/ru/aspose.cells/abstracttextloadoptions)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
