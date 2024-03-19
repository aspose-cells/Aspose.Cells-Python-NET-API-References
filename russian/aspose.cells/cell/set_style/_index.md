---
title: set_style метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 360
url: /ru/aspose.cells/cell/set_style/
is_root: false
---
##  set_style {#aspose.cells.Style}
Устанавливает стиль ячейки.



```python
def set_style(self, style):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| style | [`Style`](/cells/python-net/ru/aspose.cells/style) | Стиль ячейки.|
###  Примечания

Если настройки границы изменены, граница корректирующих ячеек также будет обновлена.

##  set_style {#aspose.cells.Style-bool}

Примените измененное свойство стиля к ячейке.



```python
def set_style(self, style, explicit_flag):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| style | [`Style`](/cells/python-net/ru/aspose.cells/style) | Стиль ячейки.|
| explicit_flag | bool | Правда, перезаписывает только явно заданное форматирование.|


##  set_style {#aspose.cells.Style-aspose.cells.StyleFlag}
Примените стиль ячейки на основе флагов.



```python
def set_style(self, style, flag):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| style | [`Style`](/cells/python-net/ru/aspose.cells/style) | Стиль ячейки.|
| flag | [`StyleFlag`](/cells/python-net/ru/aspose.cells/styleflag) | Флаг стиля.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
