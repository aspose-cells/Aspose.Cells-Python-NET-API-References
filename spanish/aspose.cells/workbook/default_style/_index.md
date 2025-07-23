---
title: default_style propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 580
url: /es/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style propiedad

Obtiene o establece el objeto [`Style`](/cells/python-net/es/aspose.cells/style) predeterminado del libro de trabajo.

###  Observaciones

La propiedad DefaultStyle es útil para implementar un estilo para todo el libro de trabajo.

###  Ejemplo

El siguiente código crea e instancia un nuevo libro de trabajo y le establece un valor predeterminado de [`Style`](/cells/python-net/es/aspose.cells/style).

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
###  Definición:
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Style`](/cells/python-net/es/aspose.cells/style)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
