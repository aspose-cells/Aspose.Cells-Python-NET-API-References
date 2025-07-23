---
title: number_category_type propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 700
url: /es/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type propiedad

Representa el tipo de categoría del formato de número de esta celda.

###  Observaciones

Cuando el patrón de formato de celda se combina con patrones de formato condicional,
Entonces, el tipo devuelto corresponde a la parte que se utiliza para el valor actual de esta celda.
Por ejemplo, si el patrón de formato para esta celda es "#,##0;(#,##0);"-";@",
entonces, cuando el valor de la celda es numérico y no 0, el tipo devuelto es [`NumberCategoryType.NUMBER`](/cells/python-net/es/aspose.cells/numbercategorytype#NUMBER);
Cuando el valor de la celda es 0 o no es un valor numérico, el tipo devuelto es [`NumberCategoryType.TEXT`](/cells/python-net/es/aspose.cells/numbercategorytype#TEXT).
###  Definición:
```python
@property
def number_category_type(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
* clase [`NumberCategoryType`](/cells/python-net/es/aspose.cells/numbercategorytype)
