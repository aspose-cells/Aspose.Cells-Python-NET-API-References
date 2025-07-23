---
title: ListObject clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject clase
Representa un objeto de lista en una hoja de cálculo.
 El objeto ListObject es un miembro de la colección ListObjects.
La colección ListObjects contiene todos los objetos de lista en una hoja de cálculo.



El tipo ListObject expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [start_row](/cells/python-net/es/aspose.cells.tables/listobject/start_row) | Obtiene la fila de inicio del rango.|
| [start_column](/cells/python-net/es/aspose.cells.tables/listobject/start_column) | Obtiene la columna de inicio del rango.|
| [end_row](/cells/python-net/es/aspose.cells.tables/listobject/end_row) | Obtiene la fila final del rango.|
| [end_column](/cells/python-net/es/aspose.cells.tables/listobject/end_column) | Obtiene la columna final del rango.|
| [list_columns](/cells/python-net/es/aspose.cells.tables/listobject/list_columns) | Obtiene ListColumns del ListObject.|
| [show_header_row](/cells/python-net/es/aspose.cells.tables/listobject/show_header_row) | Obtiene y establece si este ListObject muestra la fila de encabezado.|
| [show_totals](/cells/python-net/es/aspose.cells.tables/listobject/show_totals) | Obtiene y establece si este ListObject muestra el total de filas.|
| [data_range](/cells/python-net/es/aspose.cells.tables/listobject/data_range) | Obtiene el rango de datos de ListObject.|
| [query_table](/cells/python-net/es/aspose.cells.tables/listobject/query_table) | Obtiene la QueryTable vinculada.|
| [data_source_type](/cells/python-net/es/aspose.cells.tables/listobject/data_source_type) |Obtiene el tipo de fuente de datos de la tabla.|
| [auto_filter](/cells/python-net/es/aspose.cells.tables/listobject/auto_filter) | Obtiene filtro automático.|
| [display_name](/cells/python-net/es/aspose.cells.tables/listobject/display_name) | Obtiene y establece el nombre para mostrar.|
| [comment](/cells/python-net/es/aspose.cells.tables/listobject/comment) | Obtiene y establece el comentario de la tabla.|
| [show_table_style_first_column](/cells/python-net/es/aspose.cells.tables/listobject/show_table_style_first_column) | Indica si se debe aplicar el estilo a la primera columna de la tabla.|
| [show_table_style_last_column](/cells/python-net/es/aspose.cells.tables/listobject/show_table_style_last_column) | Indica si se debe aplicar el estilo a la última columna de la tabla.|
| [show_table_style_row_stripes](/cells/python-net/es/aspose.cells.tables/listobject/show_table_style_row_stripes) | Indica si se aplica el formato de franja de fila.|
| [show_table_style_column_stripes](/cells/python-net/es/aspose.cells.tables/listobject/show_table_style_column_stripes) | Indica si se aplica el formato de franja de columna.|
| [table_style_type](/cells/python-net/es/aspose.cells.tables/listobject/table_style_type) | Obtiene el estilo de tabla incorporado.|
| [table_style_name](/cells/python-net/es/aspose.cells.tables/listobject/table_style_name) | Obtiene y establece el nombre del estilo de tabla.|
| [xml_map](/cells/python-net/es/aspose.cells.tables/listobject/xml_map) | Obtiene un [`ListObject.xml_map`](/cells/python-net/es/aspose.cells.tables/listobject#xml_map) utilizado para esta lista.|
| [alternative_text](/cells/python-net/es/aspose.cells.tables/listobject/alternative_text) | Obtiene y establece el texto alternativo.|
| [alternative_description](/cells/python-net/es/aspose.cells.tables/listobject/alternative_description) | Obtiene y establece la descripción alternativa.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/es/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Pon el valor en la celda.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/es/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Pon el valor en la celda.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/es/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Coloque la fórmula en la celda de la tabla.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/es/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Coloque la fórmula en la celda de la tabla.|
| [`convert_to_range(self)`](/cells/python-net/es/aspose.cells.tables/listobject/convert_to_range/#) | Convertir la tabla en rango.|
| [`convert_to_range(self, options)`](/cells/python-net/es/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Convertir la tabla en rango.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/es/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Cambiar el tamaño del rango del objeto de lista.|
| [`update_column_name(self)`](/cells/python-net/es/aspose.cells.tables/listobject/update_column_name/#) | Actualiza el nombre de todas las columnas de la lista de la hoja de cálculo.|
| [`filter(self)`](/cells/python-net/es/aspose.cells.tables/listobject/filter/#) | Filtrar la tabla.|
| [`apply_style_to_range(self)`](/cells/python-net/es/aspose.cells.tables/listobject/apply_style_to_range/#) | Aplicar el estilo de tabla al rango.|



###  Ejemplo

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Ver también
* módulo [`aspose.cells.tables`](..)
