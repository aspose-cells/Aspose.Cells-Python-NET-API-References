---
title: QueryTable класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 1230
url: /ru/aspose.cells/querytable/
is_root: false
---
##  QueryTable класс
Представляет информацию QueryTable.



Тип QueryTable предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [connection_id](/cells/python-net/ru/aspose.cells/querytable/connection_id) |Получает идентификатор соединения таблицы запроса.|
| [external_connection](/cells/python-net/ru/aspose.cells/querytable/external_connection) | Получает связанное внешнее соединение.|
| [name](/cells/python-net/ru/aspose.cells/querytable/name) | Получает имя запрашиваемой таблицы.|
| [result_range](/cells/python-net/ru/aspose.cells/querytable/result_range) | Получает диапазон результата.|
| [preserve_formatting](/cells/python-net/ru/aspose.cells/querytable/preserve_formatting) | Возвращает или задает PreserveFormatting объекта.|
| [adjust_column_width](/cells/python-net/ru/aspose.cells/querytable/adjust_column_width) | Возвращает или задает AdjustColumnWidth объекта.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Getting the first query table in the worksheet
qt = worksheet.query_tables[0]
# Getting display address of the query table.
address = qt.result_range.address

```

###  Смотрите также
* модуль [aspose.cells](..)
