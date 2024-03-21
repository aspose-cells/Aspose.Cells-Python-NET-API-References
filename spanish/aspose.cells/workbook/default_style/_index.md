---
title: default_style propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 550
url: /es/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style propiedad

Obtiene o establece el objeto [`Style`](/cells/python-net/es/aspose.cells/style) predeterminado del libro.

###  Observaciones

La propiedad DefaultStyle es útil para implementar un estilo para todo el libro.

###  Ejemplo

El siguiente código crea y crea una instancia de un nuevo libro de trabajo y le establece un valor predeterminado [`Style`](/cells/python-net/es/aspose.cells/style).

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
