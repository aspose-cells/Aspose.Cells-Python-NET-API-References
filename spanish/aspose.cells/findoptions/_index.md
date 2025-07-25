---
title: FindOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 640
url: /es/aspose.cells/findoptions/
is_root: false
---
##  FindOptions clase
Representa opciones de búsqueda.



El tipo FindOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/findoptions/__init__/#) | Construye una nueva instancia de FindOptions|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_case_sensitive](/cells/python-net/es/aspose.cells/findoptions/is_case_sensitive) | Indica si la cadena buscada distingue entre mayúsculas y minúsculas.|
| [case_sensitive](/cells/python-net/es/aspose.cells/findoptions/case_sensitive) | Indica si la cadena buscada distingue entre mayúsculas y minúsculas.|
| [look_at_type](/cells/python-net/es/aspose.cells/findoptions/look_at_type) | Mira el tipo.|
| [is_range_set](/cells/python-net/es/aspose.cells/findoptions/is_range_set) | Indica si el rango buscado está establecido.|
| [search_next](/cells/python-net/es/aspose.cells/findoptions/search_next) |Orden de búsqueda. Verdadero: buscar siguiente. Falso: buscar anterior.|
| [search_backward](/cells/python-net/es/aspose.cells/findoptions/search_backward) | Si busca celdas hacia atrás.|
| [seach_order_by_rows](/cells/python-net/es/aspose.cells/findoptions/seach_order_by_rows) | Indica si el orden de búsqueda es por filas o columnas.|
| [search_order_by_rows](/cells/python-net/es/aspose.cells/findoptions/search_order_by_rows) | Indica si el orden de búsqueda es por filas o columnas.|
| [look_in_type](/cells/python-net/es/aspose.cells/findoptions/look_in_type) | Mirar en tipo.|
| [regex_key](/cells/python-net/es/aspose.cells/findoptions/regex_key) | Indica si la clave buscada es una expresión regular.<br/>Si es verdadero, la clave buscada se tomará como expresión regular y se analizará.<br/> De lo contrario, la clave se analizará de acuerdo con las reglas de MS Excel.|
| [value_type_sensitive](/cells/python-net/es/aspose.cells/findoptions/value_type_sensitive) | Indica si el tipo de valor de la celda buscada debe ser el mismo que la clave buscada.|
| [style](/cells/python-net/es/aspose.cells/findoptions/style) | El formato a buscar.|
| [convert_numeric_data](/cells/python-net/es/aspose.cells/findoptions/convert_numeric_data) | Obtiene o establece un valor que indica si se convertirá el valor de la cadena buscada en datos numéricos.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_range(self)`](/cells/python-net/es/aspose.cells/findoptions/get_range/#) | Obtiene y establece el rango buscado.|
| [`set_range(self, ca)`](/cells/python-net/es/aspose.cells/findoptions/set_range/#aspose.cells.cellarea) | Establece el rango buscado.|



###  Ejemplo

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  Ver también
* módulo [`aspose.cells`](..)
