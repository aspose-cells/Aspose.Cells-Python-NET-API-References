---
title: refresh_dynamic_array_formulas Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 290
url: /de/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
Aktualisiert dynamische Array-Formeln (Überlauf in einen neuen Bereich benachbarter Zellen entsprechend den aktuellen Daten)
Andere Formeln in der Arbeitsmappe werden nicht rekursiv berechnet, selbst wenn sie von dynamischen Arrayformeln verwendet wurden.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| calculate | bool | Ob berechnet und aktualisiert Zellwerte für diese dynamischen Array-Formeln|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
Aktualisiert dynamische Array-Formeln (Überlauf in einen neuen Bereich benachbarter Zellen entsprechend den aktuellen Daten)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| calculate | bool | Ob berechnet und aktualisiert Zellwerte für diese dynamischen Array-Formeln|
| copts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Die Möglichkeiten zur Berechnung von Formeln|
###  Bemerkungen

Aus Leistungsgründen aktualisieren wir nicht alle dynamischen Array-Formeln automatisch
wenn sich die Formel selbst oder die Daten, auf die sie verweist, geändert haben.
Daher muss der Benutzer diese Methode nach den Vorgängen, die dynamische Array-Formeln beeinflussen können, manuell aufrufen.
wie z. B. Importieren/Festlegen von Zellenwerten, Einfügen/Löschen von Zeilen/Spalten/Bereichen usw.

Bei den meisten Formeln mit Funktionen muss zur Berechnung des Überlaufbereichs auch die Formel berechnet werden.
Daher wird im Allgemeinen der wahre Wert für die Flagge „Berechnen“ bevorzugt.
Wenn die Formel einfach ist, z. B. ein Bereichsverweis oder ein Array (z. B. "=C1:E5", "={1,2;3,4}", ...),
einfache Funktion für einen Bereich oder ein Array (zum Beispiel "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
und alle Formeln werden später berechnet(z.B. von [`Workbook.calculate_formula`](/cells/python-net/de/aspose.cells/workbook/calculate_formula)),
Dann kann die Verwendung des Werts „false“ für das Flag „Berechnen“ die doppelte Berechnung zum Vorteil der Leistung vermeiden.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
