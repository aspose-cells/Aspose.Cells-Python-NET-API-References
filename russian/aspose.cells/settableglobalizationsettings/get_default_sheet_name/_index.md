---
title: get_default_sheet_name метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name(self) {#}
Получает имя листа по умолчанию для автоматического добавления листа.
По умолчанию — «Лист».


###  Возврат

имя листа по умолчанию для автоматического добавления листа


```python

def get_default_sheet_name(self):
    ...
```


###  Примечания

Автоматически добавленный (например, [`WorksheetCollection.add`](/cells/python-net/ru/aspose.cells/worksheetcollection/add))
Имя листа будет состоять из указанного имени и порядкового номера.
 Например, пользователь из Германии может захотеть, чтобы имя листа было «Tabellenblatt2» вместо «Sheet2».
Затем пользователь может реализовать этот метод для возврата «Tabellenblatt».


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`SettableGlobalizationSettings`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings)
