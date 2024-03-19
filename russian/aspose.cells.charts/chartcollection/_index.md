---
title: ChartCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 60
url: /ru/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection класс
Инкапсулирует коллекцию из [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart) объектов.



Тип ChartCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.charts/chartcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Добавляет диаграмму с предустановленным шаблоном.|
| [add](/cells/python-net/ru/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-bool-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [get](/cells/python-net/ru/aspose.cells.charts/chartcollection/get/#int) | Добавьте API for Python через .Net.так как этот[int index] не поддерживается.|
| [get](/cells/python-net/ru/aspose.cells.charts/chartcollection/get/#str) | Добавьте API for Python через .Net.поскольку эта [строковая диаграмма] не поддерживается.|
| [copy_to](/cells/python-net/ru/aspose.cells.charts/chartcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [add_floating_chart](/cells/python-net/ru/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.ChartType-int-int-int-int) | Добавляет диаграмму в коллекцию.|
| [binary_search](/cells/python-net/ru/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.Chart) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Смотрите также
* модуль [`aspose.cells.charts`](..)
* класс [`Chart`](/cells/python-net/ru/aspose.cells.charts/chart)
