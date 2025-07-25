---
title: LowCodeSaveOptionsProviderOfPlaceHolders класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 120
url: /ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders класс
Реализация, предоставляющая возможности сохранения, которые сохраняют разделенные части в файлы
и путь к результирующему файлу определяются с помощью заполнителей.



**Наследование:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



Тип LowCodeSaveOptionsProviderOfPlaceHolders предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Создает экземпляр для предоставления параметров сохранения в соответствии с указанными шаблонами.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [sheet_index_offset](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Смещение индекса листа между тем, что используется в пути к файлу<br/> и его фактическое значение ([`SplitPartInfo.sheet_index`](/cells/python-net/ru/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Смещение индекса разделенной части между тем, что используется в пути к файлу<br/> и его фактическое значение ([`SplitPartInfo.part_index`](/cells/python-net/ru/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Добавлять ли индекс листа или имя всегда к пути файла.<br/>Значение по умолчанию — false, то есть, когда есть только один лист,<br/>индекс листа, имя и соответствующий префикс ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> не будет добавлен в путь к файлу.|
| [build_path_with_split_part_always](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Добавлять ли всегда индекс разделенной части к пути файла.<br/>Значение по умолчанию — false, то есть, когда есть только одна разделенная часть,<br/>индекс разделенной части и соответствующий префикс ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> не будет добавлен в путь к файлу.|
| [sheet_name_prefix](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Префикс для индекса рабочего листа.|
| [sheet_index_prefix](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Префикс для индекса рабочего листа.|
| [split_part_prefix](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Префикс для индекса разделенной части.|
| [save_options_template](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | Шаблон для создания экземпляра сохранения параметров в [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Получает параметры сохранения, из которых можно получить выходные настройки для текущей разделенной части.|
| [`finish(self, part)`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Смотрите также
* модуль [`aspose.cells.lowcode`](..)
* класс [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
