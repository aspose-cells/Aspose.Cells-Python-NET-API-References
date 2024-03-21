---
title: get_default_sheet_name метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 80
url: /ru/aspose.cells/globalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name {#}
Получает имя листа по умолчанию для автоматического добавления листа.
По умолчанию — «Лист».


###  Возврат

имя листа по умолчанию для автоматического добавления листа


```python
def get_default_sheet_name(self):
    ...
```


###  Примечания

Автоматически добавленный (например, по номеру [`WorksheetCollection.add`](/cells/python-net/ru/aspose.cells/worksheetcollection/add))
именем листа будет указанное имя плюс порядковый номер.
 Например, пользователь из Германии может захотеть, чтобы имя листа было «Табелленблатт2» вместо «Лист2».
Затем пользователь может реализовать этот метод для возврата «Tabellenblatt».


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`GlobalizationSettings`](/cells/python-net/ru/aspose.cells/globalizationsettings)
