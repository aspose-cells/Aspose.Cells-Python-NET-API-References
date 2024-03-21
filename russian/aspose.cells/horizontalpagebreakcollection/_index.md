---
title: HorizontalPageBreakCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 790
url: /ru/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection класс
Инкапсулирует коллекцию из [`HorizontalPageBreak`](/cells/python-net/ru/aspose.cells/horizontalpagebreak) объектов.



Тип HorizontalPageBreakCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) |Добавляет горизонтальный разрыв страницы в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#int) |Добавляет горизонтальный разрыв страницы в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#int-int) |Добавляет горизонтальный разрыв страницы в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/add/#str) |Добавляет горизонтальный разрыв страницы в коллекцию.|
| [copy_to](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [binary_search](/cells/python-net/ru/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.HorizontalPageBreak) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



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
