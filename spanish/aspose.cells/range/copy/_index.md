---
title: copy método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/range/copy/
is_root: false
---
##  copy(range) {#Range}
Copia datos (incluidas fórmulas), formato, objetos de dibujo, etc. de un rango de origen.



```python
def copy(self, range):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| range | [Range](/cells/python-net/es/aspose.cells/range) | Objeto de origen [Range](/cells/python-net/es/aspose.cells/range).|

###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy(range, options) {#Range-PasteOptions}
Copiando el rango con opciones especiales de pegado.



```python
def copy(self, range, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| range | [Range](/cells/python-net/es/aspose.cells/range) | El rango de la fuente.|
| options | [PasteOptions](/cells/python-net/es/aspose.cells/pasteoptions) | Las opciones especiales de pegado.|



###  Ver también
* módulo [aspose.cells](../../)
* clase [Range](/cells/python-net/es/aspose.cells/range)
