---
title: calculation_mode Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
##  calculation_mode Eigentum

Ruft den Modus für die Arbeitsmappenberechnung in MS Excel ab oder legt ihn fest.

###  Bemerkungen

Diese Eigenschaft dient nur zum Speichern der Einstellungen in der resultierenden Tabellenkalkulationsdatei
damit andere Anwendungen (wie z. B. MS Excel) beim Laden und Bearbeiten der resultierenden Datei entsprechend reagieren können.
Aus Leistungsgründen berechnen wir für die meisten Benutzeranwendungen keine Formeln in der Arbeitsmappe automatisch.
unabhängig davon, welcher Modus für diese Eigenschaft eingestellt wurde.
Wenn der Benutzer Formeln berechnen muss, rufen Sie je nach Bedarf immer Methoden auf verschiedenen Objekten auf:
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/de/aspose.cells/cell/calculate), ...usw.
###  Definition:
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalcModeType`](/cells/python-net/de/aspose.cells/calcmodetype)
* Klasse [`FormulaSettings`](/cells/python-net/de/aspose.cells/formulasettings)
