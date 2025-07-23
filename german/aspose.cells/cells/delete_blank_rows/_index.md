---
title: delete_blank_rows Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 210
url: /de/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Löschen Sie alle leeren Zeilen, die keine Daten oder andere Objekte enthalten.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Löschen Sie alle leeren Zeilen, die keine Daten oder spezielle Objekte wie sichtbare Kommentare oder Pivot-Tabellen enthalten.



```python

def delete_blank_rows(self, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/de/aspose.cells/deleteoptions) | Die Optionen zum Löschen des Bereichs.|
###  Bemerkungen

Für leere Zeilen, die gelöscht werden, ist es nicht nur erforderlich, dass [`Row.is_blank`](/cells/python-net/de/aspose.cells/row#is_blank) wahr ist,
aber auch sollte für keine Zelle in diesen Zeilen ein sichtbarer Kommentar definiert sein,
und keine Pivot-Tabelle, deren Bereich sich mit ihnen überschneidet.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
