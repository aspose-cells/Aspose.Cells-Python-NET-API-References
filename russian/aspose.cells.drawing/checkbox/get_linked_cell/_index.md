---
title: get_linked_cell метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 120
url: /ru/aspose.cells.drawing/checkbox/get_linked_cell/
is_root: false
---
##  get_linked_cell(self, is_r1c1, is_local) {#bool-bool}
Возвращает диапазон, связанный со значением элемента управления.


###  Возврат

Диапазон, связанный со значением элемента управления.


```python

def get_linked_cell(self, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_r1c1 | bool | Необходимо ли форматировать формулу как R1C1.|
| is_local | bool | Необходимо ли форматировать формулу в соответствии с локалью.|

###  Пример

```python

# You may get results like '$A$1'
link = shape.get_linked_cell(False, False)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`CheckBox`](/cells/python-net/ru/aspose.cells.drawing/checkbox)
