---
title: put_value Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 280
url: /de/aspose.cells/cell/put_value/
is_root: false
---
##  put_value {#bool}
Fügt einen booleschen Wert in die Zelle ein.



```python
def put_value(self, bool_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value {#int}
Fügt einen ganzzahligen Wert in die Zelle ein.



```python
def put_value(self, int_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| int_value | int | Eingegebener Wert|


##  put_value {#float}
Fügt einen Double-Wert in die Zelle ein.



```python
def put_value(self, double_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| double_value | float | Eingegebener Wert|


##  put_value {#str}
Fügt einen Zeichenfolgewert in die Zelle ein.



```python
def put_value(self, string_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| string_value | str | Eingegebener Wert|


##  put_value {#DateTime}
Fügt einen DateTime-Wert in die Zelle ein.



```python
def put_value(self, date_time):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| date_time | DateTime | Eingegebener Wert|
###  Bemerkungen

Das Festlegen eines DateTime-Werts für eine Zelle bedeutet nicht, dass die Zelle automatisch als Datum/Uhrzeit formatiert wird.
Der DateTime-Wert wurde als numerischer Wert im Datenmodell von MS Excel und Aspose.Cells verwaltet.
Ob der numerische Wert als numerischer Wert selbst oder als Datum/Uhrzeit verwendet wird
hängt vom Zahlenformat ab, das auf diese Zelle angewendet wird. Wenn diese Zelle nicht als Datum/Uhrzeit formatiert wurde,
Es wird als numerischer Wert angezeigt, obwohl Sie DateTime eingeben.
###  Beispiel

Dieses Beispiel zeigt, wie man den DateTime-Wert für eine Zelle festlegt und dafür sorgt, dass er als Datum und Uhrzeit angezeigt wird.

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value {#any}
Fügt einen Objektwert in die Zelle ein.



```python
def put_value(self, object_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| object_value | any | eingegebener Wert|


##  put_value {#str-bool}
Fügt einen Zeichenfolgewert in die Zelle ein und konvertiert den Wert gegebenenfalls in einen anderen Datentyp.



```python
def put_value(self, string_value, is_converted):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| string_value | str | Eingegebener Wert|
| is_converted | bool | True: ggf. in einen anderen Datentyp konvertiert.|


##  put_value {#str-bool-bool}
Fügt einen Wert in die Zelle ein. Gegebenenfalls wird der Wert in einen anderen Datentyp konvertiert und das Zahlenformat der Zelle wird zurückgesetzt.



```python
def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| string_value | str | Eingegebener Wert|
| is_converted | bool | True: ggf. in einen anderen Datentyp konvertiert.|
| set_style | bool | True: Stellen Sie beim Konvertieren in einen anderen Datentyp das Zahlenformat auf den Zellstil ein|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
