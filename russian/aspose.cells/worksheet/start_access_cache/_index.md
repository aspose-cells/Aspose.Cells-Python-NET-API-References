---
title: start_access_cache метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 320
url: /ru/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Запускает сеанс, который использует кэши для доступа к данным на этом листе.



```python

def start_access_cache(self, opts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/ru/aspose.cells/accesscacheoptions) | варианты доступа к данным|
###  Примечания

После завершения доступа к данным [`Worksheet.close_access_cache`](/cells/python-net/ru/aspose.cells/worksheet/close_access_cache) должен
быть вызван с теми же параметрами для очистки всех кэшей и восстановления обычного режима доступа.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
