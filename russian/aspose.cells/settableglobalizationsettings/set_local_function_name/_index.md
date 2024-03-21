---
title: set_local_function_name метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 350
url: /ru/aspose.cells/settableglobalizationsettings/set_local_function_name/
is_root: false
---
##  set_local_function_name {#str-str-bool}
Устанавливает имя функции, зависящее от локали, соответствующее заданному стандартному имени функции.



```python
def set_local_function_name(self, standard_name, local_name, bidirectional):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| standard_name | str | Стандартное имя функции (язык EN-US).|
| local_name | str | Имя функции, зависящее от локали|
| bidirectional | bool | Автоматически ли сопоставлять имя локальной функции со стандартным именем функции.<br/>Если это правда, локальное имя будет автоматически сопоставлено со стандартным именем.<br/>поэтому пользователю не нужно снова звонить на номер [`SettableGlobalizationSettings.set_standard_function_name`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_function_name).<br/> для одной и той же пары стандартных и локальных имен|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`SettableGlobalizationSettings`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings)
