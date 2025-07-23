---
title: start_access_cache метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 400
url: /ru/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Запускает сеанс, использующий кэши для доступа к данным.



```python

def start_access_cache(self, opts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/ru/aspose.cells/accesscacheoptions) | варианты доступа к данным|
###  Примечания

Если кэш указанного доступа к данным требует, чтобы некоторые модели данных на листе были доступны «только для чтения»,
то соответствующие модели данных на каждом листе этой книги будут восприниматься как доступные только для чтения.
и пользователь не должен изменять ни один из них.


После завершения доступа к данным [`Workbook.close_access_cache`](/cells/python-net/ru/aspose.cells/workbook/close_access_cache) должен
быть вызван с теми же параметрами для очистки всех кэшей и восстановления обычного режима доступа.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
