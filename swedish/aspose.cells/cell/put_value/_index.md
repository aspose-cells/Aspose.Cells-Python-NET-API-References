---
title: put_value metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 290
url: /sv/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
Lägger in ett booleskt värde i cellen.



```python

def put_value(self, bool_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
Lägger in ett heltal i cellen.



```python

def put_value(self, int_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| int_value | int | Inmatningsvärde|


##  put_value(self, double_value) {#float}
Lägger in ett dubbelt värde i cellen.



```python

def put_value(self, double_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| double_value | float | Inmatningsvärde|


##  put_value(self, string_value) {#str}
Lägger in ett strängvärde i cellen.



```python

def put_value(self, string_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| string_value | str | Inmatningsvärde|


##  put_value(self, date_time) {#DateTime}
Lägger in ett DateTime-värde i cellen.



```python

def put_value(self, date_time):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| date_time | DateTime | Inmatningsvärde|
###  Anmärkningar

Att ange ett DateTime-värde för en celldos betyder inte att cellen automatiskt formateras som datum och tid.
DateTime-värdet bibehölls som ett numeriskt värde i datamodellen för både MS Excel och Aspose.Cells.
Om det numeriska värdet ska tas som själva det numeriska värdet eller datum och tid
beror på vilket talformat som används på den här cellen. Om den här cellen inte har formaterats som datum och tid,
Det kommer att visas som ett numeriskt värde även om det du anger är DateTime.
###  Exempel

Det här exemplet visar hur man ställer in ett DateTime-värde i en cell och får det att visas som datum och tid.

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
Lägger in ett objektvärde i cellen.



```python

def put_value(self, object_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| object_value | any | ingångsvärde|


##  put_value(self, string_value, is_converted) {#str-bool}
Lägger in ett strängvärde i cellen och konverterar värdet till en annan datatyp om det är lämpligt.



```python

def put_value(self, string_value, is_converted):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| string_value | str | Inmatningsvärde|
| is_converted | bool | Sant: konverterat till annan datatyp om tillämpligt.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
Lägger in ett värde i cellen. Om det är lämpligt konverteras värdet till en annan datatyp och cellens talformat återställs.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| string_value | str | Inmatningsvärde|
| is_converted | bool | Sant: konverterat till annan datatyp om tillämpligt.|
| set_style | bool | Sant: ange talformatet till cellens stil vid konvertering till annan datatyp|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
