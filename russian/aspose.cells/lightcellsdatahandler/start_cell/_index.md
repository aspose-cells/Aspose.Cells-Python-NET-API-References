---
title: start_cell метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 40
url: /ru/aspose.cells/lightcellsdatahandler/start_cell/
is_root: false
---
##  start_cell(column_index) {#int}
Готовится к обработке ячейки.


###  Возвращает

нужно ли обрабатывать эту ячейку. false, чтобы игнорировать ячейку и проверять следующую, пока не будут достигнуты данные ячеек текущей строки


```python
def start_cell(self, column_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| column_index | int | индекс столбца ячейки для обработки|
###  Примечания

Он будет вызываться при достижении существующей ячейки в текущей строке. Текущая строка — это строка последнего звонка [LightCellsDataHandler.process_row(row)](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/process_row).


###  Смотрите также

* модуль [aspose.cells](../../)
* класс [LightCellsDataHandler](/cells/python-net/ru/aspose.cells/lightcellsdatahandler)
