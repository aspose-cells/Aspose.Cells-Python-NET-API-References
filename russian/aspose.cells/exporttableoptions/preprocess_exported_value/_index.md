---
title: preprocess_exported_value метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value(self, cell_row, cell_column, value) {#int-int-aspose.cells.CellValue}
Предварительно обработать значение текущей ячейки для экспорта.


###  Возврат

Была ли текущая ячейка заменена другим типом и/или значением.


```python

def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_row | int | индекс строки текущей ячейки|
| cell_column | int | индекс столбца ячейки|
| value | [`CellValue`](/cells/python-net/ru/aspose.cells/cellvalue) | значение и тип текущей ячейки|
###  Примечания

Индекс строки и столбца — это абсолютный индекс ячейки на листе, а не индекс в экспортированной таблице.
Пользователь может проверить значение текущей ячейки в переопределенной реализации этого метода,
если текущую ячейку необходимо заменить другим типом и значением,
здесь реализация должна установить ожидаемый тип и значение для объекта CellValue и вернуть true.
По умолчанию этот метод ничего не делает и возвращает false.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`ExportTableOptions`](/cells/python-net/ru/aspose.cells/exporttableoptions)
