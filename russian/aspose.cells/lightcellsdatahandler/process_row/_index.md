---
title: process_row метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 30
url: /ru/aspose.cells/lightcellsdatahandler/process_row/
is_root: false
---
##  process_row(row) {#Row}
Начинает обрабатывать одну строку.


###  Возвращает

нужно ли обрабатывать ячейки этой строки. false, чтобы игнорировать все ячейки в этой строке.


```python
def process_row(self, row):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | [Row](/cells/python-net/ru/aspose.cells/row) | Объект строки, который обрабатывается в данный момент.|
###  Примечания

Он будет вызываться после свойств строки, таких как высота, стиль и т. д. были прочитаны. Однако ячейки в этой строке еще не были прочитаны.


###  Смотрите также

* модуль [aspose.cells](../../)
* класс [LightCellsDataHandler](/cells/python-net/ru/aspose.cells/lightcellsdatahandler)
