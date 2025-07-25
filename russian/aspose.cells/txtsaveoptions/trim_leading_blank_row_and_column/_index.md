---
title: trim_leading_blank_row_and_column недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 230
url: /ru/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column недвижимость

Указывает, следует ли обрезать начальные пустые строки и столбцы, как это делает MS Excel.
Значение по умолчанию — true.

###  Примечания

То же самое с правилом в MS Excel: строка/столбец не будут считаться пустыми, если у них есть пользовательский стиль,
даже если он не содержит данных о ячейках.
При сохранении в режиме LightCells эта опция не действует.
Пользователь должен контролировать выходной диапазон путем реализации [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/ru/aspose.cells/txtsaveoptions)
или указав [`TxtSaveOptions.export_area`](/cells/python-net/ru/aspose.cells/txtsaveoptions#export_area)
###  Определение:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`TxtSaveOptions`](/cells/python-net/ru/aspose.cells/txtsaveoptions)
