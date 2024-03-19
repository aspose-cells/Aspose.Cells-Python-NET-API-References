---
title: refresh_dynamic_array_formulas Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 270
url: /de/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
Aktualisiert dynamische Array-Formeln (überläuft entsprechend den aktuellen Daten in einen neuen Bereich benachbarter Zellen)
Andere Formeln in der Arbeitsmappe werden nicht rekursiv berechnet, selbst wenn sie von dynamischen Array-Formeln verwendet wurden.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| calculate | bool | Ob Zellwerte für diese dynamischen Array-Formeln berechnet und aktualisiert werden|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
Aktualisiert dynamische Array-Formeln (überläuft entsprechend den aktuellen Daten in einen neuen Bereich benachbarter Zellen)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| calculate | bool | Ob Zellwerte für diese dynamischen Array-Formeln berechnet und aktualisiert werden|
| copts | [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions) | Die Optionen zur Berechnung von Formeln|
###  Bemerkungen

Aus Leistungsgründen aktualisieren wir nicht alle dynamischen Array-Formeln automatisch
wenn sich die Formel selbst oder die Daten, auf die sie verweist, geändert haben.
Daher muss der Benutzer diese Methode nach den Vorgängen, die sich auf dynamische Array-Formeln auswirken können, manuell aufrufen.
wie das Importieren/Festlegen von Zellwerten, das Einfügen/Löschen von Zeilen/Spalten/Bereichen usw.

Bei den meisten Formeln mit Funktionen muss zur Berechnung des Überlaufbereichs auch die Formel berechnet werden.
Daher wird im Allgemeinen der wahre Wert für das Flag „Berechnen“ bevorzugt.
Wenn die Formel einfach ist, beispielsweise eine Bereichsreferenz oder ein Array (z. B. „=C1:E5“, „={1,2;3,4}“, ...),
einfache Funktion für einen Bereich oder ein Array (zum Beispiel „=ABS(C1:E5)“, „=1+{1,2;3,4}“, ...),
und alle Formeln werden später berechnet (z. B. bis [`Workbook.calculate_formula`](/cells/python-net/de/aspose.cells/workbook/calculate_formula)),
Wenn Sie dann den falschen Wert für das Flag „Berechnen“ verwenden, kann die doppelte Berechnung zugunsten der Leistung vermieden werden.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
