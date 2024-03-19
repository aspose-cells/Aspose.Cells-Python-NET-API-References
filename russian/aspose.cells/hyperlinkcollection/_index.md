---
title: HyperlinkCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 850
url: /ru/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection класс
Инкапсулирует коллекцию из [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink) объектов.



Тип HyperlinkCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/hyperlinkcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Добавляет гиперссылку в указанную ячейку или диапазон ячеек.|
| [add](/cells/python-net/ru/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Добавляет гиперссылку в указанную ячейку или диапазон ячеек.|
| [add](/cells/python-net/ru/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Добавляет гиперссылку в указанную ячейку или диапазон ячеек.|
| [copy_to](/cells/python-net/ru/aspose.cells/hyperlinkcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [binary_search](/cells/python-net/ru/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink)
