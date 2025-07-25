---
title: calculate_data метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
Рассчитывает данные сводной таблицы по ячейкам.



```python

def calculate_data(self):
    ...
```


###  Примечания

Cell. Значение в диапазоне опорных точек не может вернуть правильный результат, если метод не был вызван.
Этот метод вычисляет данные с использованием внутреннего кэша, а не исходного источника данных.
Поэтому, если источник данных изменился, сначала вызовите метод RefreshData().

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
Расчет сводных таблиц с параметрами



```python

def calculate_data(self, option):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/ru/aspose.cells.pivot/pivottablecalculateoption) |  |



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotTable`](/cells/python-net/ru/aspose.cells.pivot/pivottable)
