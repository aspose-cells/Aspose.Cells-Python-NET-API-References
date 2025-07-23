---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/hyperlinkcollection/add/
is_root: false
---
##  add(self, cell_name, total_rows, total_columns, address) {#str-int-int-str}
Добавляет гиперссылку к указанной ячейке или диапазону ячеек.


###  Возврат

Индекс объекта [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink).


```python

def add(self, cell_name, total_rows, total_columns, address):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_name | str | Cell имя.|
| total_rows | int | Количество строк в этом диапазоне гиперссылки.|
| total_columns | int |Количество столбцов этого диапазона гиперссылки.|
| address | str | Адрес гиперссылки.|


##  add(self, first_row, first_column, total_rows, total_columns, address) {#int-int-int-int-str}
Добавляет гиперссылку к указанной ячейке или диапазону ячеек.


###  Возврат

Индекс объекта [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink).


```python

def add(self, first_row, first_column, total_rows, total_columns, address):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| first_row | int | Первая строка диапазона гиперссылки.|
| first_column | int | Первый столбец диапазона гиперссылки.|
| total_rows | int | Количество строк в этом диапазоне гиперссылки.|
| total_columns | int |Количество столбцов этого диапазона гиперссылки.|
| address | str | Адрес гиперссылки.|

###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
excel = Workbook()
worksheet = excel.worksheets[0]
worksheet.hyperlinks.add("A4", 1, 1, "http://www.aspose.com")
worksheet.hyperlinks.add("A5", 1, 1, "c:\\book1.xls")

```


##  add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip) {#str-str-str-str-str}
Добавляет гиперссылку к указанной ячейке или диапазону ячеек.


###  Возврат

Индекс объекта [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink).


```python

def add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start_cell_name | str |Верхняя левая ячейка диапазона.|
| end_cell_name | str | Нижняя правая ячейка диапазона.|
| address | str | Адрес гиперссылки.|
| text_to_display | str | Текст, который будет отображаться для указанной гиперссылки.|
| screen_tip | str | Текст всплывающей подсказки для указанной гиперссылки.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink)
* класс [`HyperlinkCollection`](/cells/python-net/ru/aspose.cells/hyperlinkcollection)
