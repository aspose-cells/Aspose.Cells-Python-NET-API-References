---
title: ScrollBarActiveXControl clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl clase
Representa el control ScrollBar.



**Herencia:** [ScrollBarActiveXControl](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[SpinButtonActiveXControl](/cells/python-net/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol) → 
[ActiveXControl](/cells/python-net/aspose.cells.drawing.activexcontrols/activexcontrol) → 
[ActiveXControlBase](/cells/python-net/es/aspose.cells.drawing.activexcontrols/activexcontrolbase)



El tipo ScrollBarActiveXControl expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [workbook](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) | Obtiene el objeto [ActiveXControlBase.workbook](/cells/python-net/es/aspose.cells.drawing.activexcontrols/activexcontrolbase#workbook).|
| [type](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Obtiene el tipo del control ActiveX.|
| [width](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |Obtiene y establece el ancho del control en unidades de puntos.|
| [height](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) | Obtiene y establece el alto del control en unidades de puntos.|
| [mouse_icon](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) | Obtiene y establece un icono personalizado para mostrar como el puntero del mouse para el control.|
| [mouse_pointer](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) | Obtiene y establece el tipo de icono que se muestra como el puntero del mouse para el control.|
| [fore_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) | Obtiene y establece el color antiguo del primer plano.|
| [back_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) | Obtiene y establece el color antiguo del fondo.|
| [is_visible](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) | Indica si este control es visible.|
| [shadow](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) | Indica si mostrar una sombra.|
| [linked_cell](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) | Obtiene y establece la celda vinculada.|
| [list_fill_range](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) | Obtiene y establece el rango de relleno de la lista.|
| [data](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) | Obtiene y establece los datos binarios del control.|
| [is_enabled](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) | Indica si el control puede recibir el foco y responder a los eventos generados por el usuario.|
| [is_locked](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) | Indica si los datos del control están bloqueados para su edición.|
| [is_transparent](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) | Indica si el control es transparente.|
| [is_auto_size](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) | Indica si el control cambiará de tamaño automáticamente para mostrar todo su contenido.|
| [ime_mode](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |Obtiene y establece el modo de tiempo de ejecución predeterminado del Editor de métodos de entrada para el control cuando recibe el foco.|
| [font](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) | Representa la fuente del control.|
| [text_align](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) | Representa cómo alinear el texto utilizado por el control.|
| [min](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Obtiene y establece el valor mínimo aceptable.|
| [max](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Obtiene y establece el valor máximo aceptable.|
| [position](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Obtiene y establece el valor.|
| [small_change](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Obtiene y establece la cantidad por la que cambia la propiedad Position|
| [orientation](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Obtiene y establece si SpinButton o ScrollBar están orientados vertical u horizontalmente.|
| [large_change](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Obtiene y establece la cantidad por la que cambia la propiedad Position|



###  Ejemplo

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, ScrollBarActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.SCROLL_BAR, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(ScrollBarActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

###  Ver también
* módulo [aspose.cells.drawing.activexcontrols](..)
* clase [ActiveXControl](/cells/python-net/es/aspose.cells.drawing.activexcontrols/activexcontrol)
* clase [ActiveXControlBase](/cells/python-net/es/aspose.cells.drawing.activexcontrols/activexcontrolbase)
* clase [ScrollBarActiveXControl](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* clase [SpinButtonActiveXControl](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
