---
title: remove_at метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells/commentcollection/remove_at/
is_root: false
---
##  remove_at(self, cell_name) {#str}
Удаляет комментарий к определенной ячейке.



```python

def remove_at(self, cell_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_name | str | Имя ячейки, содержащей комментарий.|

###  Пример

```python

comments.remove_at("B2")

```


##  remove_at(self, row, column) {#int-int}
Удаляет комментарий к определенной ячейке.



```python

def remove_at(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки.|
| column | int | индекс столбца.|

###  Пример

```python

comments.remove_at(1, 1)

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CommentCollection`](/cells/python-net/ru/aspose.cells/commentcollection)
