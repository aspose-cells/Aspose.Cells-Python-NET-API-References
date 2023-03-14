---
title: metodo move
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 150
url: /it/aspose.cells.drawing/picture/move/
is_root: false
---
##  move(upper_left_row, upper_left_column) {#int-int}
Sposta l'immagine in una posizione specificata.



```python
def move(self, upper_left_row, upper_left_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice colonna in alto a sinistra.|

###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Adding a picture at the location of a cell whose row and column indices are 1 in the worksheet. It is "B2" cell
imgIndex = worksheet.pictures.add(1, 1, "example.jpeg")
# Get the inserted picture object
pic = worksheet.pictures[imgIndex]
# Set the new location of the picture
pic.move(2, 4)
# Save the excel file.
workbook.save("result.xlsx")

```



###  Guarda anche
* modulo [aspose.cells.drawing](../../)
* classe [Picture](/cells/python-net/it/aspose.cells.drawing/picture)
