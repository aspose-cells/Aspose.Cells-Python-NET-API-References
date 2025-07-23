---
title: Name класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1000
url: /ru/aspose.cells/name/
is_root: false
---
##  Name класс
Представляет определенное имя для диапазона ячеек.



Тип Name предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [comment](/cells/python-net/ru/aspose.cells/name/comment) | Получает и задает комментарий к имени.<br/> Применимо только к Excel 2007 и более поздним версиям.|
| [text](/cells/python-net/ru/aspose.cells/name/text) | Получает текст имени объекта.|
| [full_text](/cells/python-net/ru/aspose.cells/name/full_text) | Получает полный текст имени объекта с настройкой области действия.|
| [refers_to](/cells/python-net/ru/aspose.cells/name/refers_to) | Возвращает или задает формулу, на которую ссылается имя, начиная со знака равенства.|
| [r1c1_refers_to](/cells/python-net/ru/aspose.cells/name/r1c1_refers_to) |Получает или задает ссылку R1C1 для [`Name`](/cells/python-net/ru/aspose.cells/name).|
| [is_referred](/cells/python-net/ru/aspose.cells/name/is_referred) | Указывает, упоминается ли это имя в других формулах.|
| [is_visible](/cells/python-net/ru/aspose.cells/name/is_visible) | Указывает, видимо ли имя.|
| [sheet_index](/cells/python-net/ru/aspose.cells/name/sheet_index) | Указывает, что это имя принадлежит рабочей книге или рабочему листу.<br/> 0 = Глобальное имя, в противном случае индекс листа (начиная с единицы)|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_refers_to(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/name/get_refers_to/#bool-bool) | Получите ссылку на это имя.|
| [`get_refers_to(self, is_r1c1, is_local, row, column)`](/cells/python-net/ru/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Получить ссылку на это имя на основе указанной ячейки.|
| [`get_ranges(self)`](/cells/python-net/ru/aspose.cells/name/get_ranges/#) | Получает все диапазоны, на которые ссылается это имя.|
| [`get_ranges(self, recalculate)`](/cells/python-net/ru/aspose.cells/name/get_ranges/#bool) | Получает все диапазоны, на которые ссылается это имя.|
| [`get_range(self)`](/cells/python-net/ru/aspose.cells/name/get_range/#) | Возвращает диапазон, если это имя ссылается на диапазон.|
| [`get_range(self, recalculate)`](/cells/python-net/ru/aspose.cells/name/get_range/#bool) | Получает диапазон, если это имя относится к диапазону|
| [`get_range(self, sheet_index, row, column)`](/cells/python-net/ru/aspose.cells/name/get_range/#int-int-int) | Возвращает диапазон, если это имя ссылается на диапазон.<br/> Если ссылка на это имя не является абсолютной, диапазон может быть разным для разных ячеек.|
| [`set_refers_to(self, refers_to, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/name/set_refers_to/#str-bool-bool) | Установите ссылку на это имя.|
| [`get_referred_areas(self, recalculate)`](/cells/python-net/ru/aspose.cells/name/get_referred_areas/#bool) | Получает все ссылки, на которые ссылается это имя.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating a named range
range = worksheet.cells.create_range("B4", "G14")
# Setting the name of the named range
range.name = "TestRange"
# Saving the modified Excel file in default (that is Excel 2000) format
workbook.save("output.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Name`](/cells/python-net/ru/aspose.cells/name)
