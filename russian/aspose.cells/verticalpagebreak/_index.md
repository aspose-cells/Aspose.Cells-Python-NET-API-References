---
title: VerticalPageBreak класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1540
url: /ru/aspose.cells/verticalpagebreak/
is_root: false
---
##  VerticalPageBreak класс
Инкапсулирует объект, представляющий вертикальный разрыв страницы.



Тип VerticalPageBreak предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [start_row](/cells/python-net/ru/aspose.cells/verticalpagebreak/start_row) | Получает индекс начальной строки вертикального разрыва страницы.|
| [end_row](/cells/python-net/ru/aspose.cells/verticalpagebreak/end_row) | Получает индекс конечной строки вертикального разрыва страницы.|
| [column](/cells/python-net/ru/aspose.cells/verticalpagebreak/column) | Получает индекс столбца вертикального разрыва страницы.|



###  Пример

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
