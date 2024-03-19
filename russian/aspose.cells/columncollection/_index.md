---
title: ColumnCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 280
url: /ru/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection класс
Коллекция объектов [`Column`](/cells/python-net/ru/aspose.cells/column), которые представляют отдельные столбцы (настройки) на листе.
Объект Column представляет только такие настройки, как ширина столбца, стили и т. д. для всего столбца,
не имеет ничего общего с тем, что в соответствующем столбце есть непустые ячейки (данные) или нет.
И «Count» этой коллекции представляет только количество объектов Column, экземпляры которых были созданы в этой коллекции,
не имеет ничего общего с тем, есть ли на листе непустые ячейки (данные) или нет.



Тип ColumnCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/columncollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [copy_to](/cells/python-net/ru/aspose.cells/columncollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/columncollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/columncollection/index_of/#aspose.cells.Column-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/columncollection/index_of/#aspose.cells.Column-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/columncollection/last_index_of/#aspose.cells.Column) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [get_by_index](/cells/python-net/ru/aspose.cells/columncollection/get_by_index/#int) | Получает объект столбца по индексу.|
| [get_column_by_index](/cells/python-net/ru/aspose.cells/columncollection/get_column_by_index/#int) | Получает объект [`Column`](/cells/python-net/ru/aspose.cells/column) по позиции в списке.|
| [binary_search](/cells/python-net/ru/aspose.cells/columncollection/binary_search/#aspose.cells.Column) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Column`](/cells/python-net/ru/aspose.cells/column)
