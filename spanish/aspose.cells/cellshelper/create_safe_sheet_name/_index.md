---
title: método create_safe_sheet_name
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, nombre_propuesta){#str}
Comprueba el nombre de la hoja dada y crea uno válido cuando sea necesario.
Si el nombre de la hoja dada cumple con las reglas del nombre de hoja de Excel, devuélvalo.
De lo contrario, la cadena se truncará si la longitud excede el límite.
y los caracteres no válidos se reemplazarán con ' ' y luego se devolverá el valor de la cadena reconstruida.


###  Devoluciones




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| name_proposal | str | Nombre de la hoja que se utilizará|


##  create_safe_sheet_name(, propuesta_de_nombre, reemplazar_carácter){#str-char}
Comprueba el nombre de la hoja dada y crea uno válido cuando sea necesario.
Si el nombre de la hoja dada cumple con las reglas del nombre de hoja de Excel, devuélvalo.
De lo contrario, la cadena se truncará si la longitud excede el límite.
y los caracteres no válidos serán reemplazados con el carácter dado y luego se devolverá el valor de la cadena reconstruida.


###  Devoluciones




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| name_proposal | str | Nombre de la hoja que se utilizará|
| replace_char | char | Carácter que se usará para reemplazar caracteres no válidos en el nombre de la hoja dada.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CellsHelper`](/cells/python-net/es/aspose.cells/cellshelper)
