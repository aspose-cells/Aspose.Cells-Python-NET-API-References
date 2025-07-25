---
title: ExportTableOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 560
url: /es/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions clase
Representa todas las opciones de la tabla de exportación.



El tipo ExportTableOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/exporttableoptions/__init__/#) | Construye una nueva instancia de ExportTableOptions|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [export_column_name](/cells/python-net/es/aspose.cells/exporttableoptions/export_column_name) | Indica si los datos de la primera fila se exportan al nombre de columna de DataTable.<br/> El valor predeterminado es falso.|
| [skip_error_value](/cells/python-net/es/aspose.cells/exporttableoptions/skip_error_value) | Indica si se debe omitir un valor no válido para la columna.<br/> Por ejemplo, si el tipo de columna es decimal, el valor es mayor que decimal.MaxValue<br/>y esta propiedad es verdadera, no lanzaremos otra excepción nuevamente.<br/> El valor predeterminado es falso.|
| [plot_visible_cells](/cells/python-net/es/aspose.cells/exporttableoptions/plot_visible_cells) | Sólo exporta celdas visibles.|
| [plot_visible_rows](/cells/python-net/es/aspose.cells/exporttableoptions/plot_visible_rows) | Sólo exporta filas visibles.|
| [plot_visible_columns](/cells/python-net/es/aspose.cells/exporttableoptions/plot_visible_columns) | Sólo exporta columnas visibles.|
| [export_as_string](/cells/python-net/es/aspose.cells/exporttableoptions/export_as_string) | Exporta el valor de la cadena de las celdas a la DataTable.|
| [export_as_html_string](/cells/python-net/es/aspose.cells/exporttableoptions/export_as_html_string) | Exporta el valor de la cadena HTML de las celdas a DataTable.|
| [format_strategy](/cells/python-net/es/aspose.cells/exporttableoptions/format_strategy) | Obtiene y establece la estrategia de formato al exportar el valor como valor de cadena.|
| [check_mixed_value_type](/cells/python-net/es/aspose.cells/exporttableoptions/check_mixed_value_type) | Falso, Aspose.Cells establecerá el tipo de DataColumn por el tipo de valor de la primera fila para el rendimiento.<br/> Es cierto que Aspose.Cells comprobará si los tipos de valores en la columna son mixtos antes de establecer el tipo de DataColumn.<br/> Y los tipos de valores son mixtos, el tipo de DataColumn será cadena.|
| [allow_db_null](/cells/python-net/es/aspose.cells/exporttableoptions/allow_db_null) |Este valor indica si se permiten DBNulls en esta tabla.|
| [is_vertical](/cells/python-net/es/aspose.cells/exporttableoptions/is_vertical) | Verdadero si una fila del libro de trabajo representa una fila de la tabla de datos. Falso si una columna del libro de trabajo representa una fila de la tabla de datos.|
| [indexes](/cells/python-net/es/aspose.cells/exporttableoptions/indexes) | Los índices de columnas/filas que deben exportarse.|
| [rename_strategy](/cells/python-net/es/aspose.cells/exporttableoptions/rename_strategy) | Estrategia para nombres duplicados de columnas.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/es/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) | Preprocesar el valor de la celda actual que se va a exportar.|



###  Observaciones

Si hay algunos requisitos especiales sobre la exportación, como ignorar valores de error, el usuario puede ampliar esta clase
sobrescribir las API correspondientes para lograr el objetivo.

###  Ver también
* módulo [`aspose.cells`](..)
