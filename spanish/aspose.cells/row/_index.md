---
title: Row clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1340
url: /es/aspose.cells/row/
is_root: false
---
##  Row clase
Representa una sola fila en una hoja de trabajo.



El tipo Row expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_blank](/cells/python-net/es/aspose.cells/row/is_blank) | Indica si la fila contiene algún dato.|
| [is_collapsed](/cells/python-net/es/aspose.cells/row/is_collapsed) | si la fila está colapsada|
| [height](/cells/python-net/es/aspose.cells/row/height) | Obtiene y establece la altura de la fila en unidades de Puntos.|
| [is_hidden](/cells/python-net/es/aspose.cells/row/is_hidden) | Indica si la fila está oculta.|
| [index](/cells/python-net/es/aspose.cells/row/index) | Obtiene el índice de esta fila.|
| [group_level](/cells/python-net/es/aspose.cells/row/group_level) | Obtiene el nivel de grupo de la fila.|
| [is_height_matched](/cells/python-net/es/aspose.cells/row/is_height_matched) | Indica si la altura de la fila coincide con la configuración de fuente predeterminada actual del libro.<br/>Verdadero de esta propiedad también indica que la altura de la fila es "automática" sin un valor de altura personalizado establecido por el usuario.|
| [has_custom_style](/cells/python-net/es/aspose.cells/row/has_custom_style) | Indica si esta fila tiene configuraciones de estilo personalizadas (diferentes de la predeterminada heredada del libro de trabajo).|
| [first_cell](/cells/python-net/es/aspose.cells/row/first_cell) | Obtiene el primer objeto de celda de la fila.|
| [first_data_cell](/cells/python-net/es/aspose.cells/row/first_data_cell) | Obtiene la primera celda que no está en blanco de la fila.|
| [last_cell](/cells/python-net/es/aspose.cells/row/last_cell) | Obtiene el último objeto de celda de la fila.|
| [last_data_cell](/cells/python-net/es/aspose.cells/row/last_data_cell) | Obtiene la última celda de la fila que no está en blanco.|



Obtiene la celda.
###  indexador
| Nombre| Descripción|
| :- | :- |
| [index] | El índice de la columna|


###  Métodos
| Método| Descripción|
| :- | :- |
| [get_cell_by_index](/cells/python-net/es/aspose.cells/row/get_cell_by_index/#int) | Obtenga la celda por índice específico en la colección de celdas de esta fila.|
| [get_enumerator](/cells/python-net/es/aspose.cells/row/get_enumerator/#bool-bool) | Obtiene un enumerador que itera celdas a través de esta fila.|
| [get_cell_or_null](/cells/python-net/es/aspose.cells/row/get_cell_or_null/#int) | Obtiene la celda o nulo en el índice específico.|
| [get_style](/cells/python-net/es/aspose.cells/row/get_style/#) | Obtiene el estilo de esta fila.|
| [set_style](/cells/python-net/es/aspose.cells/row/set_style/#aspose.cells.Style) | Establece el estilo de esta fila.|
| [copy_settings](/cells/python-net/es/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | Copie la configuración de la fila, como estilo, altura, visibilidad, etc.|
| [apply_style](/cells/python-net/es/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Aplica formatos para una fila completa.|
| [equals](/cells/python-net/es/aspose.cells/row/equals/#aspose.cells.Row) | Comprueba si este objeto hace referencia a la misma fila con otro objeto de fila.|



###  Ejemplo

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
