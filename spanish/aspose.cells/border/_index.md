---
title: Border clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/border/
is_root: false
---
##  Border clase
Encapsula el objeto que representa el borde de la celda.



El tipo Border expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [theme_color](/cells/python-net/es/aspose.cells/border/theme_color) | Obtiene y establece el color del tema del borde.|
| [color](/cells/python-net/es/aspose.cells/border/color) | Obtiene o establece el color del borde.|
| [argb_color](/cells/python-net/es/aspose.cells/border/argb_color) | Obtiene y establece el color con un valor ARGB de 32 bits.|
| [line_style](/cells/python-net/es/aspose.cells/border/line_style) | Obtiene o establece el tipo de borde de celda.|



###  Ejemplo

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
# Set top border style and color
border = style.borders.get(BorderType.TOP_BORDER)
border.line_style = CellBorderType.MEDIUM
border.color = Color.red
cell.set_style(style)

```

###  Ver también
* módulo [`aspose.cells`](..)
