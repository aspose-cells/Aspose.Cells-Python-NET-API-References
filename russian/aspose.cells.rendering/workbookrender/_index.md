---
title: WorkbookRender класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender класс
 Представляет собой визуализацию рабочей книги.
Конструктор этого класса должен использоваться после изменения настроек страницы и стиля ячейки.



Тип WorkbookRender предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | Конструкция WorkbookRender|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [page_count](/cells/python-net/ru/aspose.cells.rendering/workbookrender/page_count) | Получает общее количество страниц в рабочей книге.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Отобразить всю книгу как изображение Tiff для потоковой передачи.|
| [`to_image(self, filename)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#str) | Сохраните всю рабочую книгу в виде изображения Tiff в файле.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#int-str) | Сохранение определенной страницы в файл.|
| [`to_image(self, page_index, stream)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Отобразить определенную страницу в потоке.|
| [`to_printer(self, printer_name)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#str) | Распечатать книгу на принтере|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Распечатать книгу на принтере|
| [`to_printer(self, printer_settings)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Распечатать книгу на принтере|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Распечатать книгу на принтере|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Распечатать книгу на принтере|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Получить размер страницы выходного изображения в дюймах.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | С помощью этой функции клиент может управлять настройками страницы принтера при печати каждой страницы.|
| [`dispose(self)`](/cells/python-net/ru/aspose.cells.rendering/workbookrender/dispose/#) | Освобождает ресурсы, созданные и используемые для рендеринга.|



###  Примечания



###  Смотрите также
* модуль [`aspose.cells.rendering`](..)
