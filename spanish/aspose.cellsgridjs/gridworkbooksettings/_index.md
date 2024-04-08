---
title: GridWorkbookSettings clase
second_title: Aspose.Cells.GridJs for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings clase

Representa la configuración del libro.



El tipo GridWorkbookSettings expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | Construye una nueva instancia de GridWorkbookSettings|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [max_iteration](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Devuelve o establece el número máximo de iteraciones para resolver una referencia circular; el valor predeterminado es 100.|
| [iteration](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/iteration) | Indica si se utiliza la iteración para resolver referencias circulares.|
| [force_full_calculate](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Indica si se calcula completamente cada vez que se activa un cálculo.|
| [create_calc_chain](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) | Indica si se crea una cadena de fórmulas calculadas. El valor predeterminado es falso.|
| [re_calculate_on_open](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Indica si se vuelven a calcular todas las fórmulas al abrir el archivo.|
| [precision_as_displayed](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | Verdadero si los cálculos de este libro se realizarán utilizando solo la precisión de los números tal como se muestran|
| [date1904](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/date1904) |Obtiene o establece un valor que representa si el libro utiliza el sistema de fechas 1904.|
| [enable_macros](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Habilitar macros; Ahora solo funciona al copiar una hoja de trabajo a otra hoja de trabajo en un libro.|
| [check_custom_number_format](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Indica si se comprueba el formato de número personalizado al configurar Style.Custom.|
| [author](/cells/python-net/es/aspose.cellsgridjs/gridworkbooksettings/author) | Obtiene/establece el autor del archivo.|



###  Ejemplo


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Ver también
* módulo [`aspose.cellsgridjs`](..)
