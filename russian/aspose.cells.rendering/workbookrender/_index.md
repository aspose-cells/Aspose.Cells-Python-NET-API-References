---
title: WorkbookRender класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 130
url: /ru/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender класс
 Представляет визуализацию рабочей книги.
Конструктор этого класса должен использоваться после модификации pagesetup, стиля ячейки.



Тип WorkbookRender предоставляет следующие члены:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [WorkbookRender(workbook, options)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/__init__/#Workbook-ImageOrPrintOptions) | Конструкция WorkbookRender|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [page_count](/cells/python-net/ru/aspose.cells.rendering/workbookrender/page_count) | Получает общее количество страниц книги.|


###  Методы
| Метод| Описание|
| :- | :- |
| [to_image(stream)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#io.RawIOBase) | Рендеринг всей книги в виде изображения Tiff для потоковой передачи.|
| [to_image(filename)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#str) | Визуализация всей книги в виде изображения Tiff в файл.|
| [to_image(page_index, file_name)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#int-str) | Рендерить определенную страницу в файл.|
| [to_image(page_index, stream)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_image/#int-io.RawIOBase) | Рендерить определенную страницу в поток.|
| [to_printer(printer_name)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#str) | Рендеринг книги на принтер|
| [to_printer(printer_name, job_name)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Рендеринг книги на принтер|
| [to_printer(printer_settings)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Рендеринг книги на принтер|
| [to_printer(printer_settings, job_name)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Рендеринг книги на принтер|
| [to_printer(printer_name, print_page_index, print_page_count)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Рендеринг книги на принтер|
| [get_page_size_inch(page_index)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) |Получить размер страницы в дюймах выходного изображения.|
| [custom_print(next_page_after_print, print_page_event_args)](/cells/python-net/ru/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Клиент может управлять настройками страницы принтера при печати каждой страницы с помощью этой функции.|



###  Примечания



###  Смотрите также
* модуль [aspose.cells.rendering](..)
