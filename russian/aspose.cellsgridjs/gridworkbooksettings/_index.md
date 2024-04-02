---
title: GridWorkbookSettings класс
second_title: Aspose.Cells.GridJs for Python via .NET API
description:
type: docs
weight: 80
url: /ru/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings класс

Представляет параметры книги.



Тип GridWorkbookSettings предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | Создает новый экземпляр GridWorkbookSettings.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [max_iteration](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Возвращает или задает максимальное количество итераций для разрешения циклической ссылки. Значение по умолчанию — 100.|
| [iteration](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/iteration) | Указывает, использовать ли итерацию для разрешения циклических ссылок.|
| [force_full_calculate](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Указывает, выполняется ли полный расчет каждый раз, когда расчет запускается.|
| [create_calc_chain](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) |Указывает, создавать ли цепочку вычисляемых формул. По умолчанию — ложь.|
| [re_calculate_on_open](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Указывает, нужно ли пересчитывать все формулы при открытии файла.|
| [precision_as_displayed](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | True, если вычисления в этой книге будут выполняться только с точностью отображаемых чисел.|
| [date1904](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/date1904) | Получает или задает значение, указывающее, использует ли книга систему дат 1904.|
| [enable_macros](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Включить макросы; Теперь это работает только при копировании листа на другой лист в книге.|
| [check_custom_number_format](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Указывает, проверяется ли пользовательский формат чисел при настройке Style.Custom.|
| [author](/cells/python-net/ru/aspose.cellsgridjs/gridworkbooksettings/author) | Получает/устанавливает автора файла.|



###  Пример


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Смотрите также
* модуль [`aspose.cellsgridjs`](..)
