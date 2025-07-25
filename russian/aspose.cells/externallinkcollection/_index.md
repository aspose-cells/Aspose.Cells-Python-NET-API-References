---
title: ExternalLinkCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 580
url: /ru/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection класс
Представляет коллекцию внешних ссылок в рабочей книге.



Тип ExternalLinkCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [count](/cells/python-net/ru/aspose.cells/externallinkcollection/count) | Возвращает количество элементов, фактически содержащихся в коллекции.|



Получает элемент [`ExternalLink`](/cells/python-net/ru/aspose.cells/externallink) по указанному индексу.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] | Индекс элемента, отсчитываемый от нуля.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/ru/aspose.cells/externallinkcollection/add/#str-list) | Добавляет внешнюю ссылку.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/ru/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | Добавить внешнюю ссылку.|
| [`clear(self)`](/cells/python-net/ru/aspose.cells/externallinkcollection/clear/#) | Удаляет все внешние ссылки.|
| [`clear(self, update_references_as_local)`](/cells/python-net/ru/aspose.cells/externallinkcollection/clear/#bool) | Удаляет все внешние ссылки.|
| [`remove_at(self, index)`](/cells/python-net/ru/aspose.cells/externallinkcollection/remove_at/#int) | Удаляет указанную внешнюю ссылку из книги.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/ru/aspose.cells/externallinkcollection/remove_at/#int-bool) | Удаляет указанную внешнюю ссылку из книги.|



###  Пример

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`ExternalLink`](/cells/python-net/ru/aspose.cells/externallink)
