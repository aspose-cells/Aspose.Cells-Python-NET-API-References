---
title: calculation_id Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 50
url: /de/aspose.cells/formulasettings/calculation_id/
is_root: false
---
##  calculation_id Eigentum

Gibt die Version der Berechnungs-Engine an, die zum Berechnen der Werte in der Arbeitsmappe verwendet wird.

###  Bemerkungen

Diese Eigenschaft dient nur zum Speichern der Einstellungen in der resultierenden Tabellenkalkulationsdatei
damit andere Anwendungen (wie z. B. MS Excel) beim Laden und Bearbeiten der resultierenden Datei entsprechend reagieren können.
Im Fall von MS Excel, wenn der Wert dieser Eigenschaft kleiner ist als die zugehörige Kennung der Neuberechnungs-Engine
Mit der Anwendung, die die resultierende Datei öffnet, berechnet die Anwendung die Ergebnisse aller Formeln neu
auf dieser Arbeitsmappe unmittelbar nach dem Laden der Datei.
Aus Leistungsgründen berechnen wir für die meisten Benutzeranwendungen keine Formeln in der Arbeitsmappe automatisch.
unabhängig davon, welcher Wert für diese Eigenschaft festgelegt wurde.
###  Definition:
```python
@property
def calculation_id(self):
    ...
@calculation_id.setter
def calculation_id(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FormulaSettings`](/cells/python-net/de/aspose.cells/formulasettings)
