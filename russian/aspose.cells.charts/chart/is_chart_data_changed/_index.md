---
title: is_chart_data_changed метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Определяет, изменился ли источник данных диаграммы.


###  Возврат

Возвращает true, если диаграмма изменилась, в противном случае возвращает false.


```python

def is_chart_data_changed(self):
    ...
```


###  Примечания

Метод обнаруживает изменения в источнике данных диаграммы перед ее преобразованием в формат изображения.
При первом вызове Chart.toImage будут записаны исходные данные диаграммы (например, XValuesParseData, ValuesParseData).
Перед повторным вызовом метода Chart.toImage вызовите метод IsChartDataChanged, чтобы проверить, требуется ли повторная отрисовка Chart.


###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart)
