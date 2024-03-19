---
title: preprocess_exported_value Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
Verarbeiten Sie den Wert der aktuellen Zelle, die exportiert werden soll, vor.


###  Kehrt zurück

Ob die aktuelle Zelle durch einen anderen Typ und/oder Wert ersetzt wurde.


```python
def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_row | int | der Zeilenindex der aktuellen Zelle|
| cell_column | int | der Spaltenindex der Zelle|
| value | [`CellValue`](/cells/python-net/de/aspose.cells/cellvalue) | Wert und Typ der aktuellen Zelle|
###  Bemerkungen

Der Zeilen- und Spaltenindex ist der absolute Index der Zelle im Arbeitsblatt, nicht der Index in der exportierten Tabelle.
Der Benutzer kann den Wert der aktuellen Zelle in der Override-Implementierung dieser Methode überprüfen.
Wenn die aktuelle Zelle durch einen anderen Typ und Wert ersetzt werden muss,
Hier sollte die Implementierung den erwarteten Typ und Wert auf das CellValue-Objekt festlegen und true zurückgeben.
Standardmäßig führt diese Methode nichts aus und gibt „false“ zurück.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`ExportTableOptions`](/cells/python-net/de/aspose.cells/exporttableoptions)
