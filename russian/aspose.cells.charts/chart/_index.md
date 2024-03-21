---
title: Chart класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 30
url: /ru/aspose.cells.charts/chart/
is_root: false
---
##  Chart класс
Инкапсулирует объект, представляющий одну диаграмму Excel.



Тип Chart предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [style](/cells/python-net/ru/aspose.cells.charts/chart/style) | Получает и устанавливает встроенный стиль.|
| [chart_object](/cells/python-net/ru/aspose.cells.charts/chart/chart_object) | Представляет диаграммуShape;|
| [hide_pivot_field_buttons](/cells/python-net/ru/aspose.cells.charts/chart/hide_pivot_field_buttons) | Указывает, следует ли скрывать кнопки полей сводной диаграммы, только если диаграмма является сводной диаграммой.|
| [pivot_options](/cells/python-net/ru/aspose.cells.charts/chart/pivot_options) | Указывает элементы управления сводкой, которые отображаются на диаграмме.|
| [pivot_source](/cells/python-net/ru/aspose.cells.charts/chart/pivot_source) |Источником являются данные сводной таблицы.<br/> Если PivotSource не пуст, это диаграмма PivotChart.|
| [plot_by](/cells/python-net/ru/aspose.cells.charts/chart/plot_by) | Получает и задает график построения по строке или по столбцу.|
| [plot_empty_cells_type](/cells/python-net/ru/aspose.cells.charts/chart/plot_empty_cells_type) | Получает и задает способ построения пустых ячеек.|
| [plot_visible_cells](/cells/python-net/ru/aspose.cells.charts/chart/plot_visible_cells) | Указывает, следует ли отображать только видимые ячейки.|
| [plot_visible_cells_only](/cells/python-net/ru/aspose.cells.charts/chart/plot_visible_cells_only) | Указывает, следует ли отображать только видимые ячейки.|
| [display_na_as_blank](/cells/python-net/ru/aspose.cells.charts/chart/display_na_as_blank) | Указывает, отображается ли #N/A как пустое значение.|
| [name](/cells/python-net/ru/aspose.cells.charts/chart/name) | Получает и задает имя диаграммы.|
| [size_with_window](/cells/python-net/ru/aspose.cells.charts/chart/size_with_window) | Истинно, если Microsoft Excel изменяет размер диаграммы в соответствии с размером окна листа диаграммы.|
| [worksheet](/cells/python-net/ru/aspose.cells.charts/chart/worksheet) | Получает лист, содержащий эту диаграмму.|
| [shapes](/cells/python-net/ru/aspose.cells.charts/chart/shapes) | Возвращает все фигуры рисунка на этой диаграмме.|
| [print_size](/cells/python-net/ru/aspose.cells.charts/chart/print_size) | Получает и задает размер печатаемой диаграммы.|
| [type](/cells/python-net/ru/aspose.cells.charts/chart/type) | Получает или задает тип диаграммы.|
| [n_series](/cells/python-net/ru/aspose.cells.charts/chart/n_series) | Получает коллекцию [`SeriesCollection`](/cells/python-net/ru/aspose.cells.charts/seriescollection), представляющую ряд данных на диаграмме.|
| [filtered_n_series](/cells/python-net/ru/aspose.cells.charts/chart/filtered_n_series) | Получает коллекцию [`SeriesCollection`](/cells/python-net/ru/aspose.cells.charts/seriescollection), представляющую ряды данных, отфильтрованные на диаграмме.|
| [title](/cells/python-net/ru/aspose.cells.charts/chart/title) | Получает заголовок диаграммы.|
| [sub_title](/cells/python-net/ru/aspose.cells.charts/chart/sub_title) | Получает подзаголовок диаграммы.<br/> Только для файла формата ODS.|
| [plot_area](/cells/python-net/ru/aspose.cells.charts/chart/plot_area) |Получает область графика диаграммы, включающую метки делений оси.|
| [chart_area](/cells/python-net/ru/aspose.cells.charts/chart/chart_area) | Получает область диаграммы на листе.|
| [category_axis](/cells/python-net/ru/aspose.cells.charts/chart/category_axis) | Получает ось X диаграммы.|
| [value_axis](/cells/python-net/ru/aspose.cells.charts/chart/value_axis) | Получает ось Y диаграммы.|
| [second_value_axis](/cells/python-net/ru/aspose.cells.charts/chart/second_value_axis) | Получает вторую ось Y диаграммы.|
| [second_category_axis](/cells/python-net/ru/aspose.cells.charts/chart/second_category_axis) | Получает вторую ось X диаграммы.|
| [series_axis](/cells/python-net/ru/aspose.cells.charts/chart/series_axis) | Получает ось рядов диаграммы.|
| [legend](/cells/python-net/ru/aspose.cells.charts/chart/legend) | Получает легенду диаграммы.|
| [chart_data_table](/cells/python-net/ru/aspose.cells.charts/chart/chart_data_table) | Представляет таблицу данных диаграммы.|
| [show_legend](/cells/python-net/ru/aspose.cells.charts/chart/show_legend) | Получает или задает значение, указывающее, будет ли отображаться легенда диаграммы. По умолчанию верно.|
| [is_rectangular_cornered](/cells/python-net/ru/aspose.cells.charts/chart/is_rectangular_cornered) | Получает или задает значение, указывающее, имеет ли область диаграммы прямоугольные углы.<br/> По умолчанию верно.|
| [show_data_table](/cells/python-net/ru/aspose.cells.charts/chart/show_data_table) | Получает или задает значение, указывающее, отображается ли на диаграмме таблица данных.|
| [first_slice_angle](/cells/python-net/ru/aspose.cells.charts/chart/first_slice_angle) | Получает или задает угол первого фрагмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от вертикали).<br/> Применяется только к круговым, трехмерным круговым и кольцевым диаграммам, от 0 до 360.|
| [gap_width](/cells/python-net/ru/aspose.cells.charts/chart/gap_width) | Возвращает или задает расстояние между кластерами полос или столбцов в процентах от ширины полосы или столбца.<br/> Значение этого свойства должно находиться в диапазоне от 0 до 500.|
| [gap_depth](/cells/python-net/ru/aspose.cells.charts/chart/gap_depth) |Получает или задает расстояние между рядами данных на трехмерной диаграмме в процентах от ширины маркера.<br/> Значение этого свойства должно находиться в диапазоне от 0 до 500.|
| [floor](/cells/python-net/ru/aspose.cells.charts/chart/floor) | Возвращает объект [`Chart.floor`](/cells/python-net/ru/aspose.cells.charts/chart#floor), представляющий стены трехмерной диаграммы.|
| [walls](/cells/python-net/ru/aspose.cells.charts/chart/walls) | Возвращает объект [`Chart.walls`](/cells/python-net/ru/aspose.cells.charts/chart#walls), представляющий стены трехмерной диаграммы.|
| [back_wall](/cells/python-net/ru/aspose.cells.charts/chart/back_wall) | Возвращает объект [`Chart.walls`](/cells/python-net/ru/aspose.cells.charts/chart#walls), представляющий заднюю стенку трехмерной диаграммы.|
| [side_wall](/cells/python-net/ru/aspose.cells.charts/chart/side_wall) | Возвращает объект [`Chart.walls`](/cells/python-net/ru/aspose.cells.charts/chart#walls), представляющий боковую стенку трехмерной диаграммы.|
| [walls_and_gridlines_2d](/cells/python-net/ru/aspose.cells.charts/chart/walls_and_gridlines_2d) | Истинно, если линии сетки нарисованы на трехмерной диаграмме в двухмерном виде.|
| [rotation_angle](/cells/python-net/ru/aspose.cells.charts/chart/rotation_angle) | Представляет вращение трехмерного представления диаграммы (поворот области графика вокруг оси Z в градусах).|
| [elevation](/cells/python-net/ru/aspose.cells.charts/chart/elevation) | Представляет высоту трехмерной карты в градусах.|
| [right_angle_axes](/cells/python-net/ru/aspose.cells.charts/chart/right_angle_axes) | Верно, если оси диаграммы расположены под прямым углом. Применяется только для трехмерных диаграмм (кроме Column3D и трехмерных круговых диаграмм).|
| [auto_scaling](/cells/python-net/ru/aspose.cells.charts/chart/auto_scaling) | Верно, если Microsoft Excel масштабирует трехмерную диаграмму так, чтобы она была ближе по размеру к эквивалентной двумерной диаграмме.<br/> Свойство RightAngleAxes должно иметь значение True.|
| [height_percent](/cells/python-net/ru/aspose.cells.charts/chart/height_percent) | Возвращает или задает высоту трехмерной диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов).|
| [perspective](/cells/python-net/ru/aspose.cells.charts/chart/perspective) |Возвращает или задает перспективу для представления трехмерной диаграммы. Должно быть от 0 до 100.<br/> Это свойство игнорируется, если свойство RightAngleAxes имеет значение True.|
| [is_3d](/cells/python-net/ru/aspose.cells.charts/chart/is_3d) | Указывает, является ли диаграмма трехмерной.|
| [depth_percent](/cells/python-net/ru/aspose.cells.charts/chart/depth_percent) | Представляет глубину трехмерной диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов).|
| [actual_chart_size](/cells/python-net/ru/aspose.cells.charts/chart/actual_chart_size) | Получает фактический размер диаграммы в пикселях.|
| [placement](/cells/python-net/ru/aspose.cells.charts/chart/placement) | Представляет способ прикрепления диаграммы к ячейкам под ней.|
| [page_setup](/cells/python-net/ru/aspose.cells.charts/chart/page_setup) | Представляет описание настройки страницы на этой диаграмме.|
| [line](/cells/python-net/ru/aspose.cells.charts/chart/line) | Получает линию.|


###  Методы
| Метод| Описание|
| :- | :- |
| [calculate](/cells/python-net/ru/aspose.cells.charts/chart/calculate/#) | Вычисляет пользовательское положение области графика и осей, если их положение назначено автоматически.|
| [calculate](/cells/python-net/ru/aspose.cells.charts/chart/calculate/#aspose.cells.charts.ChartCalculateOptions) | Вычисляет пользовательское положение области графика и осей, если их положение назначено автоматически, с помощью параметров расчета диаграммы.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str) | Создает изображение диаграммы и сохраняет его в файл.<br/> Расширение имени файла определяет формат изображения.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str-aspose.cells.drawing.ImageType) | Создает изображение диаграммы и сохраняет его в файл указанного типа изображения.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str-int) |Создает изображение диаграммы и сохраняет его в файл в формате Jpeg.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#io.RawIOBase-int) | Создает изображение диаграммы и сохраняет его в поток в формате Jpeg.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#io.RawIOBase-aspose.cells.drawing.ImageType) | Создает изображение диаграммы и сохраняет его в поток в указанном формате.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#str-aspose.cells.rendering.ImageOrPrintOptions) | Создает изображение диаграммы и сохраняет его в файл.<br/> Расширение имени файла определяет формат изображения.|
| [to_image](/cells/python-net/ru/aspose.cells.charts/chart/to_image/#io.RawIOBase-aspose.cells.rendering.ImageOrPrintOptions) | Создает изображение диаграммы и сохраняет его в поток в указанном формате.|
| [to_pdf](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#str) | Сохраняет диаграмму в файл PDF.|
| [to_pdf](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#str-float-float-aspose.cells.PageLayoutAlignmentType-aspose.cells.PageLayoutAlignmentType) | Сохраняет диаграмму в файл PDF.|
| [to_pdf](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#io.RawIOBase) | Создает диаграмму в формате PDF и сохраняет ее в поток.|
| [to_pdf](/cells/python-net/ru/aspose.cells.charts/chart/to_pdf/#io.RawIOBase-float-float-aspose.cells.PageLayoutAlignmentType-aspose.cells.PageLayoutAlignmentType) | Создает диаграмму в формате PDF и сохраняет ее в поток.|
| [is_refered_by_chart](/cells/python-net/ru/aspose.cells.charts/chart/is_refered_by_chart/#int-int) | Возвращает, на какую ячейку ссылается диаграмма.|
| [is_cell_refered_by_chart](/cells/python-net/ru/aspose.cells.charts/chart/is_cell_refered_by_chart/#int-int-int) | Возвращает, на какую ячейку ссылается диаграмма.|
| [is_chart_data_changed](/cells/python-net/ru/aspose.cells.charts/chart/is_chart_data_changed/#) | Обнаруживает, изменился ли источник данных диаграммы.|
| [refresh_pivot_data](/cells/python-net/ru/aspose.cells.charts/chart/refresh_pivot_data/#) | Обновляет данные сводной диаграммы из источника сводных данных.|
| [change_template](/cells/python-net/ru/aspose.cells.charts/chart/change_template/#bytes) | Измените тип диаграммы с помощью предустановленного шаблона.|
| [move](/cells/python-net/ru/aspose.cells.charts/chart/move/#int-int-int-int) | Перемещает диаграмму в указанное место.|
| [get_actual_size](/cells/python-net/ru/aspose.cells.charts/chart/get_actual_size/#) | Получает фактический размер диаграммы в пикселях.|
| [has_axis](/cells/python-net/ru/aspose.cells.charts/chart/has_axis/#aspose.cells.charts.AxisType-bool) | Возвращает сведения о том, какие оси существуют на диаграмме.|
| [switch_row_column](/cells/python-net/ru/aspose.cells.charts/chart/switch_row_column/#) | Переключает строку/столбец.|
| [get_chart_data_range](/cells/python-net/ru/aspose.cells.charts/chart/get_chart_data_range/#) | Получает диапазон источника данных диаграммы.|
| [set_chart_data_range](/cells/python-net/ru/aspose.cells.charts/chart/set_chart_data_range/#str-bool) | Указывает диапазон данных для диаграммы.|



###  Пример

Следующие коды показывают, как создать диаграмму с кодами .Net.

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
* модуль [`aspose.cells.charts`](..)
* класс [`SeriesCollection`](/cells/python-net/ru/aspose.cells.charts/seriescollection)
