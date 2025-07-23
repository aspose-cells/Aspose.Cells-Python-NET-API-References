---
title: ImageOrPrintOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions класс
Позволяет указать параметры при преобразовании рабочего листа в изображение, печати рабочего листа или преобразовании диаграммы в изображение.



Тип ImageOrPrintOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/__init__/#) | Ctor.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/save_format) | Получает или задает тип формата выходного файла<br/> Поддержка Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | Если PrintWithStatusDialog = true, появится диалоговое окно, отображающее текущий статус печати.<br/> в противном случае диалоговое окно отображаться не будет.|
| [horizontal_resolution](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Получает или задает горизонтальное разрешение для создаваемых изображений в точках на дюйм.|
| [vertical_resolution](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Получает или задает вертикальное разрешение для создаваемых изображений в точках на дюйм.|
| [tiff_compression](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Возвращает или задает тип сжатия, применяемый только при сохранении страниц в формате `Tiff`.|
| [tiff_color_depth](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Возвращает или задает битовую глубину, применяемую только при сохранении страниц в формате `Tiff`.|
| [tiff_binarization_method](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Возвращает или задает метод, используемый при преобразовании изображений в формат 1 бит/пиксель<br/>когда [`ImageOrPrintOptions.image_type`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#image_type) — это Tiff, а [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#tiff_compression) равно Ccitt3 или Ccitt4.|
| [printing_page](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/printing_page) | Указывает, какие страницы не будут распечатаны.|
| [quality](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/quality) | Возвращает или задает значение, определяющее качество создаваемых изображений.<br/> Применять только при сохранении страниц в формате `Jpeg`. Значение по умолчанию — 100.|
| [image_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/image_type) | Получает или задает формат создаваемых изображений.<br/> значение по умолчанию: PNG.|
| [is_cell_auto_fit](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Указывает, будет ли ширина и высота ячеек автоматически подбираться в соответствии со значением ячейки.<br/> Значение по умолчанию — false.|
| [one_page_per_sheet](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | Если OnePagePerSheet имеет значение true, все содержимое одного листа будет выведено только на одну страницу в результате.<br/> Размер бумаги pagesetup будет недействительным, а другие настройки pagesetup<br/> все равно вступит в силу.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | Если AllColumnsInOnePagePerSheet имеет значение true, все содержимое столбцов одного листа будет выведено только на одну страницу в результате.<br/> Ширина размера бумаги в настройках страницы будет недействительной, а другие настройки настроек страницы<br/> все равно вступит в силу.|
| [chart_image_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Укажите тип изображения диаграммы при конвертации.<br/> значение по умолчанию: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Укажите имя файла встроенного изображения в формате svg.<br/> Это должен быть полный путь с каталогом, например "c:\\xpsEmbedded".|
| [svg_fit_to_view_port](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | Если это свойство имеет значение true, сгенерированный SVG-файл будет соответствовать области просмотра.|
| [svg_css_prefix](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/svg_css_prefix) |Получает и задает префикс имени CSS в SVG, значение по умолчанию — пустая строка.|
| [only_area](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/only_area) | Если это свойство имеет значение true, будет выведена одна область, и масштабирование не применяется.|
| [text_rendering_hint](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Определяет качество отображения текста.<br/> Значение по умолчанию — TextRenderingHint.SystemDefault.|
| [smoothing_mode](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Указывает, применяется ли сглаживание (антиалиасинг) к линиям и кривым, а также к краям заполненных областей.<br/> Значение по умолчанию — SmoothingMode.None.|
| [transparent](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/transparent) | Указывает, должен ли фон создаваемого изображения быть прозрачным.|
| [pixel_format](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/pixel_format) | Получает или задает формат пикселей для создаваемых изображений.|
| [is_font_substitution_char_granularity](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) | Указывает, следует ли заменять шрифт символа только в том случае, если шрифт ячейки с ним несовместим.|
| [page_index](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/page_index) | Возвращает или задает индекс (начиная с 0) первой страницы для сохранения.|
| [page_count](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/page_count) | Возвращает или задает количество сохраняемых страниц.|
| [is_optimized](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/is_optimized) | Указывает, следует ли оптимизировать выходные элементы.|
| [default_font](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/default_font) | Если символы в Excel являются символами Unicode и им не задан правильный шрифт в стиле ячейки,<br/>Они могут отображаться в виде блока в PDF-файле, изображения.<br/>Установите шрифт по умолчанию, например MingLiu или MS Gothic, чтобы отобразить эти символы.<br/>Если это свойство не задано, Aspose.Cells будет использовать системный шрифт по умолчанию для отображения этих символов Unicode.|
| [check_workbook_default_font](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | Если символы в Excel являются символами Unicode и им не задан правильный шрифт в стиле ячейки,<br/>Они могут отображаться в виде блока в PDF-файле, изображения.<br/> Установите значение true, чтобы попытаться использовать шрифт рабочей книги по умолчанию для отображения этих символов в первую очередь.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Указывает, следует ли выводить пустую страницу, если печатать нечего.|
| [gridline_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/gridline_type) | Получает или задает тип линии сетки.|
| [gridline_color](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/gridline_color) | Получает или задает цвет сетки.|
| [text_cross_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Возвращает или задает тип отображаемого текста, когда ширина текста больше ширины ячейки.|
| [emf_type](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/emf_type) | Возвращает или задает EmfType, который определяет формат метафайла.<br/> Значение по умолчанию — EmfPlusDual.|
| [default_edit_language](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Получает или задает язык редактирования по умолчанию.|
| [sheet_set](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/sheet_set) | Получает или задаёт листы для отображения. По умолчанию отображаются все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Настройка для рендеринга метафайлов Emf в исходном файле.|
| [custom_render_settings](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/custom_render_settings) | Получает или задает пользовательские настройки во время рендеринга.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Устанавливает желаемую ширину и высоту изображения.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Устанавливает желаемую ширину и высоту изображения.|



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
