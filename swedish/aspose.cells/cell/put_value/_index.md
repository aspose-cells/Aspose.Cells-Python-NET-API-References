---
title: put_value metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 280
url: /sv/aspose.cells/cell/put_value/
is_root: false
---
##  put_value {#bool}
Lägger in ett booleskt värde i cellen.



```python
def put_value(self, bool_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value {#int}
Lägger in ett heltalsvärde i cellen.



```python
def put_value(self, int_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| int_value | int | Ingångsvärde|


##  put_value {#float}
Lägger ett dubbelt värde i cellen.



```python
def put_value(self, double_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| double_value | float | Ingångsvärde|


##  put_value {#str}
Lägger ett strängvärde i cellen.



```python
def put_value(self, string_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| string_value | str | Ingångsvärde|


##  put_value {#DateTime}
Lägger in ett DateTime-värde i cellen.



```python
def put_value(self, date_time):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| date_time | DateTime | Ingångsvärde|
###  Anmärkningar

Att ställa in ett DateTime-värde för en celldos betyder inte att cellen formateras som datum och tid automatiskt.
DateTime-värdet bibehölls som numeriskt värde i datamodellen för både ms excel och Aspose.Cells.
Om det numeriska värdet kommer att tas som själva numeriska värdet eller datum och tid
beror på det talformat som används på den här cellen. Om den här cellen inte har formaterats som datum och tid,
det kommer att visas som ett numeriskt värde även om det du matar in är DateTime.
###  Exempel

Det här exemplet visar hur du ställer in DateTime-värdet på en cell och får det att visas som datumtid.

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
Lägger ett objektvärde i cellen.



```python
def put_value(self, object_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| object_value | any | ingångsvärde|


##  put_value {#str-bool}
Lägger in ett strängvärde i cellen och konverterar värdet till en annan datatyp om så är lämpligt.



```python
def put_value(self, string_value, is_converted):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| string_value | str | Ingångsvärde|
| is_converted | bool | Sant: konverteras till annan datatyp om så är lämpligt.|


##  put_value {#str-bool-bool}
Lägger ett värde i cellen, om så är lämpligt kommer värdet att konverteras till annan datatyp och cellens talformat återställs.



```python
def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| string_value | str | Ingångsvärde|
| is_converted | bool | Sant: konverteras till annan datatyp om så är lämpligt.|
| set_style | bool | Sant: ställ in talformatet till cellens stil vid konvertering till annan datatyp|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
