---
title: freeze_panes метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 140
url: /ru/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Закрепляет области в указанной ячейке рабочего листа.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_name | str | Cell имя.|
| freezed_rows | int | Количество видимых строк в верхней панели, не более индекса строки.|
| freezed_columns | int | Количество видимых столбцов в левой панели, не более индекса столбца.|
###  Примечания

Индекс строки и индекс столбца не могут быть равны нулю одновременно. Количество строк и количество столбцов.
также не могут все быть равны нулю.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Закрепляет области в указанной ячейке рабочего листа.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки.|
| column | int | Индекс столбца.|
| freezed_rows | int | Количество видимых строк в верхней панели, не более индекса строки.|
| freezed_columns | int | Количество видимых столбцов в левой панели, не более индекса столбца.|
###  Примечания

Индекс строки и индекс столбца не могут быть равны нулю одновременно. Количество строк и количество столбцов.
также не могут все быть равны нулю.


Первые два параметра определяют положение замороженного изображения, а последние два параметра определяют область замороженного изображения на левой верхней панели.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
