---
title: max_column_count недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 290
url: /ru/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count недвижимость

Максимальное количество столбцов, которые можно импортировать на один лист.

###  Примечания

Столбцы, превышающие этот предел, будут игнорироваться.
или продлен на следующий лист по номеру [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/ru/aspose.cells/txtloadoptions#extend_to_next_sheet).
Это количество включает столбцы заголовков ([`TxtLoadOptions.header_columns_count`](/cells/python-net/ru/aspose.cells/txtloadoptions#header_columns_count)).
Максимальное значение — это ограничение столбца соответствующего формата файла, например, для файла xlsx — 16384.
Если это свойство не указано или указанное значение не является положительным, то будет использоваться и максимальный предел.
###  Определение:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`TxtLoadOptions`](/cells/python-net/ru/aspose.cells/txtloadoptions)
