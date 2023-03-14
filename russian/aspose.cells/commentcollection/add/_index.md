---
title: add метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/commentcollection/add/
is_root: false
---
##  add(cell_name) {#str}
Добавляет комментарий к коллекции.


###  Возвращает

[Comment](/cells/python-net/ru/aspose.cells/comment) индекс объекта.


```python
def add(self, cell_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_name | str | Cell имя.|

###  Пример

```python

commentIndex2 = comments.add("B2")
comment2 = comments[commentIndex2]
comment2.note = "Second note."
comment2.font.name = "Times New Roman"

```


##  add(row, column) {#int-int}
Добавляет комментарий к коллекции.


###  Возвращает

[Comment](/cells/python-net/ru/aspose.cells/comment) индекс объекта.


```python
def add(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Cell индекс строки.|
| column | int | Cell индекс столбца.|

###  Пример

```python

commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"

```



###  Смотрите также
* модуль [aspose.cells](../../)
* класс [Comment](/cells/python-net/ru/aspose.cells/comment)
* класс [CommentCollection](/cells/python-net/ru/aspose.cells/commentcollection)
