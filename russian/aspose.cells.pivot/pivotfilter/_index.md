---
title: PivotFilter класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 140
url: /ru/aspose.cells.pivot/pivotfilter/
is_root: false
---
##  PivotFilter класс
Представляет собой PivotFilter в коллекции PivotFilter.



Тип PivotFilter предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [use_whole_day](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/use_whole_day) | Указывает, используются ли целые дни в критериях фильтрации.|
| [auto_filter](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/auto_filter) | Получает автофильтр опорного фильтра.|
| [filter_type](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/filter_type) | Получает тип автофильтра для фильтра-опоры.|
| [field_index](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/field_index) | Возвращает индекс исходного поля, к которому применяется этот сводный фильтр.|
| [filter_category](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/filter_category) | Получает категорию этого фильтра.|
| [value1](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/value1) | Получает строковое значение1 фильтра опорной метки.|
| [value2](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/value2) | Получает строковое значение2 фильтра опорной метки.|
| [measure_fld_index](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/measure_fld_index) | Получает индекс поля меры сводного фильтра.|
| [value_field_index](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/value_field_index) | Получает индекс поля значения в области значений.|
| [measure_cube_field_index](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/measure_cube_field_index) | Указывает индекс поля куба меры.<br/>это свойство используется только фильтрами в сводных таблицах OLAP и указывает, к какой мере должен применяться фильтр значений.|
| [member_property_field_index](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/member_property_field_index) | Получает индекс поля свойств элемента сводного фильтра.|
| [name](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/name) | Получает имя фильтра-сводки.|
| [evaluation_order](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/evaluation_order) | Получает порядок оценки опорного фильтра.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_top_10_value(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/get_top_10_value/#) | Получает 10 лучших настроек фильтра.|
| [`get_labels(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/get_labels/#) | Получает метки фильтра субтитров.|
| [`get_number_values(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/get_number_values/#) | Получает значения числового фильтра.|
| [`get_date_time_values(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotfilter/get_date_time_values/#) | Получает значения числового фильтра.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Add top 10 filter
pivot.base_fields[0].filter_top10(0, PivotFilterType.COUNT, False, 2)
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
