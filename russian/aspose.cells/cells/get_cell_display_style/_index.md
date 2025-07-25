---
title: get_cell_display_style метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 320
url: /ru/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Получить стиль отображения заданной ячейки.


###  Возврат

стиль отображения данной ячейки.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | индекс строки данной ячейки|
| column | int | столбец данной ячейки|
###  Примечания

То же самое с [`Cell.get_display_style`](/cells/python-net/ru/aspose.cells/cell/get_display_style),
и то же самое с использованием [`BorderType.SIDE_BORDERS`](/cells/python-net/ru/aspose.cells/bordertype#SIDE_BORDERS)
для [`Cells.get_cell_display_style`](/cells/python-net/ru/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Получить стиль отображения заданной ячейки.


###  Возврат

стиль отображения данной ячейки.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | индекс строки данной ячейки|
| column | int | столбец данной ячейки|
| adjacent_borders | [`BorderType`](/cells/python-net/ru/aspose.cells/bordertype) | Указывает, какие границы необходимо проверить и скорректировать в соответствии с границами соседних ячеек.<br/>Пожалуйста, смотрите описание для того же параметра<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Примечания

Если на ячейку также влияют другие настройки, такие как условное форматирование, объекты списка и т. д.,
то стиль отображения может отличаться от [`Cells.get_cell_style`](/cells/python-net/ru/aspose.cells/cells/get_cell_style).
И поскольку эти настройки также могут быть применены к пустым (несуществующим) ячейкам,
Использование этого метода позволяет избежать создания пустых ячеек.
поэтому производительность будет лучше, чем при получении экземпляра Cell из Cells
и затем позвонить по номеру [`Cell.get_display_style`](/cells/python-net/ru/aspose.cells/cell/get_display_style).


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
