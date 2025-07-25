---
title: max_row_count недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 280
url: /ru/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count недвижимость

Максимальное количество строк, которые можно импортировать для одного листа.

###  Примечания

Строки, превышающие этот лимит, будут игнорироваться.
или продлен до следующего листа согласно [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/ru/aspose.cells/txtloadoptions#extend_to_next_sheet).
В это число входят строки заголовков ([`TxtLoadOptions.header_rows_count`](/cells/python-net/ru/aspose.cells/txtloadoptions#header_rows_count)).
Максимально допустимое значение — это ограничение по количеству строк соответствующего формата файла, например, для файла xlsx это 1048576.
Если это свойство не указано или указанное значение не является положительным, то будет использоваться также максимальный предел.
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
