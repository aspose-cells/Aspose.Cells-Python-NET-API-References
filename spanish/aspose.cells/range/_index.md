---
title: Range clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1290
url: /es/aspose.cells/range/
is_root: false
---
##  Range clase
Encapsula el objeto que representa un rango de celdas dentro de una hoja de cálculo.



El tipo Range expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [current_region](/cells/python-net/es/aspose.cells/range/current_region) |Devuelve un objeto Range que representa la región actual.<br/> La región actual es un rango delimitado por cualquier combinación de filas y columnas en blanco.|
| [hyperlinks](/cells/python-net/es/aspose.cells/range/hyperlinks) | Obtiene todos los hipervínculos del rango.|
| [row_count](/cells/python-net/es/aspose.cells/range/row_count) | Obtiene el recuento de filas del rango.|
| [column_count](/cells/python-net/es/aspose.cells/range/column_count) | Obtiene el recuento de columnas del rango.|
| [name](/cells/python-net/es/aspose.cells/range/name) | Obtiene o establece el nombre del rango.|
| [refers_to](/cells/python-net/es/aspose.cells/range/refers_to) | Obtiene el rango al que se refiere.|
| [address](/cells/python-net/es/aspose.cells/range/address) | Obtiene la dirección del rango.|
| [left](/cells/python-net/es/aspose.cells/range/left) | Obtiene la distancia, en puntos, desde el borde izquierdo de la columna A hasta el borde izquierdo del rango.|
| [top](/cells/python-net/es/aspose.cells/range/top) | Obtiene la distancia, en puntos, desde el borde superior de la fila 1 hasta el borde superior del rango.|
| [width](/cells/python-net/es/aspose.cells/range/width) | Obtiene el ancho de un rango en puntos.|
| [height](/cells/python-net/es/aspose.cells/range/height) | Obtiene el ancho de un rango en puntos.|
| [first_row](/cells/python-net/es/aspose.cells/range/first_row) | Obtiene el índice de la primera fila del rango.|
| [first_column](/cells/python-net/es/aspose.cells/range/first_column) | Obtiene el índice de la primera columna del rango.|
| [value](/cells/python-net/es/aspose.cells/range/value) | Obtiene y establece el valor del rango.|
| [column_width](/cells/python-net/es/aspose.cells/range/column_width) | Establece u obtiene el ancho de columna de este rango|
| [row_height](/cells/python-net/es/aspose.cells/range/row_height) | Establece u obtiene la altura de las filas en este rango|
| [entire_column](/cells/python-net/es/aspose.cells/range/entire_column) | Obtiene un objeto Range que representa la columna (o columnas) completa que contiene el rango especificado.|
| [entire_row](/cells/python-net/es/aspose.cells/range/entire_row) |Obtiene un objeto Range que representa la fila (o filas) completa que contiene el rango especificado.|
| [worksheet](/cells/python-net/es/aspose.cells/range/worksheet) | Obtiene el objeto [`Range.worksheet`](/cells/python-net/es/aspose.cells/range#worksheet) que contiene este rango.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [auto_fill](/cells/python-net/es/aspose.cells/range/auto_fill/#aspose.cells.Range) | Completa automáticamente el rango objetivo.|
| [auto_fill](/cells/python-net/es/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Completa automáticamente el rango objetivo.|
| [set_style](/cells/python-net/es/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Aplicar el estilo de celda.|
| [set_style](/cells/python-net/es/aspose.cells/range/set_style/#aspose.cells.Style) | Establece el estilo del rango.|
| [set_outline_borders](/cells/python-net/es/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Establece los bordes del contorno alrededor de un rango de celdas con el mismo estilo y color de borde.|
| [set_outline_borders](/cells/python-net/es/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Establece los bordes del contorno alrededor de un rango de celdas con el mismo estilo y color de borde.|
| [set_outline_borders](/cells/python-net/es/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Establece límites de línea alrededor de un rango de celdas.|
| [set_outline_border](/cells/python-net/es/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Establece el borde del contorno alrededor de un rango de celdas.|
| [set_outline_border](/cells/python-net/es/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Establece el borde del contorno alrededor de un rango de celdas.|
| [copy](/cells/python-net/es/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Copiando el rango con opciones especiales de pegado.|
| [copy](/cells/python-net/es/aspose.cells/range/copy/#aspose.cells.Range) | Copia datos (incluidas fórmulas), formateo, objetos de dibujo, etc. desde un rango de origen.|
| [add_hyperlink](/cells/python-net/es/aspose.cells/range/add_hyperlink/#str-str-str) | Agrega un hipervínculo a una celda específica o a un rango de celdas.|
| [get_enumerator](/cells/python-net/es/aspose.cells/range/get_enumerator/#) | Obtiene el enumerador de las celdas de este rango.|
| [is_intersect](/cells/python-net/es/aspose.cells/range/is_intersect/#aspose.cells.Range) | Indica si el rango se cruza.|
| [intersect](/cells/python-net/es/aspose.cells/range/intersect/#aspose.cells.Range) | Devuelve un objeto [`Range`](/cells/python-net/es/aspose.cells/range) que representa la intersección rectangular de dos rangos.|
| [union_rang](/cells/python-net/es/aspose.cells/range/union_rang/#aspose.cells.Range) | Devuelve el resultado de la unión de dos rangos.|
| [union](/cells/python-net/es/aspose.cells/range/union/#aspose.cells.Range) | Devuelve la unión de dos rangos.|
| [is_blank](/cells/python-net/es/aspose.cells/range/is_blank/#) | Indica si el rango contiene valores.|
| [merge](/cells/python-net/es/aspose.cells/range/merge/#) | Combina una variedad de celdas en una sola celda.|
| [un_merge](/cells/python-net/es/aspose.cells/range/un_merge/#) |Desintegra las celdas fusionadas de este rango.|
| [put_value](/cells/python-net/es/aspose.cells/range/put_value/#str-bool-bool) | Coloca un valor en el rango; si corresponde, el valor se convertirá a otro tipo de datos y se restablecerá el formato del número de celda.|
| [apply_style](/cells/python-net/es/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Aplica formatos para toda una gama.|
| [set_inside_borders](/cells/python-net/es/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Establecer dentro de los límites del rango.|
| [move_to](/cells/python-net/es/aspose.cells/range/move_to/#int-int) | Mueve el rango actual al rango de destino.|
| [copy_data](/cells/python-net/es/aspose.cells/range/copy_data/#aspose.cells.Range) | Copia datos de celda (incluidas fórmulas) de un rango de origen.|
| [copy_value](/cells/python-net/es/aspose.cells/range/copy_value/#aspose.cells.Range) | Copia el valor de la celda de un rango de origen.|
| [copy_style](/cells/python-net/es/aspose.cells/range/copy_style/#aspose.cells.Range) | Copia la configuración de estilo de un rango de origen.|
| [get_cell_or_null](/cells/python-net/es/aspose.cells/range/get_cell_or_null/#int-int) | Obtiene [`Cell`](/cells/python-net/es/aspose.cells/cell) objeto o nulo en este rango.|
| [get_offset](/cells/python-net/es/aspose.cells/range/get_offset/#int-int) | Obtiene el rango [`Range`](/cells/python-net/es/aspose.cells/range) por desplazamiento.|



###  Observaciones

La clase Range denota una región de la hoja de cálculo de Excel.
Con esto, puede formatear y establecer el valor del rango.
Y también puedes simplemente copiar el rango de Excel.

###  Ejemplo

El siguiente ejemplo muestra cómo crear un rango y establecer el valor del rango de Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
