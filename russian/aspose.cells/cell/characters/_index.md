---
title: characters метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 30
url: /ru/aspose.cells/cell/characters/
is_root: false
---
##  characters(start_index, length) {#int-int}
Возвращает объект символов, представляющий диапазон characters в тексте ячейки.


###  Возвращает

Возражают персонажи.


```python
def characters(self, start_index, length):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start_index | int | Индекс начала персонажа.|
| length | int | Количество символов.|
###  Примечания

Этот метод работает только с ячейкой со строковым значением.
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
* модуль [aspose.cells](../../)
* класс [Cell](/cells/python-net/ru/aspose.cells/cell)
