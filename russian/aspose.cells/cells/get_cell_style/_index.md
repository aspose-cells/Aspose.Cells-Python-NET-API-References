---
title: get_cell_style метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 330
url: /ru/aspose.cells/cells/get_cell_style/
is_root: false
---
##  get_cell_style(self, row, column) {#int-int}
Получить стиль заданной ячейки.


###  Возврат

стиль данной ячейки.


```python

def get_cell_style(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | индекс строки|
| column | int | столбец|
###  Примечания

Возвращаемый стиль — это только тот, который установлен для ячейки или унаследован от строки/столбца ячейки.
не включает примененные свойства других настроек, такие как условное форматирование.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
