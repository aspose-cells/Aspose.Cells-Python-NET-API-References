---
title: ImageOrPrintOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 40
url: /ru/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions класс
Позволяет указать параметры при рендеринге листа в изображения, печати листа или рендеринге диаграммы в изображение.



Тип ImageOrPrintOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/__init__/#) | Создает новый экземпляр ImageOrPrintOptions.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/save_format) | Получает или задает тип формата выходного файла.<br/> Поддержка Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | Если PrintWithStatusDialog = true, появится диалоговое окно, показывающее текущий статус печати.<br/>в противном случае такой диалог не появится.|
| [horizontal_resolution](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Получает или задает горизонтальное разрешение созданных изображений (в точках на дюйм).<br/> Применяет метод создания изображений, за исключением изображений в формате Emf.|
| [vertical_resolution](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Получает или задает вертикальное разрешение созданных изображений (в точках на дюйм).<br/> Применяется метод создания изображения, кроме изображения в формате Emf.|
| [tiff_compression](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Получает или задает тип сжатия, который будет применяться только при сохранении страниц в формате `Tiff`.|
| [tiff_color_depth](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Получает или задает разрядность, которая применяется только при сохранении страниц в формате `Tiff`.|
| [tiff_binarization_method](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Получает или задает метод, используемый при преобразовании изображений в формат 1 бит на пиксель.<br/> когда [`ImageOrPrintOptions.image_type`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#image_type) — это Tiff, а [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#tiff_compression) равно Ccitt3 или Ccitt4.|
| [printing_page](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/printing_page) | Указывает, какие страницы не будут распечатаны.|
| [quality](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/quality) | Получает или задает значение, определяющее качество создаваемых изображений.<br/> применять только при сохранении страниц в формате `Jpeg`. Значение по умолчанию – 100.|
| [image_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/image_type) | Получает или задает формат создаваемых изображений.<br/> значение по умолчанию: PNG.|
| [is_cell_auto_fit](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Указывает, подгоняется ли ширина и высота ячеек автоматически по значению ячейки.<br/> Значение по умолчанию неверно.|
| [one_page_per_sheet](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | Если OnePagePerSheet имеет значение true , все содержимое одного листа в результате будет выведено только на одну страницу.<br/> Размер бумаги в настройках страницы будет недействительным, а другие настройки страницы<br/> все равно вступит в силу.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | Если AllColumnsInOnePagePerSheet имеет значение true , все содержимое столбцов одного листа будет выводиться только на одну страницу.<br/>Ширина бумаги в настройках страницы будет недействительной, а другие настройки в настройках страницы<br/> все равно вступит в силу.|
| [draw_object_event_handler](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/draw_object_event_handler) | Реализует этот интерфейс для получения DrawObject и Bound при рендеринге.|
| [chart_image_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Укажите тип изображения диаграммы при конвертации.<br/> значение по умолчанию: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Укажите имя файла встроенного изображения в формате svg.<br/> Это должен быть полный путь к каталогу типа «c:\\xpsEmbedded».|
| [svg_fit_to_view_port](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | если это свойство истинно, сгенерированный SVG будет соответствовать порту просмотра.|
| [only_area](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/only_area) | Если это свойство имеет значение true , будет выведена одна область, и масштаб не вступит в силу.|
| [text_rendering_hint](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Определяет качество рендеринга текста.<br/> Значение по умолчанию — TextRenderingHint.SystemDefault.|
| [smoothing_mode](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Указывает, применяется ли сглаживание (сглаживание) к линиям и кривым, а также к краям заполненных областей.<br/> Значение по умолчанию — SmoothingMode.None.|
| [transparent](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/transparent) | Указывает, должен ли фон сгенерированного изображения быть прозрачным.|
| [pixel_format](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/pixel_format) | Получает или задает формат пикселей для создаваемых изображений.|
| [warning_callback](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [page_saving_callback](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/page_saving_callback) | Контролируйте/отображайте ход процесса сохранения страницы.|
| [is_font_substitution_char_granularity](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |Указывает, следует ли заменять шрифт символа только в том случае, если шрифт ячейки несовместим с ним.|
| [page_index](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/page_index) | Получает или задает индекс первой сохраняемой страницы, отсчитываемый от 0.|
| [page_count](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/page_count) | Получает или задает количество сохраняемых страниц.|
| [is_optimized](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/is_optimized) | Указывает, следует ли оптимизировать выходные элементы.|
| [default_font](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/>Установите DefaultFont, например MingLiu или MS Gothic, чтобы отобразить эти символы.<br/> Если это свойство не установлено, Aspose.Cells будет использовать системный шрифт по умолчанию для отображения этих символов Юникода.|
| [check_workbook_default_font](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/> Установите для этого параметра значение true, чтобы попытаться использовать шрифт книги по умолчанию для отображения этих символов в первую очередь.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Указывает, выводить ли пустую страницу, если печатать нечего.|
| [gridline_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/gridline_type) | Получает или задает тип линии сетки.|
| [text_cross_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Получает или задает отображаемый тип текста, когда ширина текста больше ширины ячейки.|
| [emf_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/emf_type) | Получает или задает EmfType, указывающий формат метафайла.<br/>Значение по умолчанию — EmfPlusDual.|
| [default_edit_language](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Получает или задает язык редактирования по умолчанию.|
| [sheet_set](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/sheet_set) |Получает или задает листы для визуализации. По умолчанию — все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Настройка рендеринга метафайла Emf.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_desired_size](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Устанавливает желаемую ширину и высоту изображения.|
| [set_desired_size](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Устанавливает желаемую ширину и высоту изображения.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  Смотрите также
* модуль [`aspose.cells.rendering`](..)
