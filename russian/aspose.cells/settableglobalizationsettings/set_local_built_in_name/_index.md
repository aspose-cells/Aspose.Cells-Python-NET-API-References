---
title: set_local_built_in_name метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 340
url: /ru/aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---
##  set_local_built_in_name {#str-str-bool}
Устанавливает текст, зависящий от локали, для встроенного имени с заданным стандартным текстом имени.



```python
def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| standard_name | str |Стандартный (локальный стандарт EN-US) текст встроенного имени.|
| local_name | str | Текст имени, зависящий от локали|
| bidirectional | bool | Автоматически ли сопоставлять текст локального имени со стандартным текстом имени.<br/>Если это правда, текст локального имени будет автоматически сопоставлен со стандартным текстом имени.<br/>поэтому пользователю не нужно снова звонить на номер [`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_built_in_name).<br/> для одной и той же пары стандартных и локальных имен|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`SettableGlobalizationSettings`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings)
