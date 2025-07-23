---
title: characters метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/cell/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Возвращает объект Characters, представляющий диапазон characters в тексте ячейки.


###  Возврат

Персонажи возражают.


```python

def characters(self, start_index, length):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start_index | int | Индекс начала символа.|
| length | int | Количество символов.|
###  Примечания

Этот метод работает только с ячейками со строковым значением.
###  Пример


```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("A1").put_value("Helloworld")
cells.get("A1").characters(5, 5).font.is_bold = True
cells.get("A1").characters(5, 5).font.color = Color.blue

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
