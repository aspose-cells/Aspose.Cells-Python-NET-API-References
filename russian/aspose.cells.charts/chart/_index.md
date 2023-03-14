---
title: Chart класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 30
url: /ru/aspose.cells.charts/chart/
is_root: false
---
##  Chart класс
Инкапсулирует объект, представляющий одну диаграмму Excel.



Тип Chart предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [style](/cells/python-net/ru/aspose.cells.charts/chart/style) | Получает и задает встроенный стиль.|
| [chart_object](/cells/python-net/ru/aspose.cells.charts/chart/chart_object) | Представляет диаграммуShape;|
| [hide_pivot_field_buttons](/cells/python-net/ru/aspose.cells.charts/chart/hide_pivot_field_buttons) |Указывает, следует ли скрывать кнопки поля сводной диаграммы только в том случае, если диаграмма является сводной диаграммой.|
| [pivot_options](/cells/python-net/ru/aspose.cells.charts/chart/pivot_options) | Задает элементы управления поворотом, которые отображаются на диаграмме.|
| [pivot_source](/cells/python-net/ru/aspose.cells.charts/chart/pivot_source) | Источником являются данные сводной таблицы.<br/> Если PivotSource не пуст, диаграмма является PivotChart.|
| [plot_by](/cells/python-net/ru/aspose.cells.charts/chart/plot_by) | Получает и задает график по строке или по столбцу.|
| [plot_empty_cells_type](/cells/python-net/ru/aspose.cells.charts/chart/plot_empty_cells_type) | Получает и задает способ построения пустых ячеек.|
| [plot_visible_cells](/cells/python-net/ru/aspose.cells.charts/chart/plot_visible_cells) | Указывает, отображать ли только видимые ячейки.|
| [plot_visible_cells_only](/cells/python-net/ru/aspose.cells.charts/chart/plot_visible_cells_only) | Указывает, отображать ли на графике только видимые ячейки.|
| [display_na_as_blank](/cells/python-net/ru/aspose.cells.charts/chart/display_na_as_blank) | Указывает, отображается ли #N/A как пустое значение.|
| [name](/cells/python-net/ru/aspose.cells.charts/chart/name) | Получает и задает имя диаграммы.|
| [size_with_window](/cells/python-net/ru/aspose.cells.charts/chart/size_with_window) | Истинно, если Microsoft Excel изменяет размер диаграммы, чтобы она соответствовала размеру окна листа диаграммы.|
| [worksheet](/cells/python-net/ru/aspose.cells.charts/chart/worksheet) | Получает рабочий лист, содержащий эту диаграмму.|
| [shapes](/cells/python-net/ru/aspose.cells.charts/chart/shapes) | Возвращает все фигуры рисования на этой диаграмме.|
| [print_size](/cells/python-net/ru/aspose.cells.charts/chart/print_size) | Получает и задает размер напечатанной диаграммы.|
| [type](/cells/python-net/ru/aspose.cells.charts/chart/type) | Получает или задает тип диаграммы.|
| [n_series](/cells/python-net/ru/aspose.cells.charts/chart/n_series) | Получает коллекцию [SeriesCollection](/cells/python-net/ru/aspose.cells.charts/seriescollection), представляющую серию данных на диаграмме.|
| [title](/cells/python-net/ru/aspose.cells.charts/chart/title) | Получает заголовок диаграммы.|
| [sub_title](/cells/python-net/ru/aspose.cells.charts/chart/sub_title) | Получает подзаголовок диаграммы.<br/>Только для файла формата ODS.|
| [plot_area](/cells/python-net/ru/aspose.cells.charts/chart/plot_area) | Получает область графика диаграммы, которая включает метки делений оси.|
| [chart_area](/cells/python-net/ru/aspose.cells.charts/chart/chart_area) | Получает область диаграммы на листе.|
| [category_axis](/cells/python-net/ru/aspose.cells.charts/chart/category_axis) | Получает ось X диаграммы.|
| [value_axis](/cells/python-net/ru/aspose.cells.charts/chart/value_axis) | Получает ось Y диаграммы.|
| [second_value_axis](/cells/python-net/ru/aspose.cells.charts/chart/second_value_axis) | Получает вторую ось Y диаграммы.|
| [second_category_axis](/cells/python-net/ru/aspose.cells.charts/chart/second_category_axis) | Получает вторую ось X диаграммы.|
| [series_axis](/cells/python-net/ru/aspose.cells.charts/chart/series_axis) | Получает ось серии диаграммы.|
| [legend](/cells/python-net/ru/aspose.cells.charts/chart/legend) | Получает легенду диаграммы.|
| [chart_data_table](/cells/python-net/ru/aspose.cells.charts/chart/chart_data_table) | Представляет таблицу данных диаграммы.|
| [show_legend](/cells/python-net/ru/aspose.cells.charts/chart/show_legend) | Получает или задает значение, указывающее, будет ли отображаться легенда диаграммы. Значение по умолчанию верно.|
| [is_rectangular_cornered](/cells/python-net/ru/aspose.cells.charts/chart/is_rectangular_cornered) | Получает или задает значение, указывающее, имеет ли область диаграммы прямоугольные углы.<br/> Значение по умолчанию верно.|
| [show_data_table](/cells/python-net/ru/aspose.cells.charts/chart/show_data_table) | Получает или задает значение, указывающее, отображается ли на диаграмме таблица данных.|
| [first_slice_angle](/cells/python-net/ru/aspose.cells.charts/chart/first_slice_angle) | Получает или задает угол первого фрагмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от вертикали). Применяется только к круговым, трехмерным круговым и кольцевым диаграммам от 0 до 360.|
| [gap_width](/cells/python-net/ru/aspose.cells.charts/chart/gap_width) | Возвращает или задает расстояние между кластерами полос или столбцов в процентах от ширины полосы или столбца.<br/>Значение этого свойства должно находиться в диапазоне от 0 до 500.|
| [gap_depth](/cells/python-net/ru/aspose.cells.charts/chart/gap_depth) | Получает или задает расстояние между рядами данных на трехмерной диаграмме в процентах от ширины маркера.<br/>Значение этого свойства должно находиться в диапазоне от 0 до 500.|
| [floor](/cells/python-net/ru/aspose.cells.charts/chart/floor) | Возвращает объект [Chart.floor](/cells/python-net/ru/aspose.cells.charts/chart#floor), представляющий стены трехмерной диаграммы.|
| [walls](/cells/python-net/ru/aspose.cells.charts/chart/walls) | Возвращает объект [Chart.walls](/cells/python-net/ru/aspose.cells.charts/chart#walls), представляющий стены трехмерной диаграммы.|
| [back_wall](/cells/python-net/ru/aspose.cells.charts/chart/back_wall) | Возвращает объект [Chart.walls](/cells/python-net/ru/aspose.cells.charts/chart#walls), представляющий заднюю стенку трехмерной диаграммы.|
| [side_wall](/cells/python-net/ru/aspose.cells.charts/chart/side_wall) | Возвращает объект [Chart.walls](/cells/python-net/ru/aspose.cells.charts/chart#walls), представляющий боковую стенку трехмерной диаграммы.|
| [walls_and_gridlines_2d](/cells/python-net/ru/aspose.cells.charts/chart/walls_and_gridlines_2d) | Значение true, если линии сетки на трехмерной диаграмме отображаются двумерными.|
| [rotation_angle](/cells/python-net/ru/aspose.cells.charts/chart/rotation_angle) | Представляет поворот представления трехмерной диаграммы (поворот области графика вокруг оси Z в градусах).|
| [elevation](/cells/python-net/ru/aspose.cells.charts/chart/elevation) | Представляет высоту представления трехмерной карты в градусах.|
| [right_angle_axes](/cells/python-net/ru/aspose.cells.charts/chart/right_angle_axes) | Истинно, если оси диаграммы расположены под прямым углом. Применяется только для трехмерных диаграмм (кроме Column3D и трехмерных круговых диаграмм).|
| [auto_scaling](/cells/python-net/ru/aspose.cells.charts/chart/auto_scaling) | Значение true, если Microsoft Excel масштабирует трехмерную диаграмму так, чтобы она была ближе по размеру к эквивалентной двумерной диаграмме.<br/> Свойство RightAngleAxes должно быть равно True.|
| [height_percent](/cells/python-net/ru/aspose.cells.charts/chart/height_percent) |Возвращает или задает высоту трехмерной диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов).|
| [perspective](/cells/python-net/ru/aspose.cells.charts/chart/perspective) | Возвращает или задает перспективу для представления трехмерной диаграммы. Должно быть от 0 до 100.<br/> Это свойство игнорируется, если свойство RightAngleAxes имеет значение True.|
| [is_3d](/cells/python-net/ru/aspose.cells.charts/chart/is_3d) | Указывает, является ли диаграмма трехмерной.|
| [depth_percent](/cells/python-net/ru/aspose.cells.charts/chart/depth_percent) | Представляет глубину трехмерной диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов).|
| [actual_chart_size](/cells/python-net/ru/aspose.cells.charts/chart/actual_chart_size) | Получает фактический размер диаграммы в пикселях.|
| [placement](/cells/python-net/ru/aspose.cells.charts/chart/placement) | Представляет способ прикрепления диаграммы к ячейкам под ней.|
| [page_setup](/cells/python-net/ru/aspose.cells.charts/chart/page_setup) | Представляет описание настройки страницы на этой диаграмме.|
| [line](/cells/python-net/ru/aspose.cells.charts/chart/line) | Получает строку.|


###  Методы
| Метод| Описание|
| :- | :- |
| [to_image(image_file)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str) | Создает изображение диаграммы и сохраняет его в файл.<br/> Расширение имени файла определяет формат изображения.|
| [to_image(image_file, image_type)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str-aspose.cells.drawing.ImageType) | Создает изображение диаграммы и сохраняет его в файл с указанным типом изображения.|
| [to_image(image_file, jpeg_quality)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str-int) | Создает изображение диаграммы и сохраняет его в файл в формате Jpeg.|
| [to_image(stream, jpeg_quality)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#io.RawIOBase-int) | Создает изображение диаграммы и сохраняет его в поток в формате Jpeg.|
| [to_image(stream, image_type)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#io.RawIOBase-aspose.cells.drawing.ImageType) |Создает изображение диаграммы и сохраняет его в потоке в указанном формате.|
| [to_image(image_file, options)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str-aspose.cells.rendering.ImageOrPrintOptions) | Создает изображение диаграммы и сохраняет его в файл.<br/> Расширение имени файла определяет формат изображения.|
| [to_image(stream, options)](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions) |Создает изображение диаграммы и сохраняет его в потоке в указанном формате.|
| [to_pdf(file_name)](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#str) | Сохраняет диаграмму в файл pdf.|
| [to_pdf(file_name, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type)](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#str-float-float-PageLayoutAlignmentType-PageLayoutAlignmentType) | Сохраняет диаграмму в файл pdf.|
| [to_pdf(stream)](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#io.RawIOBase) | Создает диаграмму в формате pdf и сохраняет ее в поток.|
| [to_pdf(stream, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type)](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#io.RawIOBase-float-float-PageLayoutAlignmentType-PageLayoutAlignmentType) | Создает диаграмму в формате pdf и сохраняет ее в поток.|
| [is_chart_data_changed()](/cells/python-net/ru/aspose.cells.charts/chart/is_chart_data_changed/#) | Определяет, изменился ли источник данных диаграммы.|
| [refresh_pivot_data()](/cells/python-net/ru/aspose.cells.charts/chart/refresh_pivot_data/#) | Обновляет данные сводной диаграммы из ее источника сводных данных.|
| [change_template(data)](/cells/python-net/ru/aspose.cells.charts/chart/change_template/#bytes) | Измените тип диаграммы с помощью предустановленного шаблона.|
| [move(upper_left_row, upper_left_column, lower_right_row, lower_right_column)](/cells/python-net/ru/aspose.cells.charts/chart/move/#int-int-int-int) | Перемещает диаграмму в указанное место.|
| [calculate()](/cells/python-net/ru/aspose.cells.charts/chart/calculate/#) | Вычисляет пользовательское положение области графика, осей, если их положение назначено автоматически.|
| [get_actual_size()](/cells/python-net/ru/aspose.cells.charts/chart/get_actual_size/#) | Получает фактический размер диаграммы в пикселях.|
| [has_axis(aixs_type, is_primary)](/cells/python-net/ru/aspose.cells.charts/chart/has_axis/#AxisType-bool) | Возвращает, какие оси существуют на диаграмме.|
| [switch_row_column()](/cells/python-net/ru/aspose.cells.charts/chart/switch_row_column/#) | Переключает строку/столбец.|
| [get_chart_data_range()](/cells/python-net/ru/aspose.cells.charts/chart/get_chart_data_range/#) | Получает диапазон источника данных диаграммы.|
| [set_chart_data_range(area, is_vertical)](/cells/python-net/ru/aspose.cells.charts/chart/set_chart_data_range/#str-bool) | Указывает диапазон данных для диаграммы.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

workbook = Workbook()
sheet = workbook.worksheets[0]
cells = sheet.cells
cells.get(0, 1).put_value("Income")
cells.get(1, 0).put_value("Company A")
cells.get(2, 0).put_value("Company B")
cells.get(3, 0).put_value("Company C")
cells.get(1, 1).put_value(10000)
cells.get(2, 1).put_value(20000)
cells.get(3, 1).put_value(30000)
chartIndex = sheet.charts.add(ChartType.COLUMN, 9, 9, 21, 15)
chart = sheet.charts[chartIndex]
chart.set_chart_data_range("A1:B4", True)
chart.show_legend = True
chart.title.text = "Income Analysis"

```

###  Смотрите также
* модуль [aspose.cells.charts](..)
* класс [SeriesCollection](/cells/python-net/ru/aspose.cells.charts/seriescollection)
