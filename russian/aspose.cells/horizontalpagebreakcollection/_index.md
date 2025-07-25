---
title: HorizontalPageBreakCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 770
url: /ru/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection класс
Инкапсулирует коллекцию из [`HorizontalPageBreak`](/cells/python-net/ru/aspose.cells/horizontalpagebreak) объектов.



Тип HorizontalPageBreakCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, row, start_column, end_column)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) | Добавляет горизонтальный разрыв страницы в коллекцию.|
| [`add(self, row)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#int) | Добавляет горизонтальный разрыв страницы в коллекцию.|
| [`add(self, row, column)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#int-int) | Добавляет горизонтальный разрыв страницы в коллекцию.|
| [`add(self, cell_name)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#str) | Добавляет горизонтальный разрыв страницы в коллекцию.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get(self, cell_name)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/get/#str) | Получает элемент [`HorizontalPageBreak`](/cells/python-net/ru/aspose.cells/horizontalpagebreak) с указанным именем ячейки.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.horizontalpagebreak) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`HorizontalPageBreak`](/cells/python-net/ru/aspose.cells/horizontalpagebreak)
