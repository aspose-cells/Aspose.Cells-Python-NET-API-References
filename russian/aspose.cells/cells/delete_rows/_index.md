---
title: delete_rows метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 260
url: /ru/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows {#int-int}
Удаляет несколько строк.



```python
def delete_rows(self, row_index, total_rows):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс первой строки, который нужно удалить.|
| total_rows | int | Количество строк, которые необходимо удалить.|
###  Примечания

Если удаленный диапазон содержит верхнюю часть (не всю) таблицы (ListObject),
дальний бой невозможно удалить, и ничего не будет сделано.
Аналогично это работает и с MS Excel.

##  delete_rows {#int-int-bool}
Удаляет несколько строк на листе.


###  Возврат




```python
def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс первой удаляемой строки.|
| total_rows | int | Количество строк, которые необходимо удалить.|
| update_reference | bool | Указывает, обновляются ли ссылки на других листах.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
