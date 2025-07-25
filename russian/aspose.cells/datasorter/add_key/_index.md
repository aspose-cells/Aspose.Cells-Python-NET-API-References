---
title: add_key метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/datasorter/add_key/
is_root: false
---
##  add_key(self, key, order) {#int-aspose.cells.SortOrder}
Добавляет отсортированный индекс столбца и порядок сортировки.



```python

def add_key(self, key, order):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| key | int | Индекс отсортированного столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...)|
| order | [`SortOrder`](/cells/python-net/ru/aspose.cells/sortorder) | Порядок сортировки|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-str}
Добавляет отсортированный индекс столбца и порядок сортировки с помощью настраиваемого списка сортировки.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| key | int | Индекс отсортированного столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...)|
| order | [`SortOrder`](/cells/python-net/ru/aspose.cells/sortorder) | Порядок сортировки.|
| custom_list | str | Список пользовательской сортировки.|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-list}
Добавляет отсортированный индекс столбца и порядок сортировки с помощью настраиваемого списка сортировки.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| key | int | Индекс отсортированного столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...)|
| order | [`SortOrder`](/cells/python-net/ru/aspose.cells/sortorder) | Порядок сортировки.|
| custom_list | list | Список пользовательской сортировки.|


##  add_key(self, key, type, order, custom_list) {#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any}
Добавляет отсортированный индекс столбца и порядок сортировки с помощью настраиваемого списка сортировки.



```python

def add_key(self, key, type, order, custom_list):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| key | int | Индекс отсортированного столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...)|
| type | [`SortOnType`](/cells/python-net/ru/aspose.cells/sortontype) | Тип сортированного значения.|
| order | [`SortOrder`](/cells/python-net/ru/aspose.cells/sortorder) | Порядок сортировки.|
| custom_list | any | Список пользовательской сортировки.|
###  Примечания

Если тип — SortOnType.CellColor или SortOnType.FontColor, то customList — Color.


###  Смотрите также

* модуль [`aspose.cells`](../../)
* класс [`DataSorter`](/cells/python-net/ru/aspose.cells/datasorter)
