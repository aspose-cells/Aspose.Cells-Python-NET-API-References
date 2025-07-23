---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
Добавляет диаграмму в коллекцию.


###  Возврат

Индекс объекта [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart).


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/ru/aspose.cells.charts/charttype) | Тип диаграммы|
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| lower_right_row | int | Индекс нижней правой строки|
| lower_right_column | int | Индекс нижнего правого столбца|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
Добавляет диаграмму в коллекцию.


###  Возврат

Индекс объекта [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart).


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/ru/aspose.cells.charts/charttype) | Тип диаграммы|
| data_range | str | Задает диапазон данных диаграммы|
| top_row | int | Указатель верхнего левого ряда.|
| left_column | int | Индекс верхнего левого столбца.|
| right_row | int | Индекс нижней правой строки|
| bottom_column | int | Индекс нижнего правого столбца|
###  Примечания

ПРИМЕЧАНИЕ: Этот элемент устарел. Вместо этого,
пожалуйста, используйте свойство [`ChartCollection.add`](/cells/python-net/ru/aspose.cells.charts/chartcollection/add).
 Эта недвижимость будет снесена через 12 месяцев с мая 2022 года.
Aspose приносит извинения за любые причиненные вам неудобства.

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
Добавляет диаграмму с предустановленным шаблоном.


###  Возврат

Индекс объекта [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart).


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| data | bytes | Данные файла шаблона диаграммы (.crtx).|
| data_range | str | Задает диапазон данных диаграммы|
| is_vertical | bool | Указывает, следует ли отображать ряд из диапазона значений ячеек по строкам или по столбцам.|
| top_row | int | Указатель верхнего левого ряда.|
| left_column | int | Индекс верхнего левого столбца.|
| right_row | int | Индекс нижней правой строки|
| bottom_column | int | Индекс нижнего правого столбца|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
Добавляет диаграмму в коллекцию.


###  Возврат

Индекс объекта [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart).


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/ru/aspose.cells.charts/charttype) | Тип диаграммы|
| data_range | str | Задает диапазон данных диаграммы|
| is_vertical | bool | Указывает, следует ли отображать ряд из диапазона значений ячеек по строкам или по столбцам.|
| top_row | int | Указатель верхнего левого ряда.|
| left_column | int | Индекс верхнего левого столбца.|
| right_row | int | Индекс нижней правой строки|
| bottom_column | int | Индекс нижнего правого столбца|



###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart)
* класс [`ChartCollection`](/cells/python-net/ru/aspose.cells.charts/chartcollection)
