---
title: WorkbookDesigner clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1580
url: /es/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner clase
Encapsula el objeto que representa una hoja de cálculo de diseñador.



El tipo WorkbookDesigner expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/workbookdesigner/__init__/#) | Inicializa una nueva instancia de la clase [`WorkbookDesigner`](/cells/python-net/es/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/es/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | Inicializa una nueva instancia de la clase [`WorkbookDesigner`](/cells/python-net/es/aspose.cells/workbookdesigner).|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [workbook](/cells/python-net/es/aspose.cells/workbookdesigner/workbook) | Obtiene y establece el objeto [`WorkbookDesigner.workbook`](/cells/python-net/es/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/es/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Indica si se repiten fórmulas con fila de subtotal.|
| [update_empty_string_as_null](/cells/python-net/es/aspose.cells/workbookdesigner/update_empty_string_as_null) |Si es VERDADERO, se insertará Null si el valor es "";|
| [update_reference](/cells/python-net/es/aspose.cells/workbookdesigner/update_reference) | Indica si se actualizarán las referencias en otras hojas de trabajo.|
| [calculate_formula](/cells/python-net/es/aspose.cells/workbookdesigner/calculate_formula) | Indica si se deben calcular fórmulas.|
| [line_by_line](/cells/python-net/es/aspose.cells/workbookdesigner/line_by_line) | Indica si se procesa el marcador inteligente línea por línea.|
| [contains_variables](/cells/python-net/es/aspose.cells/workbookdesigner/contains_variables) | Indica si la primera hoja de trabajo contiene variables personalizadas.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/es/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/es/aspose.cells/workbookdesigner/set_data_source/#str-any) | Establece el enlace de datos a una variable.|
| [`process(self, range, is_preserved)`](/cells/python-net/es/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | Procesa los marcadores inteligentes y completa los valores de la fuente de datos.|
| [`process(self)`](/cells/python-net/es/aspose.cells/workbookdesigner/process/#) | Procesa los marcadores inteligentes y completa los valores de la fuente de datos.|
| [`process(self, is_preserved)`](/cells/python-net/es/aspose.cells/workbookdesigner/process/#bool) | Procesa los marcadores inteligentes y completa los valores de la fuente de datos.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/es/aspose.cells/workbookdesigner/process/#int-bool) | Procesa los marcadores inteligentes y completa los valores de la fuente de datos.|
| [`clear_data_source(self)`](/cells/python-net/es/aspose.cells/workbookdesigner/clear_data_source/#) | Borra todas las fuentes de datos.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/es/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/es/aspose.cells/workbookdesigner/get_smart_markers/#) | Devuelve una colección de marcadores inteligentes en una hoja de cálculo.|



###  Ejemplo

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`WorkbookDesigner`](/cells/python-net/es/aspose.cells/workbookdesigner)
