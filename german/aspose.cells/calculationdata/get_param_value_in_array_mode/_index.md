---
title: get_param_value_in_array_mode Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode {#int-int-int}
Ruft den/die Wert(e) des Parameters am angegebenen Index ab.
Wenn es sich bei dem Parameter um einen Ausdruck handelt, der berechnet werden muss,
dann wird es im Array-Modus berechnet.


###  Kehrt zurück

Ein Array, das alle durch den angegebenen Parameter dargestellten Elemente enthält.


```python
def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | Der Index des Parameters (0-basiert)|
| max_row_count | int | Die Zeilenanzahlbegrenzung für das zurückgegebene Array.<br/> Wenn es nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Zeilenanzahl verwendet.|
| max_column_count | int | Der Grenzwert für die Spaltenanzahl für das zurückgegebene Array.<br/> Wenn es nicht positiv oder größer als die tatsächliche Zeilenanzahl ist, wird die tatsächliche Spaltenanzahl verwendet.|
###  Bemerkungen

Für einen Ausdruck, der berechnet werden muss, am Beispiel von A:A+B:B:
Im Wertemodus wird er entsprechend der aktuellen Zellbasis zu einem einzelnen Wert berechnet.
Aber im Array-Modus werden alle Werte von A1+B1,A2+B2,A3+B3,... berechnet und zum Aufbau des zurückgegebenen Arrays verwendet.
Und für eine solche Situation ist es besser, den Grenzwert für die Zeilen-/Spaltenanzahl anzugeben
(z. B. nach [`Cells.max_data_row`](/cells/python-net/de/aspose.cells/cells#max_data_row) und [`Cells.max_data_column`](/cells/python-net/de/aspose.cells/cells#max_data_column)),
Andernfalls kann das zurückgegebene große Array die Speicherkosten aufgrund einer großen Menge nutzloser Daten erhöhen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata)
