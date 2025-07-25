---
title: Slicer класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.slicers/slicer/
is_root: false
---
##  Slicer класс
краткое описание Slicer Вид



Тип Slicer предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [title](/cells/python-net/ru/aspose.cells.slicers/slicer/title) | Задает заголовок текущего объекта слайсера.|
| [alternative_text](/cells/python-net/ru/aspose.cells.slicers/slicer/alternative_text) | Возвращает или задает описательную (альтернативную) текстовую строку объекта Slicer.|
| [is_printable](/cells/python-net/ru/aspose.cells.slicers/slicer/is_printable) | Указывает, можно ли распечатать объект среза.|
| [is_locked](/cells/python-net/ru/aspose.cells.slicers/slicer/is_locked) | Указывает, заблокирована ли форма среза.|
| [placement](/cells/python-net/ru/aspose.cells.slicers/slicer/placement) | Представляет собой способ присоединения объекта рисунка к ячейкам под ним.<br/> Свойство управляет размещением объекта на рабочем листе.|
| [locked_aspect_ratio](/cells/python-net/ru/aspose.cells.slicers/slicer/locked_aspect_ratio) | Указывает, заблокировано ли соотношение сторон.|
| [locked_position](/cells/python-net/ru/aspose.cells.slicers/slicer/locked_position) |Указывает, можно ли перемещать или изменять размер указанного слайсера с помощью пользовательского интерфейса.|
| [shape](/cells/python-net/ru/aspose.cells.slicers/slicer/shape) | Возвращает объект Shape, связанный с указанным срезом. Только для чтения.|
| [slicer_cache](/cells/python-net/ru/aspose.cells.slicers/slicer/slicer_cache) | Возвращает объект SlicerCache, связанный со слайсером. Только для чтения.|
| [parent](/cells/python-net/ru/aspose.cells.slicers/slicer/parent) | Возвращает объект [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet), содержащий этот срез. Только для чтения.|
| [style_type](/cells/python-net/ru/aspose.cells.slicers/slicer/style_type) | Укажите тип стиля встроенного слайсера<br/> тип по умолчанию — SlicerStyleLight1|
| [name](/cells/python-net/ru/aspose.cells.slicers/slicer/name) | Возвращает или задает имя указанного слайсера|
| [caption](/cells/python-net/ru/aspose.cells.slicers/slicer/caption) | Возвращает или задает заголовок указанного слайсера.|
| [caption_visible](/cells/python-net/ru/aspose.cells.slicers/slicer/caption_visible) | Возвращает или задает видимость заголовка, отображающего подпись среза.<br/> значение по умолчанию — true|
| [number_of_columns](/cells/python-net/ru/aspose.cells.slicers/slicer/number_of_columns) | Возвращает или задает количество столбцов в указанном срезе.|
| [left_pixel](/cells/python-net/ru/aspose.cells.slicers/slicer/left_pixel) | Возвращает или задает горизонтальное смещение фигуры среза от ее левого столбца в пикселях.|
| [top_pixel](/cells/python-net/ru/aspose.cells.slicers/slicer/top_pixel) | Возвращает или задает вертикальное смещение фигуры среза от ее верхней строки в пикселях.|
| [width](/cells/python-net/ru/aspose.cells.slicers/slicer/width) | Возвращает или задает ширину указанного среза в пунктах.|
| [width_pixel](/cells/python-net/ru/aspose.cells.slicers/slicer/width_pixel) |Возвращает или задает ширину указанного слайсера в пикселях.|
| [height](/cells/python-net/ru/aspose.cells.slicers/slicer/height) | Возвращает или задает высоту указанного среза в пунктах.|
| [height_pixel](/cells/python-net/ru/aspose.cells.slicers/slicer/height_pixel) | Возвращает или задает высоту указанного среза в пикселях.|
| [column_width_pixel](/cells/python-net/ru/aspose.cells.slicers/slicer/column_width_pixel) | Возвращает или задает ширину каждого столбца в слайсере в пикселях.|
| [column_width](/cells/python-net/ru/aspose.cells.slicers/slicer/column_width) | Возвращает или задает ширину каждого столбца в срезе в пунктах.|
| [row_height_pixel](/cells/python-net/ru/aspose.cells.slicers/slicer/row_height_pixel) | Возвращает или задает высоту в пикселях каждой строки в указанном срезе.|
| [row_height](/cells/python-net/ru/aspose.cells.slicers/slicer/row_height) | Возвращает или задает высоту в пунктах каждой строки в указанном срезе.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add_pivot_connection(self, pivot)`](/cells/python-net/ru/aspose.cells.slicers/slicer/add_pivot_connection/#aspose.cells.pivot.pivottable) | Добавляет подключение к сводной таблице.|
| [`remove_pivot_connection(self, pivot)`](/cells/python-net/ru/aspose.cells.slicers/slicer/remove_pivot_connection/#aspose.cells.pivot.pivottable) | Удаляет подключение к сводной таблице.|
| [`refresh(self)`](/cells/python-net/ru/aspose.cells.slicers/slicer/refresh/#) | Обновление среза. Тем временем обновление и расчет относительных сводных таблиц.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
items = slicer.slicer_cache.slicer_cache_items
item = items[0]
item.selected = False
# do your business
book.save("out.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.slicers`](..)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
