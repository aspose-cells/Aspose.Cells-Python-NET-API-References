---
title: Row класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1230
url: /ru/aspose.cells/row/
is_root: false
---
##  Row класс
Представляет одну строку на рабочем листе.



Тип Row предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_blank](/cells/python-net/ru/aspose.cells/row/is_blank) | Указывает, содержит ли строка какие-либо данные|
| [is_collapsed](/cells/python-net/ru/aspose.cells/row/is_collapsed) | свернут ли ряд|
| [height](/cells/python-net/ru/aspose.cells/row/height) | Получает и задает высоту строки в точках.|
| [is_hidden](/cells/python-net/ru/aspose.cells/row/is_hidden) | Указывает, скрыта ли строка.|
| [index](/cells/python-net/ru/aspose.cells/row/index) | Получает индекс этой строки.|
| [group_level](/cells/python-net/ru/aspose.cells/row/group_level) | Получает уровень группы строки.|
| [is_height_matched](/cells/python-net/ru/aspose.cells/row/is_height_matched) | Указывает, соответствует ли высота строки текущей настройке шрифта по умолчанию для рабочей книги.<br/> Значение True этого свойства также означает, что высота строки является «автоматической» и не требует установки пользователем специального значения высоты.|
| [has_custom_style](/cells/python-net/ru/aspose.cells/row/has_custom_style) | Указывает, имеет ли эта строка пользовательские настройки стиля (отличные от настроек по умолчанию, унаследованных из рабочей книги).|
| [first_cell](/cells/python-net/ru/aspose.cells/row/first_cell) | Получает первый объект ячейки в строке.|
| [first_data_cell](/cells/python-net/ru/aspose.cells/row/first_data_cell) |Получает первую непустую ячейку в строке.|
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
| [`get_cell_by_index(self, index)`](/cells/python-net/ru/aspose.cells/row/get_cell_by_index/#int) | Получить ячейку по определенному индексу в коллекции ячеек этой строки.|
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/ru/aspose.cells/row/get_enumerator/#bool-bool) | Получает перечислитель, который перебирает ячейки в этой строке.|
| [`get_cell_or_null(self, column)`](/cells/python-net/ru/aspose.cells/row/get_cell_or_null/#int) | Возвращает ячейку или значение NULL в указанном индексе.|
| [`get_style(self)`](/cells/python-net/ru/aspose.cells/row/get_style/#) | Получает стиль этой строки.|
| [`set_style(self, style)`](/cells/python-net/ru/aspose.cells/row/set_style/#aspose.cells.style) | Задает стиль этой строки.|
| [`copy_settings(self, source, check_style)`](/cells/python-net/ru/aspose.cells/row/copy_settings/#aspose.cells.row-bool) | Копировать настройки строки, такие как стиль, высота, видимость и т. д.|
| [`apply_style(self, style, flag)`](/cells/python-net/ru/aspose.cells/row/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Применяет форматирование ко всей строке.|
| [`equals(self, row)`](/cells/python-net/ru/aspose.cells/row/equals/#aspose.cells.row) | Проверяет, ссылается ли данный объект на ту же строку, что и другой объект строки.|



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
