---
title: max_column_count недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 270
url: /ru/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count недвижимость

Максимальное количество столбцов, которые можно импортировать для одного листа.

###  Примечания

Столбцы, превышающие этот лимит, будут игнорироваться.
или продлен до следующего листа согласно [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/ru/aspose.cells/txtloadoptions#extend_to_next_sheet).
В это число входят столбцы заголовков ([`TxtLoadOptions.header_columns_count`](/cells/python-net/ru/aspose.cells/txtloadoptions#header_columns_count)).
Максимальное значение — это предел числа столбцов соответствующего формата файла, например, для файла xlsx это 16384.
Если это свойство не указано или указанное значение не является положительным, то будет использоваться также максимальный предел.
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
