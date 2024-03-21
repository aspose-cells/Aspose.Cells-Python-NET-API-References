---
title: método get_enumerator
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
Obtiene el enumerador de las celdas de este rango.


###  Devoluciones

El enumerador de células.


```python
def get_enumerator(self):
    ...
```


###  Observaciones

Al atravesar elementos por el enumerador devuelto, la colección de celdas
no debe modificarse (como operaciones que causarán que se cree una instancia del nuevo Cell/Row o que se elimine el Cell/Row existente).
De lo contrario, es posible que el enumerador no pueda recorrer todas las celdas correctamente (algunos elementos pueden atravesarse repetidamente u omitirse).
###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
