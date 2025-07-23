---
title: ListColumn класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn класс
Представляет столбец в таблице.



Тип ListColumn предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [name](/cells/python-net/ru/aspose.cells.tables/listcolumn/name) | Получает и задает имя столбца.|
| [totals_calculation](/cells/python-net/ru/aspose.cells.tables/listcolumn/totals_calculation) | Возвращает и задает тип расчета в строке «Итоги» столбца списка.|
| [range](/cells/python-net/ru/aspose.cells.tables/listcolumn/range) | Получает диапазон этого столбца списка.|
| [is_array_formula](/cells/python-net/ru/aspose.cells.tables/listcolumn/is_array_formula) | Указывает, является ли формула формулой массива.|
| [formula](/cells/python-net/ru/aspose.cells.tables/listcolumn/formula) | Получает и задает формулу столбца списка.|
| [totals_row_label](/cells/python-net/ru/aspose.cells.tables/listcolumn/totals_row_label) | Получает и задает отображаемые метки общей строки.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | Получает формулу итоговой строки этого столбца списка.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | Получает формулу итоговой строки этого столбца списка.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | Получает формулу этого столбца списка.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | Задает формулу для этого столбца списка.|
| [`get_data_style(self)`](/cells/python-net/ru/aspose.cells.tables/listcolumn/get_data_style/#) | Получает стиль данных в этом столбце таблицы.|
| [`set_data_style(self, style)`](/cells/python-net/ru/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | Задает стиль данных в этом столбце таблицы.|



###  Пример

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(4):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
listColumn = table.list_columns[4]
listColumn.totals_calculation = TotalsCalculation.SUM
listColumn.formula = "=[A]"
workbook.save(r"Book1.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.tables`](..)
