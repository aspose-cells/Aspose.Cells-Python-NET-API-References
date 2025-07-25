---
title: Slicer clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.slicers/slicer/
is_root: false
---
##  Slicer clase
Descripción resumida de Slicer Ver



El tipo Slicer expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [title](/cells/python-net/es/aspose.cells.slicers/slicer/title) | Especifica el título del objeto Slicer actual.|
| [alternative_text](/cells/python-net/es/aspose.cells.slicers/slicer/alternative_text) | Devuelve o establece la cadena de texto descriptiva (alternativa) del objeto Slicer.|
| [is_printable](/cells/python-net/es/aspose.cells.slicers/slicer/is_printable) | Indica si el objeto segmentador es imprimible.|
| [is_locked](/cells/python-net/es/aspose.cells.slicers/slicer/is_locked) | Indica si la forma de la segmentación está bloqueada.|
| [placement](/cells/python-net/es/aspose.cells.slicers/slicer/placement) | Representa la forma en que el objeto de dibujo se adjunta a las celdas debajo de él.<br/> La propiedad controla la ubicación de un objeto en una hoja de cálculo.|
| [locked_aspect_ratio](/cells/python-net/es/aspose.cells.slicers/slicer/locked_aspect_ratio) | Indica si se bloquea la relación de aspecto.|
| [locked_position](/cells/python-net/es/aspose.cells.slicers/slicer/locked_position) |Indica si la segmentación de datos especificada se puede mover o cambiar de tamaño mediante la interfaz de usuario.|
| [shape](/cells/python-net/es/aspose.cells.slicers/slicer/shape) | Devuelve el objeto Shape asociado a la segmentación de datos especificada. Solo lectura.|
| [slicer_cache](/cells/python-net/es/aspose.cells.slicers/slicer/slicer_cache) | Devuelve el objeto SlicerCache asociado a la segmentación de datos. Solo lectura.|
| [parent](/cells/python-net/es/aspose.cells.slicers/slicer/parent) | Devuelve el objeto [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet) que contiene esta segmentación. Solo lectura.|
| [style_type](/cells/python-net/es/aspose.cells.slicers/slicer/style_type) | Especifique el tipo de estilo de segmentación de datos integrado<br/> El tipo predeterminado es SlicerStyleLight1|
| [name](/cells/python-net/es/aspose.cells.slicers/slicer/name) | Devuelve o establece el nombre de la segmentación de datos especificada|
| [caption](/cells/python-net/es/aspose.cells.slicers/slicer/caption) | Devuelve o establece el título de la segmentación de datos especificada.|
| [caption_visible](/cells/python-net/es/aspose.cells.slicers/slicer/caption_visible) | Devuelve o establece si el encabezado que muestra el título de la segmentación de datos es visible<br/> El valor predeterminado es verdadero|
| [number_of_columns](/cells/python-net/es/aspose.cells.slicers/slicer/number_of_columns) | Devuelve o establece el número de columnas en la segmentación de datos especificada.|
| [left_pixel](/cells/python-net/es/aspose.cells.slicers/slicer/left_pixel) | Devuelve o establece el desplazamiento horizontal de la forma de la segmentación de datos desde su columna izquierda, en píxeles.|
| [top_pixel](/cells/python-net/es/aspose.cells.slicers/slicer/top_pixel) | Devuelve o establece el desplazamiento vertical de la forma de la segmentación de datos desde su fila superior, en píxeles.|
| [width](/cells/python-net/es/aspose.cells.slicers/slicer/width) | Devuelve o establece el ancho de la segmentación de datos especificada, en puntos.|
| [width_pixel](/cells/python-net/es/aspose.cells.slicers/slicer/width_pixel) |Devuelve o establece el ancho de la segmentación de datos especificada, en píxeles.|
| [height](/cells/python-net/es/aspose.cells.slicers/slicer/height) | Devuelve o establece la altura de la segmentación de datos especificada, en puntos.|
| [height_pixel](/cells/python-net/es/aspose.cells.slicers/slicer/height_pixel) | Devuelve o establece la altura de la segmentación de datos especificada, en píxeles.|
| [column_width_pixel](/cells/python-net/es/aspose.cells.slicers/slicer/column_width_pixel) | Obtiene o establece el ancho de cada columna en la segmentación de datos, en unidades de píxeles.|
| [column_width](/cells/python-net/es/aspose.cells.slicers/slicer/column_width) | Devuelve o establece el ancho, en puntos, de cada columna en la segmentación de datos.|
| [row_height_pixel](/cells/python-net/es/aspose.cells.slicers/slicer/row_height_pixel) | Devuelve o establece la altura, en píxeles, de cada fila en la segmentación de datos especificada.|
| [row_height](/cells/python-net/es/aspose.cells.slicers/slicer/row_height) | Devuelve o establece la altura, en puntos, de cada fila en la segmentación de datos especificada.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add_pivot_connection(self, pivot)`](/cells/python-net/es/aspose.cells.slicers/slicer/add_pivot_connection/#aspose.cells.pivot.pivottable) | Agrega conexión de tabla dinámica.|
| [`remove_pivot_connection(self, pivot)`](/cells/python-net/es/aspose.cells.slicers/slicer/remove_pivot_connection/#aspose.cells.pivot.pivottable) | Elimina la conexión de la tabla dinámica.|
| [`refresh(self)`](/cells/python-net/es/aspose.cells.slicers/slicer/refresh/#) | Actualizando la segmentación de datos. Mientras tanto, actualizando y calculando tablas dinámicas relativas.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

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
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
items = slicer.slicer_cache.slicer_cache_items
item = items[0]
item.selected = False
# do your business
book.save("out.xlsx")

```

###  Ver también
* módulo [`aspose.cells.slicers`](..)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
