---
title: LowCodeSaveOptionsProviderOfAssembling класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling класс
Реализация, предоставляющая возможности сохранения, которые сохраняют разделенные части в файлы
и путь к полученному файлу именуются как (он может содержать каталоги):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+ИндексЛиста(или ИмяЛиста)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Наследование:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



Тип LowCodeSaveOptionsProviderOfAssembling предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | Создает новый экземпляр LowCodeSaveOptionsProviderOfAssembling|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [path_header](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Заголовочная часть (до добавленного содержимого листа и разделенной части) пути к файлу.|
| [path_tail](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Конечная часть (после порядковых номеров) пути к файлу.<br/> Необходимо указать расширение имени файла.|
| [use_sheet_name](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Создавать ли путь к файлу с именем листа вместо индекса листа. Значение по умолчанию — false.|
| [sheet_prefix](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Префикс для индекса рабочего листа.|
| [split_part_prefix](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Префикс для индекса разделенной части.|
| [sheet_index_offset](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Смещение индекса листа между тем, что используется в пути к файлу<br/> и его фактическое значение ([`SplitPartInfo.sheet_index`](/cells/python-net/ru/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Смещение индекса разделенной части между тем, что используется в пути к файлу<br/> и его фактическое значение ([`SplitPartInfo.part_index`](/cells/python-net/ru/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Добавлять ли индекс листа или имя всегда к пути файла.<br/>Значение по умолчанию — false, то есть, когда есть только один лист,<br/> индекс листа (или имя) и соответствующий префикс не будут добавлены к пути к файлу.|
| [build_path_with_split_part_always](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Добавлять ли всегда индекс разделенной части к пути файла.<br/>Значение по умолчанию — false, то есть, когда есть только одна разделенная часть,<br/> индекс разделенной части и соответствующий префикс не будут добавлены к пути файла.|
| [save_options_template](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | Шаблон для создания экземпляра сохранения параметров в [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Получает параметры сохранения, из которых можно получить выходные настройки для текущей разделенной части.|
| [`finish(self, part)`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Смотрите также
* модуль [`aspose.cells.lowcode`](..)
* класс [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
