---
title: Row класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1340
url: /ru/aspose.cells/row/
is_root: false
---
##  Row класс
Представляет одну строку на листе.



Тип Row предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_blank](/cells/python-net/ru/aspose.cells/row/is_blank) | Указывает, содержит ли строка какие-либо данные|
| [is_collapsed](/cells/python-net/ru/aspose.cells/row/is_collapsed) | свернута ли строка|
| [height](/cells/python-net/ru/aspose.cells/row/height) | Получает и задает высоту строки в баллах.|
| [is_hidden](/cells/python-net/ru/aspose.cells/row/is_hidden) | Указывает, скрыта ли строка.|
| [index](/cells/python-net/ru/aspose.cells/row/index) | Получает индекс этой строки.|
| [group_level](/cells/python-net/ru/aspose.cells/row/group_level) | Получает уровень группы строки.|
| [is_height_matched](/cells/python-net/ru/aspose.cells/row/is_height_matched) | Указывает, соответствует ли высота строки текущей настройке шрифта по умолчанию в книге.<br/>Значение true для этого свойства также означает, что высота строки является «автоматической» без специального значения высоты, установленного пользователем.|
| [has_custom_style](/cells/python-net/ru/aspose.cells/row/has_custom_style) | Указывает, имеет ли эта строка пользовательские настройки стиля (отличные от стиля по умолчанию, унаследованного из книги).|
| [first_cell](/cells/python-net/ru/aspose.cells/row/first_cell) | Получает первый объект ячейки в строке.|
| [first_data_cell](/cells/python-net/ru/aspose.cells/row/first_data_cell) | Получает первую непустую ячейку в строке.|
| [last_cell](/cells/python-net/ru/aspose.cells/row/last_cell) | Получает последний объект ячейки в строке.|
| [last_data_cell](/cells/python-net/ru/aspose.cells/row/last_data_cell) | Получает последнюю непустую ячейку в строке.|



Получает ячейку.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] | Индекс столбца|


###  Методы
| Метод| Описание|
| :- | :- |
| [get_cell_by_index](/cells/python-net/ru/aspose.cells/row/get_cell_by_index/#int) | Получите ячейку по определенному индексу в коллекции ячеек этой строки.|
| [get_enumerator](/cells/python-net/ru/aspose.cells/row/get_enumerator/#bool-bool) | Получает перечислитель, который перебирает ячейки в этой строке.|
| [get_cell_or_null](/cells/python-net/ru/aspose.cells/row/get_cell_or_null/#int) | Получает ячейку или значение NULL в определенном индексе.|
| [get_style](/cells/python-net/ru/aspose.cells/row/get_style/#) | Получает стиль этой строки.|
| [set_style](/cells/python-net/ru/aspose.cells/row/set_style/#aspose.cells.Style) | Устанавливает стиль этой строки.|
| [copy_settings](/cells/python-net/ru/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | Скопируйте настройки строки, такие как стиль, высота, видимость и т. д.|
| [apply_style](/cells/python-net/ru/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Применяет форматы для всей строки.|
| [equals](/cells/python-net/ru/aspose.cells/row/equals/#aspose.cells.Row) | Проверяет, ссылается ли этот объект на одну и ту же строку с другим объектом строки.|



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
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
