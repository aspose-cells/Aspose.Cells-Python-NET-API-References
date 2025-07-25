---
title: CopyOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 340
url: /ru/aspose.cells/copyoptions/
is_root: false
---
##  CopyOptions класс
Представляет варианты копирования.



Тип CopyOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/copyoptions/__init__/#) | Конструктор CopyOptions.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [keep_macros](/cells/python-net/ru/aspose.cells/copyoptions/keep_macros) |Указывает, следует ли сохранять макросы;|
| [extend_to_adjacent_range](/cells/python-net/ru/aspose.cells/copyoptions/extend_to_adjacent_range) | Указывает, следует ли расширять диапазоны при копировании диапазона в соседний диапазон.|
| [copy_names](/cells/python-net/ru/aspose.cells/copyoptions/copy_names) | Указывает, копируются ли имена.|
| [copy_invalid_formulas_as_values](/cells/python-net/ru/aspose.cells/copyoptions/copy_invalid_formulas_as_values) | Если формула недействительна для указанного назначения, копируйте только значения.|
| [column_character_width](/cells/python-net/ru/aspose.cells/copyoptions/column_character_width) | Указывает, копируется ли ширина столбца в символах.|
| [refer_to_sheet_with_same_name](/cells/python-net/ru/aspose.cells/copyoptions/refer_to_sheet_with_same_name) | В MS Excel при копировании формул, которые ссылаются на другие листы, при копировании одного листа на другой,<br/>скопированные формулы должны ссылаться на исходную книгу.<br/>Однако в некоторых ситуациях пользователю может потребоваться, чтобы скопированные формулы ссылались на рабочие листы с тем же именем.<br/>в той же рабочей книге, например, когда эти рабочие листы были скопированы до этой операции копирования,<br/> то это свойство должно быть сохранено как истинное.|
| [refer_to_destination_sheet](/cells/python-net/ru/aspose.cells/copyoptions/refer_to_destination_sheet) | При копировании диапазона в тот же файл и при наличии ссылки на исходный лист в диаграмме,<br/>Значение False означает, что источник данных скопированной диаграммы не будет изменен.<br/> True означает, что источник данных скопированной диаграммы ссылается на целевой лист.|



###  Смотрите также
* модуль [`aspose.cells`](..)
