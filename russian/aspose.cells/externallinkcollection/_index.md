---
title: ExternalLinkCollection класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 570
url: /ru/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection класс
Представляет коллекцию внешних ссылок в книге.



Тип ExternalLinkCollection предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [count](/cells/python-net/ru/aspose.cells/externallinkcollection/count) | Получает количество элементов, фактически содержащихся в коллекции.|



Получает элемент [ExternalLink](/cells/python-net/ru/aspose.cells/externallink) по указанному индексу.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] | Отсчитываемый от нуля индекс элемента.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add(file_name, sheet_names)](/cells/python-net/ru/aspose.cells/externallinkcollection/add/#str-list) | Добавляет внешнюю ссылку.|
| [add(directory_type, file_name, sheet_names)](/cells/python-net/ru/aspose.cells/externallinkcollection/add/#DirectoryType-str-list) | Добавьте внешнюю ссылку.|
| [clear()](/cells/python-net/ru/aspose.cells/externallinkcollection/clear/#) | Удаляет все внешние ссылки.|
| [clear(update_references_as_local)](/cells/python-net/ru/aspose.cells/externallinkcollection/clear/#bool) | Удаляет все внешние ссылки.|
| [remove_at(index)](/cells/python-net/ru/aspose.cells/externallinkcollection/remove_at/#int) | Удаляет указанную внешнюю ссылку из книги.|
| [remove_at(index, update_references_as_local)](/cells/python-net/ru/aspose.cells/externallinkcollection/remove_at/#int-bool) | Удаляет указанную внешнюю ссылку из книги.|



###  Пример

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Смотрите также
* модуль [aspose.cells](..)
* класс [ExternalLink](/cells/python-net/ru/aspose.cells/externallink)
