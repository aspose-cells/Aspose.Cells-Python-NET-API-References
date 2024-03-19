---
title: HtmlSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 810
url: /ru/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions класс
Представляет параметры сохранения HTML-файла.



**Наследование:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип HtmlSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/htmlsaveoptions/__init__/#) | Создает параметры для сохранения html-файла.|
| [__init__](/cells/python-net/ru/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.SaveFormat) | Создает параметры для сохранения файла HTM.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/htmlsaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells/htmlsaveoptions/clear_data) | Сделайте книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/htmlsaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/htmlsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/htmlsaveoptions/merge_areas) | Указывает, нужно ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/htmlsaveoptions/create_directory) | Если это правда и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/htmlsaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/htmlsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells/htmlsaveoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/htmlsaveoptions/update_smart_art) | Указывает, обновляются ли настройки Smart Art.<br/> Значение по умолчанию неверно.|
| [ignore_invisible_shapes](/cells/python-net/ru/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Укажите, следует ли экспортировать невидимые фигуры.|
| [page_title](/cells/python-net/ru/aspose.cells/htmlsaveoptions/page_title) | Заголовок html-страницы.<br/> Только для сохранения в html-поток.|
| [attached_files_directory](/cells/python-net/ru/aspose.cells/htmlsaveoptions/attached_files_directory) | Каталог, в котором будут сохранены прикрепленные файлы.<br/> Только для сохранения в html-поток.|
| [attached_files_url_prefix](/cells/python-net/ru/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Укажите префикс URL-адреса прикрепленных файлов, например изображения в html-файле.<br/> Только для сохранения в html-поток.|
| [default_font_name](/cells/python-net/ru/aspose.cells/htmlsaveoptions/default_font_name) | Укажите имя шрифта по умолчанию для экспорта HTML. Шрифт по умолчанию будет использоваться, если шрифт стиля не существует.<br/>Если это свойство имеет значение null, Aspose.Cells будет использовать универсальный шрифт того же семейства, что и исходный шрифт.<br/> значение по умолчанию равно нулю.|
| [worksheet_scalable](/cells/python-net/ru/aspose.cells/htmlsaveoptions/worksheet_scalable) | Указывает, увеличивается ли масштаб HTML с помощью уровня масштабирования листа при сохранении файла в формате HTML, значение по умолчанию — false.|
| [is_export_comments](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_export_comments) |Указывает, что при экспорте комментариев при сохранении файла в формате html значение по умолчанию — false.|
| [export_comments_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_comments_type) | Представляет тип экспорта комментариев в файлы HTML.|
| [disable_downlevel_revealed_comments](/cells/python-net/ru/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Указывает, отключите ли условные комментарии, отображаемые на нижнем уровне, при экспорте файла в HTML, значение по умолчанию — false.|
| [is_exp_image_to_temp_dir](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Указывает, экспортируются ли файлы изображений во временный каталог.<br/> Только для сохранения в html-поток.|
| [image_scalable](/cells/python-net/ru/aspose.cells/htmlsaveoptions/image_scalable) | Указывает, используется ли масштабируемая единица измерения для описания ширины изображения.<br/>при использовании масштабируемой единицы для описания ширины столбца.<br/> Значение по умолчанию верно.|
| [width_scalable](/cells/python-net/ru/aspose.cells/htmlsaveoptions/width_scalable) | Указывает, экспортируется ли ширина столбца в единицах масштаба в HTML.<br/> Значение по умолчанию неверно.|
| [export_single_tab](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_single_tab) | Указывает, следует ли экспортировать одну вкладку, если файл содержит только один лист.<br/> Значение по умолчанию неверно.|
| [export_images_as_base64](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_images_as_base64) | Указывает, сохраняются ли изображения в формате Base64 в формате HTML, MHTML или EPUB.|
| [export_active_worksheet_only](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Указывает, экспортируется ли только активный лист в файл html.<br/>Если это правда, то только активный лист будет экспортирован в html-файл;<br/>Если установлено значение false, вся книга будет экспортирована в файл html.<br/> Значение по умолчанию неверно.|
| [export_print_area_only](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_print_area_only) | Указывает, экспортируется ли только область печати в файл html. Значение по умолчанию неверно.|
| [export_area](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_area) | Получает или задает экспортируемую CellArea текущего активного листа.<br/>Если вы установите этот атрибут, область печати текущего активного листа будет пропущена.<br/> При сохранении файла в html будет экспортирована только указанная область.|
| [parse_html_tag_in_cell](/cells/python-net/ru/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) |Указывает, должен ли HTML-тег (например, `<div></div>`) в ячейке анализироваться как значение ячейки или сохраняться как есть.<br/> Значение по умолчанию верно.|
| [html_cross_string_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/html_cross_string_type) | Указывает, будет ли строка между ячейками отображаться так же, как MS Excel, при сохранении файла Excel в формате html.<br/>По умолчанию используется значение «По умолчанию», поэтому для строк между ячейками разница между HTML-файлами, созданными с помощью Aspose.Cells, и MS Excel невелика.<br/> Но производительность создания больших html-файлов при установке значения Cross будет в несколько раз выше, чем при установке значения Default или Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Скрытый столбец (ширина этого столбца равна 0) в Excel, прежде чем сохранить его в формате html,<br/>если HtmlHiddenColDisplayType имеет значение «Удалить», скрытый столбец не будет выводиться,<br/> если значение «Скрытый», столбец будет выводиться, но был скрыт, значение по умолчанию — «Скрытый».|
| [hidden_row_display_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Скрытая строка (высота этой строки равна 0) в Excel, прежде чем сохранить ее в формате html,<br/>если HtmlHiddenRowDisplayType имеет значение «Удалить», скрытая строка не будет выводиться,<br/> если значение «Скрыто», строка будет выводиться, но была скрыта, значение по умолчанию — «Скрыто».|
| [encoding](/cells/python-net/ru/aspose.cells/htmlsaveoptions/encoding) | Если не установлено, используйте Encoding.UTF8 в качестве типа кодировки по умолчанию.|
| [export_object_listener](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_object_listener) | Получает или задает ExportObjectListener для экспорта объектов.|
| [file_path_provider](/cells/python-net/ru/aspose.cells/htmlsaveoptions/file_path_provider) |Получает или задает IFilePathProvider для отдельного экспорта листа в HTML.|
| [stream_provider](/cells/python-net/ru/aspose.cells/htmlsaveoptions/stream_provider) | Получает или задает IStreamProvider для экспорта объектов.|
| [image_options](/cells/python-net/ru/aspose.cells/htmlsaveoptions/image_options) | Получите объект ImageOrPrintOptions перед экспортом.|
| [save_as_single_file](/cells/python-net/ru/aspose.cells/htmlsaveoptions/save_as_single_file) | Указывает, следует ли сохранять HTML как один файл.<br/> Значение по умолчанию неверно.|
| [show_all_sheets](/cells/python-net/ru/aspose.cells/htmlsaveoptions/show_all_sheets) | Указывает, отображаются ли все листы при сохранении в виде одного HTML-файла.|
| [export_page_headers](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_page_headers) | Указывает, экспортируются ли заголовки страниц.|
| [export_page_footers](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_page_footers) | Указывает, экспортируются ли заголовки страниц.|
| [export_hidden_worksheet](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Указывает, экспортируется ли скрытое содержимое листа. Значение по умолчанию — true.|
| [presentation_preference](/cells/python-net/ru/aspose.cells/htmlsaveoptions/presentation_preference) | Указывает, является ли файл html или mht предпочтительным для представления.<br/>Значение по умолчанию неверно.<br/> если вы хотите получить более красивую презентацию, установите значение true.|
| [cell_css_prefix](/cells/python-net/ru/aspose.cells/htmlsaveoptions/cell_css_prefix) | Получает и устанавливает префикс имени CSS, значение по умолчанию — "".|
| [table_css_id](/cells/python-net/ru/aspose.cells/htmlsaveoptions/table_css_id) | Получает и устанавливает префикс имени типа CSS, например tr,col,td и т. д., они содержатся в элементе таблицы.<br/> который имеет определенный атрибут TableCssId. Значение по умолчанию — «».|
| [is_full_path_link](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_full_path_link) | Указывает, используется ли ссылка на полный путь в файлеsheet00x.htm,filelist.xml и tabstrip.htm.<br/> Значение по умолчанию неверно.|
| [export_worksheet_css_separately](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) |Указывает, нужно ли экспортировать CSS отдельно. Значение по умолчанию — false.|
| [export_similar_border_style](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_similar_border_style) | Указывает, следует ли экспортировать аналогичный стиль границы, если стиль границы не поддерживается браузерами.<br/>Если вы хотите импортировать файл html или mht в Excel, сохраните значение по умолчанию.<br/> Значение по умолчанию неверно.|
| [merge_empty_td_forcely](/cells/python-net/ru/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Указывает, нужно ли принудительно объединять пустой элемент TD при экспорте файла в HTML.<br/> Размер html-файла значительно уменьшится после установки значения true. Значение по умолчанию неверно.<br/> Если вы хотите импортировать HTML-файл в Excel или экспортировать идеальные линии сетки при сохранении файла в HTML,<br/> пожалуйста, сохраните значение по умолчанию.|
| [merge_empty_td_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/merge_empty_td_type) | Указывает, будет ли пустой элемент TD объединяться так же, как MS Excel, при сохранении файла Excel в формате html.<br/> Значение по умолчанию — MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Указывает, экспортируется ли координата Excel непустых ячеек при сохранении файла в HTML. Значение по умолчанию неверно.<br/> Если вы хотите импортировать выходной HTML-код в Excel, сохраните значение по умолчанию.|
| [export_extra_headings](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_extra_headings) | Указывает, следует ли экспортировать дополнительные заголовки, если длина текста превышает максимальную отображаемую колонку.<br/> Значение по умолчанию неверно. Если вы хотите импортировать HTML-файл в Excel, сохраните значение по умолчанию.|
| [export_headings](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_headings) |Указывает, экспортируются ли заголовки строк и столбцов листа при сохранении в файлы HTML.|
| [export_row_column_headings](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_row_column_headings) |Указывает, экспортируются ли заголовки строк и столбцов листа при сохранении в файлы HTML.|
| [export_formula](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_formula) | Указывает, экспортируется ли формула при сохранении файла в формате html. Значение по умолчанию верно.<br/> Если вы хотите импортировать выходной HTML-код в Excel, сохраните значение по умолчанию.|
| [add_tooltip_text](/cells/python-net/ru/aspose.cells/htmlsaveoptions/add_tooltip_text) | Указывает, следует ли добавлять текст всплывающей подсказки, когда данные не могут быть полностью отображены.<br/> Значение по умолчанию неверно.|
| [export_grid_lines](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_grid_lines) | Указывает, экспортируется ли линия сетки. Значение по умолчанию — false.|
| [export_bogus_row_data](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Указывает, экспортируются ли фиктивные данные нижней строки. Значение по умолчанию — true. Если вы хотите импортировать файл html или mht<br/> чтобы преуспеть, сохраните значение по умолчанию.|
| [exclude_unused_styles](/cells/python-net/ru/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Указывает, исключает ли неиспользуемые стили.<br/>Для сгенерированных html-файлов исключение неиспользуемых стилей может уменьшить размер файла.<br/>не влияя на визуальные эффекты. Таким образом, значение этого свойства по умолчанию — true.<br/>Если пользователю необходимо сохранить все стили в книге для сгенерированного HTML (например, сценарий, который пользователь<br/> необходимо позже восстановить книгу из сгенерированного HTML), установите для этого свойства значение false.|
| [export_document_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_document_properties) | Указывает, экспортируются ли свойства документа. Значение по умолчанию — true. Если вы хотите импортировать<br/> файл html или mht для Excel, оставьте значение по умолчанию.|
| [export_worksheet_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Указывает, экспортируются ли свойства листа. Значение по умолчанию — true. Если вы хотите импортировать<br/> файл html или mht для Excel, оставьте значение по умолчанию.|
| [export_workbook_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_workbook_properties) |Указывает, экспортируются ли свойства книги. Значение по умолчанию — true. Если вы хотите импортировать<br/> файл html или mht для Excel, оставьте значение по умолчанию.|
| [export_frame_scripts_and_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Указывает, экспортируются ли сценарии фреймов и свойства документа. Значение по умолчанию — true. Если вы хотите импортировать файл html или mht<br/> чтобы преуспеть, сохраните значение по умолчанию.|
| [export_data_options](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_data_options) | Указание правила экспорта данных html-файла. Значение по умолчанию — «Все».|
| [link_target_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/link_target_type) | Указание типа целевого атрибута в ссылке `<a>`. Значение по умолчанию — HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_ie_compatible) | Указывает, совместим ли вывод HTML с браузером IE.<br/> Значение по умолчанию неверно|
| [format_data_ignore_column_width](/cells/python-net/ru/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Указывает, показывать ли все форматированные данные ячейки при переполнении столбца.<br/>Если это правда, то игнорируйте ширину столбца, и все данные ячейки будут экспортированы.<br/>Если false, то данные будут экспортированы так же, как Excel.<br/> Значение по умолчанию неверно.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/htmlsaveoptions/calculate_formula) | Указывает, следует ли вычислять формулы перед сохранением HTML-файла.|
| [is_js_browser_compatible](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Указывает, совместим ли JavaScript с браузерами, которые не поддерживают JavaScript.<br/> Значение по умолчанию верно.|
| [is_mobile_compatible](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Указывает, совместим ли выход HTML с мобильными устройствами.<br/> Значение по умолчанию неверно.|
| [css_styles](/cells/python-net/ru/aspose.cells/htmlsaveoptions/css_styles) | Получает или задает дополнительные стили CSS для средства форматирования.<br/>Работает только тогда, когда [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/ru/aspose.cells/htmlsaveoptions#save_as_single_file) имеет значение True.<br/><br/> CssStyles="body {padding: 5px}";|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`HtmlSaveOptions`](/cells/python-net/ru/aspose.cells/htmlsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
