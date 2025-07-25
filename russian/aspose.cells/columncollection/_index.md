---
title: ColumnCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 250
url: /ru/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection класс
Коллекция объектов [`Column`](/cells/python-net/ru/aspose.cells/column), представляющих отдельные столбцы (настройки) на рабочем листе.
Объект «Столбец» представляет только настройки, такие как ширина столбца, стили и т. д. для всего столбца.
не имеет никакого отношения к тому факту, что есть непустые ячейки (данные) или их нет в соответствующем столбце.
И «Количество» этой коллекции представляет собой только количество объектов-столбцов, которые были созданы в этой коллекции,
не имеет никакого отношения к тому факту, есть ли на листе непустые ячейки (данные) или нет.



Тип ColumnCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/columncollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/columncollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/columncollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get_by_index(self, index)`](/cells/python-net/ru/aspose.cells/columncollection/get_by_index/#int) | Получает объект столбца по индексу.|
| [`get_column_by_index(self, index)`](/cells/python-net/ru/aspose.cells/columncollection/get_column_by_index/#int) | Получает объект [`Column`](/cells/python-net/ru/aspose.cells/column) по позиции в списке.|
| [`get(self, column_index)`](/cells/python-net/ru/aspose.cells/columncollection/get/#int) | Добавить API for Python Через .Net.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



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
