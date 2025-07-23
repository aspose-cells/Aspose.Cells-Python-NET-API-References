---
title: delete_rows метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 260
url: /ru/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Удаляет несколько строк.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Первый индекс строки, подлежащей удалению.|
| total_rows | int | Количество строк, подлежащих удалению.|
###  Примечания

Если удаленный диапазон содержит верхнюю часть (не всю) таблицы (ListObject),
удаленный объект не может быть удален, и ничего не будет сделано.
Аналогично работает и с MS Excel.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
Удаляет несколько строк на листе.


###  Возврат




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс первой строки, подлежащей удалению.|
| total_rows | int | Количество строк, подлежащих удалению.|
| update_reference | bool | Указывает, следует ли обновлять ссылки на других листах.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Удаляет несколько строк на листе.


###  Возврат




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс первой строки, подлежащей удалению.|
| total_rows | int | Количество строк, подлежащих удалению.|
| options | [`DeleteOptions`](/cells/python-net/ru/aspose.cells/deleteoptions) | Варианты операции удаления|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
