---
title: PivotFilter clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells.pivot/pivotfilter/
is_root: false
---
##  PivotFilter clase
Representa un PivotFilter en la colección PivotFilter.



El tipo PivotFilter expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [use_whole_day](/cells/python-net/es/aspose.cells.pivot/pivotfilter/use_whole_day) | Indica si utiliza días completos en sus criterios de filtrado.|
| [auto_filter](/cells/python-net/es/aspose.cells.pivot/pivotfilter/auto_filter) | Obtiene el filtro automático del filtro pivote.|
| [filter_type](/cells/python-net/es/aspose.cells.pivot/pivotfilter/filter_type) | Obtiene el tipo de filtro automático del filtro pivote.|
| [field_index](/cells/python-net/es/aspose.cells.pivot/pivotfilter/field_index) | Obtiene el índice del campo de origen al que se aplica este filtro pivote.|
| [filter_category](/cells/python-net/es/aspose.cells.pivot/pivotfilter/filter_category) | Obtiene la categoría de este filtro.|
| [value1](/cells/python-net/es/aspose.cells.pivot/pivotfilter/value1) | Obtiene el valor de la cadena1 del filtro pivote de etiqueta.|
| [value2](/cells/python-net/es/aspose.cells.pivot/pivotfilter/value2) | Obtiene el valor de la cadena2 del filtro pivote de etiqueta.|
| [measure_fld_index](/cells/python-net/es/aspose.cells.pivot/pivotfilter/measure_fld_index) | Obtiene el índice del campo de medida del filtro pivote.|
| [value_field_index](/cells/python-net/es/aspose.cells.pivot/pivotfilter/value_field_index) | Obtiene el índice del campo de valor en la región de valor.|
| [measure_cube_field_index](/cells/python-net/es/aspose.cells.pivot/pivotfilter/measure_cube_field_index) | Especifica el índice del campo del cubo de medida.<br/>Esta propiedad solo la utilizan los filtros en los pivotes OLAP y especifica en qué medida se debe aplicar un filtro de valor.|
| [member_property_field_index](/cells/python-net/es/aspose.cells.pivot/pivotfilter/member_property_field_index) | Obtiene el índice del campo de propiedad miembro del filtro pivote.|
| [name](/cells/python-net/es/aspose.cells.pivot/pivotfilter/name) | Obtiene el nombre del filtro pivote.|
| [evaluation_order](/cells/python-net/es/aspose.cells.pivot/pivotfilter/evaluation_order) | Obtiene el orden de evaluación del filtro pivote.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_top_10_value(self)`](/cells/python-net/es/aspose.cells.pivot/pivotfilter/get_top_10_value/#) | Obtiene la configuración top 10 del filtro.|
| [`get_labels(self)`](/cells/python-net/es/aspose.cells.pivot/pivotfilter/get_labels/#) | Obtiene las etiquetas del filtro de subtítulos.|
| [`get_number_values(self)`](/cells/python-net/es/aspose.cells.pivot/pivotfilter/get_number_values/#) | Obtiene valores del filtro numérico.|
| [`get_date_time_values(self)`](/cells/python-net/es/aspose.cells.pivot/pivotfilter/get_date_time_values/#) | Obtiene valores del filtro numérico.|



###  Ejemplo

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

###  Ver también
* módulo [`aspose.cells.pivot`](..)
