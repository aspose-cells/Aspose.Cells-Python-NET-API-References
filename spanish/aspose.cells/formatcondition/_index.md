---
title: FormatCondition clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 720
url: /es/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition clase
Representa la condición de formato condicional.



El tipo FormatCondition expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [formula1](/cells/python-net/es/aspose.cells/formatcondition/formula1) | Obtiene y establece el valor o expresión asociada al formato condicional.|
| [formula2](/cells/python-net/es/aspose.cells/formatcondition/formula2) | Obtiene y establece el valor o expresión asociada al formato condicional.|
| [operator](/cells/python-net/es/aspose.cells/formatcondition/operator) | Obtiene y establece el tipo de operador de formato condicional.|
| [stop_if_true](/cells/python-net/es/aspose.cells/formatcondition/stop_if_true) | Es cierto que no se pueden aplicar reglas con menor prioridad que esta regla cuando esta regla se evalúa como verdadera.<br/> Sólo aplica para Excel 2007;|
| [priority](/cells/python-net/es/aspose.cells/formatcondition/priority) | La prioridad de esta regla de formato condicional. Este valor se utiliza para determinar qué<br/>El formato debe ser evaluado y renderizado. Los valores numéricos más bajos tienen mayor prioridad que<br/> valores numéricos más altos, donde '1' es la prioridad más alta.|
| [style](/cells/python-net/es/aspose.cells/formatcondition/style) | Obtiene o establece el estilo de los rangos de celdas con formato condicional.|
| [type](/cells/python-net/es/aspose.cells/formatcondition/type) |Obtiene y establece si el formato condicional es Tipo.|
| [icon_set](/cells/python-net/es/aspose.cells/formatcondition/icon_set) | Obtenga la instancia "IconSet" del formato condicional.<br/>El IconSetType de la instancia predeterminada es TrafficLights31.<br/> Válido sólo para tipo = IconSet.|
| [data_bar](/cells/python-net/es/aspose.cells/formatcondition/data_bar) | Obtenga la instancia "DataBar" del formato condicional.<br/>El color predeterminado de la instancia es azul.<br/> Válido sólo para el tipo DataBar.|
| [color_scale](/cells/python-net/es/aspose.cells/formatcondition/color_scale) | Obtenga la instancia "ColorScale" del formato condicional.<br/>La instancia predeterminada es un 3ColorScale "verde-amarillo-rojo".<br/> Válido sólo para tipo = ColorScale.|
| [top10](/cells/python-net/es/aspose.cells/formatcondition/top10) | Obtenga la instancia "Top10" del formato condicional.<br/>La regla de la instancia predeterminada resalta las celdas cuyas<br/>los valores se encuentran en el grupo de los 10 primeros.<br/> Válido únicamente para el tipo Top10.|
| [above_average](/cells/python-net/es/aspose.cells/formatcondition/above_average) | Obtenga la instancia "AboveAverage" del formato condicional.<br/> La regla de la instancia predeterminada resalta las celdas que están<br/>por encima del promedio para todos los valores del rango.<br/>Válido sólo para tipo = AboveAverage.|
| [text](/cells/python-net/es/aspose.cells/formatcondition/text) | El valor de texto en una regla de formato condicional "el texto contiene".<br/>Válido solo para tipo = contieneTexto, noContieneTexto, comienzaCon y terminaCon.<br/> El valor predeterminado es nulo.|
| [time_period](/cells/python-net/es/aspose.cells/formatcondition/time_period) | El período de tiempo aplicable en una regla de formato condicional "fecha que ocurrió...".<br/>Válido sólo para tipo = timePeriod.<br/> El valor predeterminado es TimePeriodType.Today.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [get_formula1](/cells/python-net/es/aspose.cells/formatcondition/get_formula1/#bool-bool) | Obtiene el valor o expresión asociada a esta condición de formato.|
| [get_formula1](/cells/python-net/es/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Obtiene el valor o expresión del formato condicional de la celda.|
| [get_formula1](/cells/python-net/es/aspose.cells/formatcondition/get_formula1/#int-int) | Obtiene la fórmula del formato condicional de la celda.|
| [get_formula2](/cells/python-net/es/aspose.cells/formatcondition/get_formula2/#bool-bool) | Obtiene el valor o expresión asociada a esta condición de formato.|
| [get_formula2](/cells/python-net/es/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Obtiene el valor o expresión del formato condicional de la celda.|
| [get_formula2](/cells/python-net/es/aspose.cells/formatcondition/get_formula2/#int-int) | Obtiene la fórmula del formato condicional de la celda.|
| [set_formulas](/cells/python-net/es/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Establece el valor o expresión asociada con esta condición de formato.|
| [set_formula1](/cells/python-net/es/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Establece el valor o expresión asociada con esta condición de formato.|
| [set_formula2](/cells/python-net/es/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Establece el valor o expresión asociada con esta condición de formato.|



###  Ejemplo

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
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
