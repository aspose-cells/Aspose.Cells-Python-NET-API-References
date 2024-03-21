---
title: Column класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 270
url: /ru/aspose.cells/column/
is_root: false
---
##  Column класс
Представляет один столбец на листе.



Тип Column предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [index](/cells/python-net/ru/aspose.cells/column/index) | Получает индекс этого столбца.|
| [width](/cells/python-net/ru/aspose.cells/column/width) | Получает и задает ширину столбца в символах.|
| [group_level](/cells/python-net/ru/aspose.cells/column/group_level) | Получает уровень группы столбца.|
| [is_hidden](/cells/python-net/ru/aspose.cells/column/is_hidden) | Указывает, скрыт ли столбец.|
| [has_custom_style](/cells/python-net/ru/aspose.cells/column/has_custom_style) | Указывает, имеет ли этот столбец пользовательские настройки стиля (отличные от стиля по умолчанию, унаследованного из книги).|
| [style](/cells/python-net/ru/aspose.cells/column/style) | Получает стиль этого столбца.|
| [is_collapsed](/cells/python-net/ru/aspose.cells/column/is_collapsed) | свернута ли колонка|


###  Методы
| Метод| Описание|
| :- | :- |
| [apply_style](/cells/python-net/ru/aspose.cells/column/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) |Применяет форматы для всего столбца.|
| [get_style](/cells/python-net/ru/aspose.cells/column/get_style/#) | Получает стиль этого столбца.|
| [set_style](/cells/python-net/ru/aspose.cells/column/set_style/#aspose.cells.Style) | Устанавливает стиль этого столбца.|



###  Пример

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first Column
column = worksheet.cells.columns[0]
# Apply Style to first Column
column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
