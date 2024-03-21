---
title: get_cell метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 310
url: /ru/aspose.cells/cells/get_cell/
is_root: false
---
##  get_cell {#int-int}
Получает элемент [`Cell`](/cells/python-net/ru/aspose.cells/cell) или значение NULL по указанному индексу строки ячейки и индексу столбца.


###  Возврат

Возвращает объект Cell, если объект Cell существует.
Верните ноль, если ячейка не существует.


```python
def get_cell(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки|
| column | int | Индекс столбца|
###  Примечания

ПРИМЕЧАНИЕ. Этот элемент устарел. Вместо,
используйте метод CheckCell(int row, int columns).
 Этот метод будет удален через 12 месяцев, с февраля 2024 года.
Aspose приносит извинения за возможные неудобства.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
