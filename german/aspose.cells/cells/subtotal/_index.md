---
title: subtotal Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 910
url: /de/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Erstellt Zwischensummen für den Bereich.



```python
def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) | Die Reichweite|
| group_by | int | Das Feld, nach dem gruppiert werden soll, als nullbasierter ganzzahliger Offset|
| function | [`ConsolidationFunction`](/cells/python-net/de/aspose.cells/consolidationfunction) | Die Zwischensummenfunktion.|
| total_list | list | Ein Array nullbasierter Feldoffsets, das die Felder angibt, zu denen die Zwischensummen hinzugefügt werden.|


##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Erstellt Zwischensummen für den Bereich.



```python
def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) | Die Reichweite|
| group_by | int | Das Feld, nach dem gruppiert werden soll, als nullbasierter ganzzahliger Offset|
| function | [`ConsolidationFunction`](/cells/python-net/de/aspose.cells/consolidationfunction) | Die Zwischensummenfunktion.|
| total_list | list | Ein Array nullbasierter Feldoffsets, das die Felder angibt, zu denen die Zwischensummen hinzugefügt werden.|
| replace | bool | Gibt an, ob die aktuellen Zwischensummen ersetzt werden|
| page_breaks | bool | Gibt an, ob ein Seitenumbruch zwischen Gruppen hinzugefügt wird|
| summary_below_data | bool | Gibt an, ob unter den Daten eine Zusammenfassung hinzugefügt werden soll.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
