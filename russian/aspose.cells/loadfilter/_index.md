---
title: LoadFilter класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1050
url: /ru/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter класс
Представляет фильтр, предоставляющий параметры загрузки данных при загрузке книги из шаблона.



Тип LoadFilter предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/loadfilter/__init__/#) | Создает один LoadFilter с параметрами фильтра по умолчанию LoadDataFilterOptions.All.|
| [__init__](/cells/python-net/ru/aspose.cells/loadfilter/__init__/#aspose.cells.LoadDataFilterOptions) | Создает один LoadFilter с заданными параметрами фильтра.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [load_data_filter_options](/cells/python-net/ru/aspose.cells/loadfilter/load_data_filter_options) | Параметры фильтра, указывающие, какие данные следует загрузить.|
| [sheets_in_loading_order](/cells/python-net/ru/aspose.cells/loadfilter/sheets_in_loading_order) | Указывает листы (индексы) и порядок загрузки.<br/>По умолчанию установлено значение null, что означает загрузку всех листов в порядке по умолчанию в файле шаблона.<br/> Если значение не равно нулю и индекс какого-либо листа отсутствует в возвращаемом массиве, лист не будет загружен.|


###  Методы
| Метод| Описание|
| :- | :- |
| [start_sheet](/cells/python-net/ru/aspose.cells/loadfilter/start_sheet/#aspose.cells.Worksheet) | Подготавливает параметры фильтра перед загрузкой данного листа.<br/>Пользовательская реализация LoadFilter может изменить LoadDataFilterOptions здесь.<br/> чтобы указать, как загрузить данные для этого листа.|



###  Примечания

Пользователь может указать параметры фильтра или реализовать свой собственный LoadFilter, чтобы указать, как загружать данные.

###  Смотрите также
* модуль [`aspose.cells`](..)
