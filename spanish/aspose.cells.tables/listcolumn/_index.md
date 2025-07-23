---
title: ListColumn clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn clase
Representa una columna en una tabla.



El tipo ListColumn expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [name](/cells/python-net/es/aspose.cells.tables/listcolumn/name) | Obtiene y establece el nombre de la columna.|
| [totals_calculation](/cells/python-net/es/aspose.cells.tables/listcolumn/totals_calculation) | Obtiene y establece el tipo de cálculo en la fila Totales de la columna de lista.|
| [range](/cells/python-net/es/aspose.cells.tables/listcolumn/range) | Obtiene el rango de esta columna de lista.|
| [is_array_formula](/cells/python-net/es/aspose.cells.tables/listcolumn/is_array_formula) | Indica si la fórmula es una fórmula matricial.|
| [formula](/cells/python-net/es/aspose.cells.tables/listcolumn/formula) | Obtiene y establece la fórmula de la columna de lista.|
| [totals_row_label](/cells/python-net/es/aspose.cells.tables/listcolumn/totals_row_label) | Obtiene y establece las etiquetas de visualización de la fila total.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | Obtiene la fórmula de la fila de totales de esta columna de lista.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | Obtiene la fórmula de la fila de totales de esta columna de lista.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | Obtiene la fórmula de esta columna de lista.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/es/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | Establece la fórmula para esta columna de lista.|
| [`get_data_style(self)`](/cells/python-net/es/aspose.cells.tables/listcolumn/get_data_style/#) | Obtiene el estilo de los datos en esta columna de la tabla.|
| [`set_data_style(self, style)`](/cells/python-net/es/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | Establece el estilo de los datos en esta columna de la tabla.|



###  Ejemplo

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

###  Ver también
* módulo [`aspose.cells.tables`](..)
