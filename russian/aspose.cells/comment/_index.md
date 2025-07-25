---
title: Comment класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 260
url: /ru/aspose.cells/comment/
is_root: false
---
##  Comment класс
Инкапсулирует объект, представляющий комментарий к ячейке.



Тип Comment предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [author](/cells/python-net/ru/aspose.cells/comment/author) | Получает и задает имя автора исходного комментария|
| [comment_shape](/cells/python-net/ru/aspose.cells/comment/comment_shape) | Получить объект Shape, представляющий форму, прикрепленную к указанному комментарию.|
| [row](/cells/python-net/ru/aspose.cells/comment/row) | Получает индекс строки комментария.|
| [column](/cells/python-net/ru/aspose.cells/comment/column) | Получает индекс столбца комментария.|
| [is_threaded_comment](/cells/python-net/ru/aspose.cells/comment/is_threaded_comment) | Указывает, является ли этот комментарий древовидным.|
| [threaded_comments](/cells/python-net/ru/aspose.cells/comment/threaded_comments) | Получает список связанных комментариев;|
| [note](/cells/python-net/ru/aspose.cells/comment/note) | Представляет содержание комментария.|
| [html_note](/cells/python-net/ru/aspose.cells/comment/html_note) | Получает и задает HTML-строку, содержащую данные и некоторые форматы в этом комментарии.|
| [font](/cells/python-net/ru/aspose.cells/comment/font) | Получает шрифт комментария.|
| [is_visible](/cells/python-net/ru/aspose.cells/comment/is_visible) | Показывает, виден ли комментарий или нет.|
| [text_orientation_type](/cells/python-net/ru/aspose.cells/comment/text_orientation_type) | Получает и задает тип ориентации текста комментария.|
| [text_horizontal_alignment](/cells/python-net/ru/aspose.cells/comment/text_horizontal_alignment) | Получает и задает тип горизонтального выравнивания текста комментария.|
| [text_vertical_alignment](/cells/python-net/ru/aspose.cells/comment/text_vertical_alignment) | Получает и задает тип вертикального выравнивания текста комментария.|
| [auto_size](/cells/python-net/ru/aspose.cells/comment/auto_size) | Указывает, регулируется ли размер комментария автоматически в соответствии с его содержанием.<br/>Примечание: В некоторых особых случаях (например, в среде Mac) этот параметр может не действовать. Если этот параметр не действует, замените его на FitToTextSize().|
| [height_cm](/cells/python-net/ru/aspose.cells/comment/height_cm) | Представляет высоту комментария в сантиметрах.|
| [width_cm](/cells/python-net/ru/aspose.cells/comment/width_cm) | Представляет ширину комментария в сантиметрах.|
| [width](/cells/python-net/ru/aspose.cells/comment/width) | Представляет ширину комментария в пикселях.|
| [height](/cells/python-net/ru/aspose.cells/comment/height) | Представляет высоту комментария в пикселях.|
| [width_inch](/cells/python-net/ru/aspose.cells/comment/width_inch) | Представляет ширину комментария в дюймах.|
| [height_inch](/cells/python-net/ru/aspose.cells/comment/height_inch) | Представляет высоту комментария в дюймах.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/ru/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Отформатируйте некоторые символы с помощью настроек шрифта.|
| [`characters(self, start_index, length)`](/cells/python-net/ru/aspose.cells/comment/characters/#int-int) | Возвращает объект Characters, представляющий диапазон символов в тексте комментария.|
| [`get_characters(self)`](/cells/python-net/ru/aspose.cells/comment/get_characters/#) | Возвращает все объекты Characters<br/> который представляет собой диапазон символов в тексте комментария.|
| [`get_rich_formattings(self)`](/cells/python-net/ru/aspose.cells/comment/get_rich_formattings/#) | Возвращает все объекты Characters<br/> который представляет собой диапазон символов в тексте комментария.|



###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
