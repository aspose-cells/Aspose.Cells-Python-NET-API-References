---
title: DeleteBlankOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 460
url: /ru/aspose.cells/deleteblankoptions/
is_root: false
---
##  DeleteBlankOptions класс
Представляет настройку удаления пустых ячеек/строк/столбцов.



**Наследование:** [`DeleteBlankOptions`](/cells/python-net/aspose.cells/deleteblankoptions) → 
[`DeleteOptions`](/cells/python-net/ru/aspose.cells/deleteoptions)



Тип DeleteBlankOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/deleteblankoptions/__init__/#) | Создает новый экземпляр DeleteBlankOptions|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [update_reference](/cells/python-net/ru/aspose.cells/deleteblankoptions/update_reference) | Указывает, следует ли обновлять ссылки на других листах.|
| [empty_string_as_blank](/cells/python-net/ru/aspose.cells/deleteblankoptions/empty_string_as_blank) | Будет ли одна ячейка считаться пустой, если ее значение представляет собой пустую строку.<br/> Значение по умолчанию — true.|
| [empty_formula_value_as_blank](/cells/python-net/ru/aspose.cells/deleteblankoptions/empty_formula_value_as_blank) | Будет ли одна ячейка считаться пустой, если она является формулой, а вычисленный результат — нуль или пустая строка.<br/> Значение по умолчанию — false.|
| [drawings_as_blank](/cells/python-net/ru/aspose.cells/deleteblankoptions/drawings_as_blank) | Будут ли объекты, связанные с чертежом, такие как изображение, фигура, диаграмма..., восприниматься как пустые.<br/> Значение по умолчанию — true.|
| [merged_cells_shrink_type](/cells/python-net/ru/aspose.cells/deleteblankoptions/merged_cells_shrink_type) | Указывает, как обрабатывать объединенные ячейки при удалении пустых строк/столбцов.|
| [start_index](/cells/python-net/ru/aspose.cells/deleteblankoptions/start_index) | Указывает начальный индекс строки/столбца диапазона для проверки и удаления пустых строк/столбцов.|
| [end_index](/cells/python-net/ru/aspose.cells/deleteblankoptions/end_index) | Указывает конечный индекс строки/столбца (включительно) диапазона для проверки и удаления пустых строк/столбцов.<br/>Значение по умолчанию -1, причем -1 означает максимальный диапазон всех объектов (ячеек, рисунков и т. д.), которые необходимо проверить.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`DeleteBlankOptions`](/cells/python-net/ru/aspose.cells/deleteblankoptions)
* класс [`DeleteOptions`](/cells/python-net/ru/aspose.cells/deleteoptions)
