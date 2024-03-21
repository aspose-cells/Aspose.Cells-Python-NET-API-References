---
title: Hyperlink класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 840
url: /ru/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink класс
Инкапсулирует объект, представляющий гиперссылку.



Тип Hyperlink предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [address](/cells/python-net/ru/aspose.cells/hyperlink/address) | Представляет адрес гиперссылки.|
| [text_to_display](/cells/python-net/ru/aspose.cells/hyperlink/text_to_display) | Представляет текст, отображаемый для указанной гиперссылки. Значением по умолчанию является адрес гиперссылки.|
| [area](/cells/python-net/ru/aspose.cells/hyperlink/area) | Получает диапазон гиперссылки.|
| [screen_tip](/cells/python-net/ru/aspose.cells/hyperlink/screen_tip) | Возвращает или задает текст всплывающей подсказки для указанной гиперссылки.|
| [link_type](/cells/python-net/ru/aspose.cells/hyperlink/link_type) | Получает тип ссылки.|


###  Методы
| Метод| Описание|
| :- | :- |
| [delete](/cells/python-net/ru/aspose.cells/hyperlink/delete/#) |Удаляет эту гиперссылку|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Adding a hyperlink to a URL at "A1" cell
index = worksheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Getting a Hyperlink by index.
hyperlink = worksheet.hyperlinks[index]
# Setting display text of this hyperlink.
hyperlink.text_to_display = "Aspose"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
