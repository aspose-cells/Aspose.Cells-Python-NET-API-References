---
title: HtmlSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 790
url: /ru/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions класс
Представляет варианты сохранения HTML-файла.



**Наследование:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип HtmlSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/htmlsaveoptions/__init__/#) | Создает параметры для сохранения HTML-файла.|
| [`__init__(self, save_format)`](/cells/python-net/ru/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.saveformat) | Создает параметры для сохранения htm-файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/htmlsaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells/htmlsaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/htmlsaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/htmlsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/htmlsaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/htmlsaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/htmlsaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/htmlsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/htmlsaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/htmlsaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [ignore_invisible_shapes](/cells/python-net/ru/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Укажите, следует ли экспортировать те невидимые фигуры|
| [page_title](/cells/python-net/ru/aspose.cells/htmlsaveoptions/page_title) | Заголовок html-страницы.<br/> Только для сохранения в html-поток.|
| [attached_files_directory](/cells/python-net/ru/aspose.cells/htmlsaveoptions/attached_files_directory) | Каталог, в котором будут сохранены прикрепленные файлы.<br/> Только для сохранения в html-поток.|
| [attached_files_url_prefix](/cells/python-net/ru/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Укажите префикс URL прикрепленных файлов, например изображений в html-файле.<br/> Только для сохранения в html-поток.|
| [default_font_name](/cells/python-net/ru/aspose.cells/htmlsaveoptions/default_font_name) | Укажите имя шрифта по умолчанию для экспорта HTML. Шрифт по умолчанию будет использоваться, если шрифт стиля отсутствует.<br/>Если это свойство равно null, Aspose.Cells будет использовать универсальный шрифт, имеющий то же семейство, что и исходный шрифт,<br/> значение по умолчанию — ноль.|
| [add_generic_font](/cells/python-net/ru/aspose.cells/htmlsaveoptions/add_generic_font) |Указывает, следует ли добавлять общий шрифт в семейство шрифтов CSS.<br/> Значение по умолчанию — true.|
| [worksheet_scalable](/cells/python-net/ru/aspose.cells/htmlsaveoptions/worksheet_scalable) | Указывает, увеличивается или уменьшается масштаб HTML с помощью уровня масштабирования листа при сохранении файла в формате HTML; значение по умолчанию — false.|
| [is_export_comments](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_export_comments) | Указывает, экспортируются ли комментарии при сохранении файла в формате HTML, значение по умолчанию — false.|
| [export_comments_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_comments_type) | Представляет собой тип экспорта комментариев в html-файлы.|
| [disable_downlevel_revealed_comments](/cells/python-net/ru/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Указывает, следует ли отключить условные комментарии Downlevel-revealed при экспорте файла в HTML, значение по умолчанию — false.|
| [is_exp_image_to_temp_dir](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Указывает, следует ли экспортировать файлы изображений во временный каталог.<br/> Только для сохранения в html-поток.|
| [image_scalable](/cells/python-net/ru/aspose.cells/htmlsaveoptions/image_scalable) | Указывает, используется ли масштабируемая единица измерения для описания ширины изображения.<br/>при использовании масштабируемой единицы для описания ширины столбца.<br/> Значение по умолчанию — true.|
| [width_scalable](/cells/python-net/ru/aspose.cells/htmlsaveoptions/width_scalable) | Указывает, экспортировать ли ширину столбца в единицах масштаба в HTML.<br/> Значение по умолчанию — false.|
| [export_single_tab](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_single_tab) | Указывает, следует ли экспортировать одну вкладку, если файл содержит только один рабочий лист.<br/> Значение по умолчанию — false.|
| [export_images_as_base64](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_images_as_base64) | Указывает, сохраняются ли изображения в формате Base64 в HTML, MHTML или EPUB.|
| [export_active_worksheet_only](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Указывает, экспортируется ли только активный рабочий лист в HTML-файл.<br/>Если true, то только активный лист будет экспортирован в HTML-файл;<br/>Если false, то вся книга будет экспортирована в HTML-файл.<br/> Значение по умолчанию — false.|
| [export_print_area_only](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_print_area_only) |Указывает, экспортируется ли только область печати в HTML-файл. Значение по умолчанию — false.|
| [export_area](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_area) | Возвращает или задает экспортируемую область ячеек текущего активного рабочего листа.<br/>Если установить этот атрибут, область печати текущего активного листа будет пропущена.<br/> При сохранении файла в формате html будет экспортирована только указанная область.|
| [parse_html_tag_in_cell](/cells/python-net/ru/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) | Указывает, следует ли анализировать HTML-тег (например, `<div></div>`) в ячейке как значение ячейки или сохранять как есть.<br/> Значение по умолчанию — true.|
| [html_cross_string_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/html_cross_string_type) | Указывает, будет ли отображаться межъячейковая строка так же, как в MS Excel при сохранении файла Excel в формате html.<br/>По умолчанию установлено значение Default, поэтому для строк между ячейками разница между HTML-файлами, созданными Aspose.Cells и MS Excel, невелика.<br/> Но производительность создания больших HTML-файлов при установке значения Cross будет в несколько раз выше, чем при установке значения Default или Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Скрытый столбец (ширина этого столбца равна 0) в Excel, перед сохранением в формате HTML,<br/>Если HtmlHiddenColDisplayType равно «Remove», скрытый столбец не будет выводиться,<br/> Если значение «Скрыто», столбец будет выведен, но будет скрыт, значение по умолчанию — «Скрыто».|
| [hidden_row_display_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Скрытая строка (высота этой строки равна 0) в Excel, перед сохранением в формате HTML,<br/>Если HtmlHiddenRowDisplayType равно «Remove», то скрытая строка не будет выводиться,<br/>Если значение равно «Скрыто», строка будет выведена, но будет скрыта, значение по умолчанию — «Скрыто».|
| [encoding](/cells/python-net/ru/aspose.cells/htmlsaveoptions/encoding) | Если не установлено, используйте Encoding.UTF8 в качестве типа кодировки по умолчанию.|
| [image_options](/cells/python-net/ru/aspose.cells/htmlsaveoptions/image_options) | Получите объект ImageOrPrintOptions перед экспортом|
| [save_as_single_file](/cells/python-net/ru/aspose.cells/htmlsaveoptions/save_as_single_file) | Указывает, следует ли сохранять HTML как отдельный файл.<br/> Значение по умолчанию — false.|
| [show_all_sheets](/cells/python-net/ru/aspose.cells/htmlsaveoptions/show_all_sheets) | Указывает, показывать ли все листы при сохранении как одного HTML-файла.|
| [export_page_headers](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_page_headers) | Указывает, экспортируются ли заголовки страниц.|
| [export_page_footers](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_page_footers) | Указывает, экспортируются ли заголовки страниц.|
| [export_hidden_worksheet](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Указывает, экспортируется ли скрытое содержимое листа. Значение по умолчанию — true.|
| [presentation_preference](/cells/python-net/ru/aspose.cells/htmlsaveoptions/presentation_preference) | Указывает, какой файл (html или mht) является предпочтительным для представления.<br/>Значение по умолчанию — false.<br/> если вы хотите получить более красивое представление, установите значение true.|
| [cell_css_prefix](/cells/python-net/ru/aspose.cells/htmlsaveoptions/cell_css_prefix) | Получает и задает префикс имени CSS, значение по умолчанию — «».|
| [table_css_id](/cells/python-net/ru/aspose.cells/htmlsaveoptions/table_css_id) | Получает и задает префикс типа css-имени, например tr,col,td и т. д., они содержатся в элементе table.<br/> У которого есть специальный атрибут TableCssId. Значение по умолчанию — "".|
| [is_full_path_link](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_full_path_link) |Указывает, используется ли ссылка полного пути в sheet00x.htm,filelist.xml и tabstrip.htm.<br/> Значение по умолчанию — false.|
| [export_worksheet_css_separately](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) | Указывает, следует ли экспортировать CSS-код листа отдельно. Значение по умолчанию — false.|
| [export_similar_border_style](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_similar_border_style) | Указывает, следует ли экспортировать аналогичный стиль границы, если стиль границы не поддерживается браузерами.<br/>Если вы хотите импортировать файл HTML или MHT в Excel, оставьте значение по умолчанию.<br/> Значение по умолчанию — false.|
| [merge_empty_td_forcely](/cells/python-net/ru/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Указывает, принудительно ли объединяется пустой элемент TD при экспорте файла в html.<br/> Размер HTML-файла значительно уменьшится после установки значения true. Значение по умолчанию — false.<br/> Если вы хотите импортировать HTML-файл в Excel или экспортировать идеальные линии сетки при сохранении файла в HTML,<br/> пожалуйста, сохраните значение по умолчанию.|
| [merge_empty_td_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/merge_empty_td_type) | Возможность объединения смежных пустых ячеек (пустых элементов td)<br/> Значение по умолчанию — MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Указывает, экспортируются ли координаты непустых ячеек Excel при сохранении файла в HTML. Значение по умолчанию — false.<br/> Если вы хотите импортировать выходной HTML-код в Excel, оставьте значение по умолчанию.|
| [export_extra_headings](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_extra_headings) | Указывает, экспортировать ли дополнительные заголовки, если длина текста превышает максимальный отображаемый столбец.<br/> Значение по умолчанию — false. Если вы хотите импортировать HTML-файл в Excel, оставьте значение по умолчанию.|
| [export_headings](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_headings) |Указывает, экспортировать ли заголовки строк и столбцов листа при сохранении в файлы HTML.|
| [export_row_column_headings](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_row_column_headings) |Указывает, экспортировать ли заголовки строк и столбцов листа при сохранении в файлы HTML.|
| [export_formula](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_formula) | Указывает, экспортируется ли формула при сохранении файла в формате HTML. Значение по умолчанию — true.<br/> Если вы хотите импортировать выходной HTML-код в Excel, оставьте значение по умолчанию.|
| [add_tooltip_text](/cells/python-net/ru/aspose.cells/htmlsaveoptions/add_tooltip_text) | Указывает, следует ли добавлять текст подсказки, если данные не могут быть отображены полностью.<br/> Значение по умолчанию — false.|
| [export_grid_lines](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_grid_lines) | Указывает, экспортировать ли линии сетки. Значение по умолчанию — false.|
| [export_bogus_row_data](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Указывает, экспортируются ли фиктивные данные нижней строки. Значение по умолчанию — true. Если вы хотите импортировать файл HTML или MHT,<br/> для Excel оставьте значение по умолчанию.|
| [exclude_unused_styles](/cells/python-net/ru/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Указывает, следует ли исключать неиспользуемые стили.<br/>Для сгенерированных HTML-файлов исключение неиспользуемых стилей может уменьшить размер файла.<br/>без ущерба для визуальных эффектов. Поэтому значение этого свойства по умолчанию — true.<br/>Если пользователю необходимо сохранить все стили в рабочей книге для сгенерированного HTML-кода (например, сценарий, в котором пользователь<br/> необходимо восстановить рабочую книгу из сгенерированного HTML-кода позже), установите это свойство как false.|
| [export_document_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_document_properties) | Указывает, экспортируются ли свойства документа. Значение по умолчанию — true. Если вы хотите импортировать<br/> html или mht-файл в Excel, пожалуйста, оставьте значение по умолчанию.|
| [export_worksheet_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Указывает, экспортируются ли свойства листа. Значение по умолчанию — true. Если вы хотите импортировать<br/> html или mht-файл в Excel, пожалуйста, оставьте значение по умолчанию.|
| [export_workbook_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_workbook_properties) |Указывает, экспортируются ли свойства книги. Значение по умолчанию — true. Если вы хотите импортировать<br/> html или mht-файл в Excel, пожалуйста, оставьте значение по умолчанию.|
| [export_frame_scripts_and_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Указывает, экспортируются ли скрипты фреймов и свойства документа. Значение по умолчанию — true. Если вы хотите импортировать файл HTML или MHT,<br/> для Excel оставьте значение по умолчанию.|
| [export_data_options](/cells/python-net/ru/aspose.cells/htmlsaveoptions/export_data_options) | Указание правила экспорта данных HTML-файла. Значение по умолчанию — Все.|
| [link_target_type](/cells/python-net/ru/aspose.cells/htmlsaveoptions/link_target_type) | Указывает тип целевого атрибута в ссылке `<a>`. Значение по умолчанию — HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_ie_compatible) | Указывает, совместим ли вывод HTML с браузером IE.<br/> Значение по умолчанию — false|
| [format_data_ignore_column_width](/cells/python-net/ru/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Указывает, показывать ли все отформатированные данные ячейки при переполнении столбца.<br/>Если true, то ширина столбца игнорируется, и все данные ячейки будут экспортированы.<br/>Если false, то данные будут экспортированы так же, как в Excel.<br/> Значение по умолчанию — false.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/htmlsaveoptions/calculate_formula) | Указывает, следует ли вычислять формулы перед сохранением HTML-файла.|
| [is_js_browser_compatible](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Указывает, совместим ли JavaScript с браузерами, которые не поддерживают JavaScript.<br/> Значение по умолчанию — true.|
| [is_mobile_compatible](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Указывает, совместим ли вывод HTML с мобильными устройствами.<br/> Значение по умолчанию — false.|
| [css_styles](/cells/python-net/ru/aspose.cells/htmlsaveoptions/css_styles) | Получает или задает дополнительные стили CSS для форматировщика.<br/>Работает только если [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/ru/aspose.cells/htmlsaveoptions#save_as_single_file) имеет значение True.<br/><br/> CssStyles="body { padding: 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/ru/aspose.cells/htmlsaveoptions/hide_overflow_wrapped_text) |Указывает, следует ли скрывать переполненный текст, если формат ячейки настроен на перенос текста.<br/> Значение по умолчанию — false.|
| [is_border_collapsed](/cells/python-net/ru/aspose.cells/htmlsaveoptions/is_border_collapsed) | Указывает, свернуты ли границы таблицы.<br/> Значение по умолчанию — true.|
| [encode_entity_as_code](/cells/python-net/ru/aspose.cells/htmlsaveoptions/encode_entity_as_code) | Указывает, заменяются ли символы HTML десятичным кодом.<br/>(например, «&nbsp;» заменяется на «&#160;»).<br/> Значение по умолчанию — false.|
| [office_math_output_mode](/cells/python-net/ru/aspose.cells/htmlsaveoptions/office_math_output_mode) | Указывает, как экспортировать объекты OfficeMath в HTML. Значение по умолчанию — Изображение.|
| [cell_name_attribute](/cells/python-net/ru/aspose.cells/htmlsaveoptions/cell_name_attribute) | Задает атрибут, указывающий CellName, который необходимо записать.<br/>(например, если значение равно «id», то для ячейки «A1» вывод будет следующим:<td id='A1'>).<br/> Значение по умолчанию — ноль.|
| [disable_css](/cells/python-net/ru/aspose.cells/htmlsaveoptions/disable_css) | Указывает, применяются ли только встроенные стили, без использования CSS.<br/> Значение по умолчанию — false.|
| [enable_css_custom_properties](/cells/python-net/ru/aspose.cells/htmlsaveoptions/enable_css_custom_properties) | Оптимизируйте вывод HTML-кода с помощью пользовательских свойств CSS. Например, в случае, если одно изображение в формате base64 встречается несколько раз, с помощью пользовательского свойства данные изображения достаточно сохранить только один раз, что позволяет повысить производительность результирующего HTML-кода.<br/> Значение по умолчанию — false.|
| [html_version](/cells/python-net/ru/aspose.cells/htmlsaveoptions/html_version) | Указывает версию стандарта HTML, которую следует использовать при сохранении формата HTML.<br/> Значение по умолчанию — HtmlVersion.Default.|
| [sheet_set](/cells/python-net/ru/aspose.cells/htmlsaveoptions/sheet_set) | Получает или задаёт листы для отображения. По умолчанию отображаются все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`HtmlSaveOptions`](/cells/python-net/ru/aspose.cells/htmlsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
