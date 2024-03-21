---
title: EbookSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 10
url: /ru/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions класс
Представляет параметры сохранения файла электронной книги.



**Наследование:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип EbookSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/__init__/#) | Создает параметры для сохранения файла электронной книги.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/clear_data) | Сделайте книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/merge_areas) | Указывает, нужно ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/create_directory) | Если это правда и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [update_smart_art](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/update_smart_art) | Указывает, обновляются ли настройки Smart Art.
| [ignore_invisible_shapes](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | Укажите, следует ли экспортировать невидимые фигуры.|
| [page_title](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/page_title) | Заголовок html-страницы.
| [attached_files_directory](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | Каталог, в котором будут сохранены прикрепленные файлы.
| [attached_files_url_prefix](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | Укажите префикс URL-адреса прикрепленных файлов, например изображения в html-файле.
| [default_font_name](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/default_font_name) | Укажите имя шрифта по умолчанию для экспорта HTML. Шрифт по умолчанию будет использоваться, если шрифт стиля не существует.
| [worksheet_scalable](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | Указывает, увеличивается ли масштаб HTML с помощью уровня масштабирования листа при сохранении файла в формате HTML, значение по умолчанию — false.|
| [is_export_comments](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/is_export_comments) |Указывает, что при экспорте комментариев при сохранении файла в формате html значение по умолчанию — false.|
| [export_comments_type](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_comments_type) | Представляет тип экспорта комментариев в файлы HTML.|
| [disable_downlevel_revealed_comments](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | Указывает, отключите ли условные комментарии, отображаемые на нижнем уровне, при экспорте файла в HTML, значение по умолчанию — false.|
| [is_exp_image_to_temp_dir](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | Указывает, экспортируются ли файлы изображений во временный каталог.
| [image_scalable](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/image_scalable) | Указывает, используется ли масштабируемая единица измерения для описания ширины изображения.
| [width_scalable](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/width_scalable) | Указывает, экспортируется ли ширина столбца в единицах масштаба в HTML.
| [export_single_tab](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_single_tab) | Указывает, следует ли экспортировать одну вкладку, если файл содержит только один лист.
| [export_images_as_base64](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | Указывает, сохраняются ли изображения в формате Base64 в формате HTML, MHTML или EPUB.|
| [export_active_worksheet_only](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | Указывает, экспортируется ли только активный лист в файл html.
| [export_print_area_only](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_print_area_only) | Указывает, экспортируется ли только область печати в файл html. Значение по умолчанию неверно.|
| [export_area](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_area) | Получает или задает экспортируемую CellArea текущего активного листа.
| [parse_html_tag_in_cell](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) |Указывает, должен ли HTML-тег (например, `<div></div>`) в ячейке анализироваться как значение ячейки или сохраняться как есть.
| [html_cross_string_type](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | Указывает, будет ли строка между ячейками отображаться так же, как MS Excel, при сохранении файла Excel в формате html.
| [hidden_col_display_type](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Скрытый столбец (ширина этого столбца равна 0) в Excel, прежде чем сохранить его в формате html,
| [hidden_row_display_type](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Скрытая строка (высота этой строки равна 0) в Excel, прежде чем сохранить ее в формате html,
| [encoding](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/encoding) | Если не установлено, используйте Encoding.UTF8 в качестве типа кодировки по умолчанию.|
| [export_object_listener](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_object_listener) | Получает или задает ExportObjectListener для экспорта объектов.|
| [file_path_provider](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/file_path_provider) |Получает или задает IFilePathProvider для отдельного экспорта листа в HTML.|
| [stream_provider](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/stream_provider) | Получает или задает IStreamProvider для экспорта объектов.|
| [image_options](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/image_options) | Получите объект ImageOrPrintOptions перед экспортом.|
| [save_as_single_file](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | Указывает, следует ли сохранять HTML как один файл.
| [show_all_sheets](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | Указывает, отображаются ли все листы при сохранении в виде одного HTML-файла.|
| [export_page_headers](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_page_headers) | Указывает, экспортируются ли заголовки страниц.|
| [export_page_footers](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_page_footers) | Указывает, экспортируются ли заголовки страниц.|
| [export_hidden_worksheet](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | Указывает, экспортируется ли скрытое содержимое листа. Значение по умолчанию — true.|
| [presentation_preference](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/presentation_preference) | Указывает, является ли файл html или mht предпочтительным для представления.
| [cell_css_prefix](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | Получает и устанавливает префикс имени CSS, значение по умолчанию — "".|
| [table_css_id](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/table_css_id) | Получает и устанавливает префикс имени типа CSS, например tr,col,td и т. д., они содержатся в элементе таблицы.
| [is_full_path_link](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/is_full_path_link) | Указывает, используется ли ссылка на полный путь в файлеsheet00x.htm,filelist.xml и tabstrip.htm.
| [export_worksheet_css_separately](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) |Указывает, нужно ли экспортировать CSS отдельно. Значение по умолчанию — false.|
| [export_similar_border_style](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | Указывает, следует ли экспортировать аналогичный стиль границы, если стиль границы не поддерживается браузерами.
| [merge_empty_td_forcely](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | Указывает, нужно ли принудительно объединять пустой элемент TD при экспорте файла в HTML.
| [merge_empty_td_type](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | Указывает, будет ли пустой элемент TD объединяться так же, как MS Excel, при сохранении файла Excel в формате html.
| [export_cell_coordinate](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | Указывает, экспортируется ли координата Excel непустых ячеек при сохранении файла в HTML. Значение по умолчанию неверно.
| [export_extra_headings](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | Указывает, следует ли экспортировать дополнительные заголовки, если длина текста превышает максимальную отображаемую колонку.
| [export_headings](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_headings) |Указывает, экспортируются ли заголовки строк и столбцов листа при сохранении в файлы HTML.|
| [export_row_column_headings](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |Указывает, экспортируются ли заголовки строк и столбцов листа при сохранении в файлы HTML.|
| [export_formula](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_formula) | Указывает, экспортируется ли формула при сохранении файла в формате html. Значение по умолчанию верно.
| [add_tooltip_text](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | Указывает, следует ли добавлять текст всплывающей подсказки, когда данные не могут быть полностью отображены.
| [export_grid_lines](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | Указывает, экспортируется ли линия сетки. Значение по умолчанию — false.|
| [export_bogus_row_data](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | Указывает, экспортируются ли фиктивные данные нижней строки. Значение по умолчанию — true. Если вы хотите импортировать файл html или mht
| [exclude_unused_styles](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | Указывает, исключает ли неиспользуемые стили.
| [export_document_properties](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_document_properties) | Указывает, экспортируются ли свойства документа. Значение по умолчанию — true. Если вы хотите импортировать
| [export_worksheet_properties](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | Указывает, экспортируются ли свойства листа. Значение по умолчанию — true. Если вы хотите импортировать
| [export_workbook_properties](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |Указывает, экспортируются ли свойства книги. Значение по умолчанию — true. Если вы хотите импортировать
| [export_frame_scripts_and_properties](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | Указывает, экспортируются ли сценарии фреймов и свойства документа. Значение по умолчанию — true. Если вы хотите импортировать файл html или mht
| [export_data_options](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/export_data_options) | Указание правила экспорта данных html-файла. Значение по умолчанию — «Все».|
| [link_target_type](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/link_target_type) | Указание типа целевого атрибута в ссылке `<a>`. Значение по умолчанию — HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | Указывает, совместим ли вывод HTML с браузером IE.
| [format_data_ignore_column_width](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | Указывает, показывать ли все форматированные данные ячейки при переполнении столбца.
| [calculate_formula](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/calculate_formula) | Указывает, следует ли вычислять формулы перед сохранением HTML-файла.|
| [is_js_browser_compatible](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | Указывает, совместим ли JavaScript с браузерами, которые не поддерживают JavaScript.
| [is_mobile_compatible](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | Указывает, совместим ли выход HTML с мобильными устройствами.
| [css_styles](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions/css_styles) | Получает или задает дополнительные стили CSS для средства форматирования.



###  Смотрите также
* модуль [`aspose.cells.saving`](..)
* класс [`EbookSaveOptions`](/cells/python-net/ru/aspose.cells.saving/ebooksaveoptions)
* класс [`HtmlSaveOptions`](/cells/python-net/ru/aspose.cells/htmlsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)