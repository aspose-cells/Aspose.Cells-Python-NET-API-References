---
title: get_cache_folder метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells/cellshelper/get_cache_folder/
is_root: false
---
##  get_cache_folder() {#}
Получает папку для временных файлов, которые могут использоваться в качестве кэша данных.


###  Возврат

Указанная папка для кэш-файлов.
Если не указано иное, будет возвращено значение null.
и при необходимости будет использоваться временный путь системы.


```python

@staticmethod
def get_cache_folder():
    ...
```


###  Примечания

Файлы кэша обычно используются для некоторых функций с целью оценки производительности памяти,
например, сохранение больших наборов данных в файл xls,
или с использованием режима памяти с файловым кэшем для модели ячеек.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CellsHelper`](/cells/python-net/ru/aspose.cells/cellshelper)
