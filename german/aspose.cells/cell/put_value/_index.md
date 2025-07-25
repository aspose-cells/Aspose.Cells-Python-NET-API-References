---
title: put_value Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 290
url: /de/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
Fügt einen Booleschen Wert in die Zelle ein.



```python

def put_value(self, bool_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
Fügt einen ganzzahligen Wert in die Zelle ein.



```python

def put_value(self, int_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| int_value | int | Eingabewert|


##  put_value(self, double_value) {#float}
Fügt einen doppelten Wert in die Zelle ein.



```python

def put_value(self, double_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| double_value | float | Eingabewert|


##  put_value(self, string_value) {#str}
Fügt einen Zeichenfolgenwert in die Zelle ein.



```python

def put_value(self, string_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| string_value | str | Eingabewert|


##  put_value(self, date_time) {#DateTime}
Fügt einen DateTime-Wert in die Zelle ein.



```python

def put_value(self, date_time):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| date_time | DateTime | Eingabewert|
###  Bemerkungen

Das Festlegen eines DateTime-Werts für eine Zelle bedeutet nicht, dass die Zelle automatisch als Datum/Uhrzeit formatiert wird.
Der DateTime-Wert wurde im Datenmodell von MS Excel und Aspose.Cells als numerischer Wert beibehalten.
Ob der numerische Wert als numerischer Wert selbst oder als Datum/Uhrzeit verwendet wird
hängt vom Zahlenformat dieser Zelle ab. Wenn diese Zelle nicht als Datum/Uhrzeit formatiert ist,
Es wird als numerischer Wert angezeigt, auch wenn Sie DateTime eingeben.
###  Beispiel

Dieses Beispiel zeigt, wie Sie einer Zelle einen DateTime-Wert zuweisen und ihn als Datum und Uhrzeit anzeigen lassen.

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


##  put_value(self, object_value) {#any}
Fügt einen Objektwert in die Zelle ein.



```python

def put_value(self, object_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| object_value | any | Eingabewert|


##  put_value(self, string_value, is_converted) {#str-bool}
Fügt einen Zeichenfolgenwert in die Zelle ein und konvertiert den Wert gegebenenfalls in einen anderen Datentyp.



```python

def put_value(self, string_value, is_converted):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| string_value | str | Eingabewert|
| is_converted | bool | True: Gegebenenfalls in einen anderen Datentyp konvertiert.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
Fügt einen Wert in die Zelle ein. Gegebenenfalls wird der Wert in einen anderen Datentyp konvertiert und das Zahlenformat der Zelle wird zurückgesetzt.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| string_value | str | Eingabewert|
| is_converted | bool | True: Gegebenenfalls in einen anderen Datentyp konvertiert.|
| set_style | bool | True: Setzt das Zahlenformat auf den Stil der Zelle, wenn es in einen anderen Datentyp konvertiert wird|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
