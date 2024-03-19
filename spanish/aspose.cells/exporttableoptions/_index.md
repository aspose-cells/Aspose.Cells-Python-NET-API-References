---
title: ExportTableOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 580
url: /es/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions clase
Representa todas las opciones de la tabla de exportación.



El tipo ExportTableOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/exporttableoptions/__init__/#) | Construye una nueva instancia de ExportTableOptions|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [export_column_name](/cells/python-net/es/aspose.cells/exporttableoptions/export_column_name) | Indica si los datos de la primera fila se exportan al nombre de la columna de DataTable.<br/> El valor predeterminado es falso.|
| [skip_error_value](/cells/python-net/es/aspose.cells/exporttableoptions/skip_error_value) | Indica si se omite un valor no válido para la columna.<br/> Por ejemplo, si el tipo de columna es decimal, el valor es mayor que decimal.MaxValue<br/>y esta propiedad es verdadera, no volveremos a lanzar una excepción.<br/> El valor predeterminado es falso.|
| [plot_visible_cells](/cells/python-net/es/aspose.cells/exporttableoptions/plot_visible_cells) | Solo exporta celdas visibles.|
| [plot_visible_rows](/cells/python-net/es/aspose.cells/exporttableoptions/plot_visible_rows) | Solo exporta filas visibles.|
| [plot_visible_columns](/cells/python-net/es/aspose.cells/exporttableoptions/plot_visible_columns) | Solo exporta columnas visibles.|
| [export_as_string](/cells/python-net/es/aspose.cells/exporttableoptions/export_as_string) | Exporta el valor de cadena de las celdas al DataTable.|
| [export_as_html_string](/cells/python-net/es/aspose.cells/exporttableoptions/export_as_html_string) | Exporta el valor de cadena html de las celdas a DataTable.|
| [format_strategy](/cells/python-net/es/aspose.cells/exporttableoptions/format_strategy) | Obtiene y establece la estrategia de formato al exportar el valor como valor de cadena.|
| [check_mixed_value_type](/cells/python-net/es/aspose.cells/exporttableoptions/check_mixed_value_type) | Falso, Aspose.Cells establecerá el tipo de DataColumn según el tipo de valor de la primera fila para mejorar el rendimiento.<br/> Es cierto, Aspose.Cells verificará si el tipo de valor en la columna está mezclado antes de establecer el tipo de DataColumn<br/> el tipo de valor es mixto, el tipo de DataColumn será una cadena.|
| [allow_db_null](/cells/python-net/es/aspose.cells/exporttableoptions/allow_db_null) | Este valor indica si se permiten DBNulls en esta tabla.|
| [is_vertical](/cells/python-net/es/aspose.cells/exporttableoptions/is_vertical) | Verdadero si una fila del archivo de libro de trabajo representa una fila de DataTable. Falso si una columna en el archivo del Libro de trabajo representa una fila en la Tabla de datos.|
| [indexes](/cells/python-net/es/aspose.cells/exporttableoptions/indexes) | Los índices de columnas/filas que deben exportarse.|
| [rename_strategy](/cells/python-net/es/aspose.cells/exporttableoptions/rename_strategy) | Estrategia para nombres duplicados de columnas.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/es/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) | Preprocese el valor de la celda actual que se va a exportar.|



###  Observaciones

Si existen algunos requisitos especiales sobre la exportación, como ignorar valores de error, el usuario puede ampliar esta clase
para sobrescribir las API correspondientes para lograr el objetivo.

###  Ver también
* módulo [`aspose.cells`](..)
