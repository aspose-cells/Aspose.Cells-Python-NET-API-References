---
title: max_row_count недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 300
url: /ru/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count недвижимость

Максимальное количество строк, которые можно импортировать на один лист.

###  Примечания

Строки, превышающие этот предел, будут игнорироваться.
или продлен на следующий лист по номеру [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/ru/aspose.cells/txtloadoptions#extend_to_next_sheet).
Это количество включает строки заголовка ([`TxtLoadOptions.header_rows_count`](/cells/python-net/ru/aspose.cells/txtloadoptions#header_rows_count)).
Максимально допустимое значение — это ограничение строки соответствующего формата файла, например, для файла xlsx — 1048576.
Если это свойство не указано или указанное значение не является положительным, то будет использоваться и максимальный предел.
###  Определение:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`TxtLoadOptions`](/cells/python-net/ru/aspose.cells/txtloadoptions)
