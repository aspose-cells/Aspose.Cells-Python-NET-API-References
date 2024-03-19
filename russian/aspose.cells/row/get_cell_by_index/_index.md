---
title: get_cell_by_index метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 50
url: /ru/aspose.cells/row/get_cell_by_index/
is_root: false
---
##  get_cell_by_index {#int}
Получите ячейку по определенному индексу в коллекции ячеек этой строки.


###  Возврат

Объект Cell в данной позиции.


```python
def get_cell_by_index(self, index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int | Индекс (позиция) ячейки в коллекции ячеек этой строки.|
###  Примечания

Чтобы последовательно пройти все ячейки без изменений,
использование [`Row.get_enumerator`](/cells/python-net/ru/aspose.cells/row/get_enumerator) даст лучшую производительность, чем использование этого метода для получения ячеек одну за другой.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Row`](/cells/python-net/ru/aspose.cells/row)
