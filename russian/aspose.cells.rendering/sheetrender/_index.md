---
title: SheetRender класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender класс
Представляет собой рендеринг рабочего листа, который может преобразовать рабочий лист в различные изображения, такие как (BMP, PNG, JPEG, TIFF..)
Конструктор этого класса должен использоваться после изменения настроек страницы и стиля ячейки.



Тип SheetRender предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | конструкция SheetRender, требует worksheet и ImageOrPrintOptions в качестве параметров|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [page_count](/cells/python-net/ru/aspose.cells.rendering/sheetrender/page_count) | Возвращает общее количество страниц текущего рабочего листа.|
| [page_scale](/cells/python-net/ru/aspose.cells.rendering/sheetrender/page_scale) | Получает рассчитанный масштаб страницы листа.<br/> Возвращает заданный масштаб, если задано значение [`PageSetup.zoom`](/cells/python-net/ru/aspose.cells/pagesetup#zoom). В противном случае возвращает рассчитанный масштаб в соответствии с [`PageSetup.fit_to_pages_wide`](/cells/python-net/ru/aspose.cells/pagesetup#fit_to_pages_wide) и [`PageSetup.fit_to_pages_tall`](/cells/python-net/ru/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Методы
| Метод| Описание|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_image/#int-str) | Сохранение определенной страницы в файл.|
| [`to_image(self, page_index, stream)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Отобразить определенную страницу в потоке.|
| [`to_tiff(self, stream)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Отобразить весь рабочий лист как изображение Tiff для потоковой передачи.|
| [`to_tiff(self, filename)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_tiff/#str) | Сохраните весь рабочий лист в виде изображения Tiff в файле.|
| [`to_printer(self, printer_name)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#str) | Распечатать рабочий лист на принтере|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Распечатать рабочий лист на принтере|
| [`to_printer(self, printer_settings)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Распечатать рабочий лист на принтере|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Распечатать рабочий лист на принтере|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Распечатать рабочий лист на принтере|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Получить размер страницы выходного изображения в дюймах.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | С помощью этой функции клиент может управлять настройками страницы принтера при печати каждой страницы.|
| [`dispose(self)`](/cells/python-net/ru/aspose.cells.rendering/sheetrender/dispose/#) | Освобождает ресурсы, созданные и используемые для рендеринга.|



###  Смотрите также
* модуль [`aspose.cells.rendering`](..)
