---
title: SheetRender класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 120
url: /ru/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender класс
Представляет отрисовку рабочего листа, которая может отображать рабочий лист в различные изображения, например (BMP, PNG, JPEG, TIFF..).
Конструктор этого класса должен использоваться после изменения настроек страницы и стиля ячейки.



Тип SheetRender предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | конструкция SheetRender, в качестве параметров нужен рабочий лист и ImageOrPrintOptions|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [page_count](/cells/python-net/ru/aspose.cells.rendering/sheetrender/page_count) | Получает общее количество страниц текущего листа.|
| [page_scale](/cells/python-net/ru/aspose.cells.rendering/sheetrender/page_scale) | Получает расчетный масштаб страницы листа.<br/> Возвращает установленный масштаб, если установлен [`PageSetup.zoom`](/cells/python-net/ru/aspose.cells/pagesetup#zoom). В противном случае возвращается рассчитанный масштаб в соответствии с [`PageSetup.fit_to_pages_wide`](/cells/python-net/ru/aspose.cells/pagesetup#fit_to_pages_wide) и [`PageSetup.fit_to_pages_tall`](/cells/python-net/ru/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Методы
| Метод| Описание|
| :- | :- |
| [to_image](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_image/#int-str) |Преобразовать определенную страницу в файл.|
| [to_image](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Рендеринг определенной страницы в поток.|
| [to_tiff](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Отобразите весь рабочий лист как изображение Tiff для потоковой передачи.|
| [to_tiff](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_tiff/#str) | Отобразите весь лист как изображение Tiff в файл.|
| [to_printer](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#str) | Отобразить рабочий лист на принтере|
| [to_printer](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Отобразить рабочий лист на принтере|
| [to_printer](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Отобразить рабочий лист на принтере|
| [to_printer](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Отобразить рабочий лист на принтере|
| [to_printer](/cells/python-net/ru/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Отобразить рабочий лист на принтере|
| [get_page_size_inch](/cells/python-net/ru/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Получите размер страницы выходного изображения в дюймах.|
| [custom_print](/cells/python-net/ru/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | С помощью этой функции клиент может управлять настройками страницы принтера при печати каждой страницы.|
| [dispose](/cells/python-net/ru/aspose.cells.rendering/sheetrender/dispose/#) | Освобождает ресурсы, созданные и используемые для рендеринга.|



###  Смотрите также
* модуль [`aspose.cells.rendering`](..)
