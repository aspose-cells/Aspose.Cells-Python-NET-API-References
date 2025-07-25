---
title: LoadFilter класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 940
url: /ru/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter класс
Представляет фильтр, который предоставляет параметры загрузки данных при загрузке рабочей книги из шаблона.



Тип LoadFilter предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/loadfilter/__init__/#) | Создает один LoadFilter с параметрами фильтра по умолчанию LoadDataFilterOptions.All.|
| [`__init__(self, opts)`](/cells/python-net/ru/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) | Создает один LoadFilter с заданными параметрами фильтра.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_data_filter_options](/cells/python-net/ru/aspose.cells/loadfilter/load_data_filter_options) |Параметры фильтра, указывающие, какие данные следует загрузить.|
| [sheets_in_loading_order](/cells/python-net/ru/aspose.cells/loadfilter/sheets_in_loading_order) | Указывает листы (индексы) и порядок загрузки.<br/>Значение по умолчанию — null, что означает загрузку всех листов в порядке по умолчанию в файле шаблона.<br/> Если значение не равно null и индекс какого-либо листа отсутствует в возвращаемом массиве, то лист не будет загружен.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/ru/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) | Подготавливает параметры фильтра перед загрузкой указанного рабочего листа.<br/>Пользовательская реализация LoadFilter может изменить LoadDataFilterOptions здесь.<br/> для обозначения способа загрузки данных для этого рабочего листа.|



###  Примечания

Пользователь может указать параметры фильтра или реализовать свои собственные LoadFilter, чтобы указать способ загрузки данных.

###  Смотрите также
* модуль [`aspose.cells`](..)
