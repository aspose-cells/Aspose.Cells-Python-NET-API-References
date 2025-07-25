---
title: XmlLoadOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1660
url: /ru/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions класс
Представляет варианты загрузки xml.



**Наследование:** [`XmlLoadOptions`](/cells/python-net/aspose.cells/xmlloadoptions) → 
[`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)



Тип XmlLoadOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/xmlloadoptions/__init__/#) | Представляет варианты загрузки XML-файла.|
| [`__init__(self, type)`](/cells/python-net/ru/aspose.cells/xmlloadoptions/__init__/#aspose.cells.loadformat) | Представляет варианты загрузки XML-файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_format](/cells/python-net/ru/aspose.cells/xmlloadoptions/load_format) | Получает формат загрузки.|
| [password](/cells/python-net/ru/aspose.cells/xmlloadoptions/password) | Получает и задает пароль для рабочей книги.|
| [parsing_formula_on_open](/cells/python-net/ru/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Указывает, производится ли разбор формулы при чтении файла.|
| [parsing_pivot_cached_records](/cells/python-net/ru/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Указывает, кэшируются ли записи при разборе сводной таблицы при загрузке файла.<br/> Значение по умолчанию — false.|
| [language_code](/cells/python-net/ru/aspose.cells/xmlloadoptions/language_code) | Возвращает или задает язык пользовательского интерфейса версии рабочей книги на основе кода страны, в которой сохранен файл.|
| [region](/cells/python-net/ru/aspose.cells/xmlloadoptions/region) | Возвращает или задает региональные настройки, используемые для рабочей книги, которая будет загружена.|
| [default_style_settings](/cells/python-net/ru/aspose.cells/xmlloadoptions/default_style_settings) | Получает настройки стиля по умолчанию для инициализации стилей рабочей книги.|
| [standard_font](/cells/python-net/ru/aspose.cells/xmlloadoptions/standard_font) | Задает имя стандартного шрифта по умолчанию.|
| [standard_font_size](/cells/python-net/ru/aspose.cells/xmlloadoptions/standard_font_size) | Устанавливает стандартный размер шрифта по умолчанию.|
| [ignore_not_printed](/cells/python-net/ru/aspose.cells/xmlloadoptions/ignore_not_printed) | Игнорируйте данные, которые не печатаются, если файл печатается напрямую.|
| [check_data_valid](/cells/python-net/ru/aspose.cells/xmlloadoptions/check_data_valid) | Проверьте корректность данных в файле шаблона.|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/xmlloadoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/>При вводе значения длиной более 32 КБ, например Cell.PutValue(string), если это свойство имеет значение true, вы получите исключение.<br/>Если это свойство ложно, мы примем ваше входное строковое значение как значение ячейки, чтобы позже<br/>вы можете вывести полное строковое значение для других форматов файлов, например CSV.<br/>Однако, если вы установили такое значение, которое недопустимо для формата файла Excel,<br/>Не сохраняйте книгу в формате Excel. В противном случае при создании файла Excel может возникнуть непредвиденная ошибка.|
| [keep_unparsed_data](/cells/python-net/ru/aspose.cells/xmlloadoptions/keep_unparsed_data) | Сохранять ли неразобранные данные в памяти рабочей книги при её загрузке из файла шаблона. Значение по умолчанию — true.|
| [load_filter](/cells/python-net/ru/aspose.cells/xmlloadoptions/load_filter) | Фильтр, указывающий способ загрузки данных.|
| [memory_setting](/cells/python-net/ru/aspose.cells/xmlloadoptions/memory_setting) | Возвращает или задает режим памяти для загруженной книги.|
| [auto_fitter_options](/cells/python-net/ru/aspose.cells/xmlloadoptions/auto_fitter_options) | Получает и задает параметры автоподбора|
| [auto_filter](/cells/python-net/ru/aspose.cells/xmlloadoptions/auto_filter) | Указывает, производится ли автоматическая фильтрация данных при загрузке файлов.|
| [font_configs](/cells/python-net/ru/aspose.cells/xmlloadoptions/font_configs) | Получает и задает индивидуальные конфигурации шрифтов.<br/> Работает только для модели [`Workbook`](/cells/python-net/ru/aspose.cells/workbook), которая использует этот [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions) для загрузки.|
| [ignore_useless_shapes](/cells/python-net/ru/aspose.cells/xmlloadoptions/ignore_useless_shapes) | Указывает, следует ли игнорировать бесполезные фигуры.|
| [preserve_padding_spaces_in_formula](/cells/python-net/ru/aspose.cells/xmlloadoptions/preserve_padding_spaces_in_formula) | Указывает, следует ли сохранять пробелы и переносы строк, которые находятся между токенами формулы.<br/>при получении и установке формул.<br/> Значение по умолчанию — false.|
| [start_cell](/cells/python-net/ru/aspose.cells/xmlloadoptions/start_cell) | Получает и задает начальную ячейку.|
| [is_xml_map](/cells/python-net/ru/aspose.cells/xmlloadoptions/is_xml_map) | Указывает, нужно ли сопоставлять xml с Excel.<br/> Значение по умолчанию — false.|
| [contains_multiple_worksheets](/cells/python-net/ru/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Указывает, импортируется ли XML как несколько рабочих листов.|
| [convert_numeric_or_date](/cells/python-net/ru/aspose.cells/xmlloadoptions/convert_numeric_or_date) | Указывает, преобразовывается ли значение в XML-файле в число или дату.|
| [number_format](/cells/python-net/ru/aspose.cells/xmlloadoptions/number_format) | Получает и задает формат числового значения.|
| [date_format](/cells/python-net/ru/aspose.cells/xmlloadoptions/date_format) | Получает и задает формат значения даты.|
| [ignore_root_attributes](/cells/python-net/ru/aspose.cells/xmlloadoptions/ignore_root_attributes) | Указывает, следует ли игнорировать атрибуты корневого элемента.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/ru/aspose.cells/xmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Устанавливает размер бумаги для печати по умолчанию в соответствии с настройками принтера по умолчанию.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
* класс [`XmlLoadOptions`](/cells/python-net/ru/aspose.cells/xmlloadoptions)
