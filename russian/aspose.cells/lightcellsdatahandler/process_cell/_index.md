---
title: process_cell метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/lightcellsdatahandler/process_cell/
is_root: false
---
##  process_cell(cell) {#Cell}
Начинает обрабатывать одну ячейку.


###  Возвращает

нужно ли сохранять эту ячейку в ячейках модели текущего листа.
Обычно он должен быть ложным, чтобы все ячейки не сохранялись в памяти после обработки, а затем память сохранялась.
Для некоторых специальных целей, таких как пользователь должен получить доступ к некоторым ячейкам позже после обработки всей книги,
пользователь может заставить этот метод возвращать значение true, чтобы сохранить эти специальные ячейки в модели Cells и получить к ним доступ позже с помощью API, таких как Cells [строка, столбец].
Однако для хранения данных ячеек в модели Cells потребуется больше памяти, и если все ячейки сохранены, то чтение файла шаблона
в режиме LightCells станет таким же, как при обычном чтении.


```python
def process_cell(self, cell):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell | [Cell](/cells/python-net/ru/aspose.cells/cell) | Cell объект, который обрабатывается в данный момент|
###  Примечания

Он будет вызван после того, как будут прочитаны данные одной ячейки.


###  Смотрите также

* модуль [aspose.cells](../../)
* класс [LightCellsDataHandler](/cells/python-net/ru/aspose.cells/lightcellsdatahandler)
