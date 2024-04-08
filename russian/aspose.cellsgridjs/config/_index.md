---
title: Config класс
second_title: Aspose.Cells.GridJs for Python via .NET API
description:
type: docs
weight: 10
url: /ru/aspose.cellsgridjs/config/
is_root: false
---
##  Config класс

Представляет все настройки GridJs.



Тип Config предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cellsgridjs/config/__init__/#) | Создает новый экземпляр Config|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_html_as_zip](/cells/python-net/ru/aspose.cellsgridjs/config/save_html_as_zip) | Устанавливает/получает, сохранять ли html-файл в виде zip-архива, значение по умолчанию — false.|
| [same_image_detecting](/cells/python-net/ru/aspose.cellsgridjs/config/same_image_detecting) | Устанавливает/получает, следует ли проверять, имеет ли изображение тот же источник, значение по умолчанию — true<br/> Значение по умолчанию верно.|
| [auto_optimize_for_large_cells](/cells/python-net/ru/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Устанавливает/получает, следует ли автоматически оптимизировать производительность загрузки для листа с большими ячейками.<br/> игнорировать некоторые стили/границы, чтобы сократить время загрузки<br/> Значение по умолчанию верно.|
| [islimit_shape_or_image](/cells/python-net/ru/aspose.cellsgridjs/config/islimit_shape_or_image) |Устанавливает/получает, следует ли ограничивать общее количество форм отображения/изображений внутри одного листа, если установлено значение true,<br/> GridJs ограничит общий размер формы/изображения дисплея внутри одного листа до MaxShapeOrImageCount.<br/> Значение по умолчанию верно.|
| [max_shape_or_image_count](/cells/python-net/ru/aspose.cellsgridjs/config/max_shape_or_image_count) | Устанавливает/получает общее количество форм отображения/изображений внутри активного листа. Это вступит в силу, если IslimitShapes=true.<br/> значение по умолчанию — 100.|
| [max_total_shape_or_image_count](/cells/python-net/ru/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Устанавливает/получает общее количество форм отображения/изображений во всей книге. Это вступит в силу, если IslimitShapes=true.<br/> значение по умолчанию — 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/ru/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Устанавливает/получает максимальную ширину или высоту для фигуры/изображения. GridJs будет игнорировать фигуру/изображение с шириной или высотой, превышающей эту, это будет действовать, когда IslimitShapes=true.<br/> значение по умолчанию — 10000.|
| [max_pdf_save_seconds](/cells/python-net/ru/aspose.cellsgridjs/config/max_pdf_save_seconds) | Устанавливает/получает максимальное время ожидания в секундах при сохранении в PDF.<br/> значение по умолчанию — 10.|
| [ignore_empty_content](/cells/python-net/ru/aspose.cellsgridjs/config/ignore_empty_content) | Устанавливает/получает, отображать ли максимальный диапазон, включающий данные, стиль, объединенные ячейки и фигуры.<br/> если последняя строка или столбец содержит ячейки без значения и формулы, но имеет собственный стиль<br/>тогда мы не будем показывать эту строку/столбец, если это значение истинно.。<br/> Значение по умолчанию верно .|
| [use_print_area](/cells/python-net/ru/aspose.cellsgridjs/config/use_print_area) |Устанавливает/получает, следует ли использовать PageSetup.PrintArea для диапазона отображения пользовательского интерфейса, если на листе имеется параметр PageSetup для PrintArea.<br/> Значение по умолчанию неверно .|
| [load_time_out](/cells/python-net/ru/aspose.cellsgridjs/config/load_time_out) | Устанавливает/получает прерывание по тайм-ауту в миллисекундах при загрузке файла, когда период стоимости загрузки файла превышает ожидаемый, это вызывает исключение.<br/> значение по умолчанию — -1, что означает, что прерывание по тайм-ауту не установлено.|
| [show_chart_sheet](/cells/python-net/ru/aspose.cellsgridjs/config/show_chart_sheet) | Устанавливает/получает, отображать ли лист диаграммы.<br/> Значение по умолчанию неверно .|
| [page_size](/cells/python-net/ru/aspose.cellsgridjs/config/page_size) | Устанавливает/получает, следует ли выполнять нумерацию страниц<br/> GridJs будет ограничивать размер строки на основе PageSize. Если PageSize равен -1, разбиение на страницы не будет выполняться.<br/> значение по умолчанию - -1|
| [empty_sheet_max_row](/cells/python-net/ru/aspose.cellsgridjs/config/empty_sheet_max_row) | Устанавливает/получает максимальную строку по умолчанию для пустого листа.<br/> значение по умолчанию — 12.|
| [empty_sheet_max_col](/cells/python-net/ru/aspose.cellsgridjs/config/empty_sheet_max_col) | Устанавливает/получает максимальный столбец по умолчанию для пустого листа.<br/> значение по умолчанию — 15.|
| [picture_cache_directory](/cells/python-net/ru/aspose.cellsgridjs/config/picture_cache_directory) | Устанавливает/получает каталог кеша для изображений (это вступит в силу, если GridJsWorkbook.CacheImp имеет значение null)<br/> путь по умолчанию будет «_piccache» внутри FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/ru/aspose.cellsgridjs/config/file_cache_directory) |Устанавливает/получает каталог кэша для файла электронной таблицы.<br/> Нам нужно установить для него определенный путь, прежде чем мы будем использовать GridJs.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_license](/cells/python-net/ru/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/ru/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Лицензирует компонент.|
| [set_font_folder](/cells/python-net/ru/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Устанавливает папку шрифтов|
| [set_font_folders](/cells/python-net/ru/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Устанавливает папки шрифтов|



###  Смотрите также
* модуль [`aspose.cellsgridjs`](..)
