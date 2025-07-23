---
title: Font класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 660
url: /ru/aspose.cells/font/
is_root: false
---
##  Font класс
Инкапсулирует объект шрифта, используемый в электронной таблице.



Тип Font предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [charset](/cells/python-net/ru/aspose.cells/font/charset) | Представляет набор символов.|
| [is_italic](/cells/python-net/ru/aspose.cells/font/is_italic) | Возвращает или задает значение, указывающее, является ли шрифт курсивом.|
| [is_bold](/cells/python-net/ru/aspose.cells/font/is_bold) | Возвращает или задает значение, указывающее, является ли шрифт полужирным.|
| [caps_type](/cells/python-net/ru/aspose.cells/font/caps_type) | Получает и задает тип заглавных букв текста.|
| [strike_type](/cells/python-net/ru/aspose.cells/font/strike_type) | Получает тип забастовки текста.|
| [is_strikeout](/cells/python-net/ru/aspose.cells/font/is_strikeout) | Возвращает или задает значение, указывающее, является ли шрифт одинарным зачеркиванием.|
| [script_offset](/cells/python-net/ru/aspose.cells/font/script_offset) | Получает и задает смещение скрипта в процентах.|
| [is_superscript](/cells/python-net/ru/aspose.cells/font/is_superscript) | Возвращает или задает значение, указывающее, является ли шрифт суперскриптом.|
| [is_subscript](/cells/python-net/ru/aspose.cells/font/is_subscript) | Возвращает или задает значение, указывающее, является ли шрифт подстрочным.|
| [underline](/cells/python-net/ru/aspose.cells/font/underline) | Получает или задает тип подчеркивания шрифта.|
| [name](/cells/python-net/ru/aspose.cells/font/name) | Получает или задает имя [`Font`](/cells/python-net/ru/aspose.cells/font).|
| [double_size](/cells/python-net/ru/aspose.cells/font/double_size) | Получает и задает двойной размер шрифта.|
| [size](/cells/python-net/ru/aspose.cells/font/size) | Получает или задает размер шрифта.|
| [theme_color](/cells/python-net/ru/aspose.cells/font/theme_color) | Получает и задает цвет темы.|
| [color](/cells/python-net/ru/aspose.cells/font/color) | Получает или задает цвет шрифта.|
| [argb_color](/cells/python-net/ru/aspose.cells/font/argb_color) | Получает и задает цвет с помощью 32-битного значения ARGB.|
| [is_normalize_heights](/cells/python-net/ru/aspose.cells/font/is_normalize_heights) | Указывает, выполняется ли нормализация высоты, которая должна применяться к текстовому потоку.|
| [scheme_type](/cells/python-net/ru/aspose.cells/font/scheme_type) |Получает и задает тип схемы шрифта.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`equals(self, font)`](/cells/python-net/ru/aspose.cells/font/equals/#aspose.cells.font) | Проверяет, равны ли два шрифта.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Hello Aspose!")
font = cell.get_style().font
# Setting the font name to "Times New Roman"
font.name = "Times New Roman"
# Setting font size to 14
font.size = 14
# setting font color as Red
font.color = Color.red
# Saving the Excel file
workbook.save(r"dest.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Font`](/cells/python-net/ru/aspose.cells/font)
