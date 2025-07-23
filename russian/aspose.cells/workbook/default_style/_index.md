---
title: default_style недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 580
url: /ru/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style недвижимость

Возвращает или задает объект [`Style`](/cells/python-net/ru/aspose.cells/style) по умолчанию для рабочей книги.

###  Примечания

Свойство DefaultStyle полезно для реализации стиля для всей книги.

###  Пример

Следующий код создает и создает новую рабочую книгу и устанавливает для нее значение по умолчанию [`Style`](/cells/python-net/ru/aspose.cells/style).

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
###  Определение:
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Style`](/cells/python-net/ru/aspose.cells/style)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
