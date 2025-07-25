---
title: FormatConditionCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 710
url: /es/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection clase
Representa formato condicional.
Las condiciones de formato pueden contener hasta tres formatos condicionales.



El tipo FormatConditionCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [count](/cells/python-net/es/aspose.cells/formatconditioncollection/count) | Obtiene el recuento de las condiciones.|
| [range_count](/cells/python-net/es/aspose.cells/formatconditioncollection/range_count) | Obtiene el recuento de rangos formateados condicionalmente.|



Obtiene la condición de formato por índice.
###  Indexador
| Nombre| Descripción|
| :- | :- |
| [index] | el índice de la condición de formato a devolver.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add_condition(self, type, operator_type, formula1, formula2)`](/cells/python-net/es/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) | Agrega una condición de formato.|
| [`add_condition(self, type)`](/cells/python-net/es/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype) | Añadir una condición de formato.|
| [`remove_area(self, index)`](/cells/python-net/es/aspose.cells/formatconditioncollection/remove_area/#int) | Elimina el rango de celdas con formato condicional por índice.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/es/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Eliminar el formato condicional del rango.|
| [`add(self, cell_area, type, operator_type, formula1, formula2)`](/cells/python-net/es/aspose.cells/formatconditioncollection/add/#aspose.cells.cellarea-aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) |Agrega una condición de formato y un rango de celdas afectado a FormatConditions<br/>Las condiciones de formato pueden contener hasta tres formatos condicionales.<br/> No se permiten referencias a otras hojas en las fórmulas de formato condicional.|
| [`add_area(self, cell_area)`](/cells/python-net/es/aspose.cells/formatconditioncollection/add_area/#aspose.cells.cellarea) | Agrega un rango de celdas con formato condicional.|
| [`get_cell_area(self, index)`](/cells/python-net/es/aspose.cells/formatconditioncollection/get_cell_area/#int) | Obtiene el rango de celdas con formato condicional por índice.|
| [`remove_condition(self, index)`](/cells/python-net/es/aspose.cells/formatconditioncollection/remove_condition/#int) | Elimina la condición de formato por índice.|



###  Ejemplo

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
