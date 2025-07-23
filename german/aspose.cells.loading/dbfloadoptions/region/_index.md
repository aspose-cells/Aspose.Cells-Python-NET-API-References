---
title: region Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 210
url: /de/aspose.cells.loading/dbfloadoptions/region/
is_root: false
---
##  region Eigentum

Ruft die regionalen Einstellungen für die zu ladende Arbeitsmappe ab oder legt diese fest.

###  Bemerkungen

Die regionalen Einstellungen können zum Initialisieren einiger Funktionen für die Arbeitsmappe verwendet werden
wie Schriftarten, Themen usw.
Für textbasierte Dateiformate wie CSV, HTML, ..., die regionale Einstellung
wird auch verwendet, um Zahlenformate zu erkennen und Textwerte in numerische Werte zu zerlegen
oder Datums-/Uhrzeitwerte für Zellen.
Diese Einstellung bleibt später für die instanziierte Arbeitsmappe erhalten, d.h.
[`WorkbookSettings.region`](/cells/python-net/de/aspose.cells/workbooksettings#region) der Arbeitsmappe wird die gleiche region verwenden
mit dieser Eigenschaft.
###  Definition:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.loading`](../../)
* Klasse [`CountryCode`](/cells/python-net/de/aspose.cells/countrycode)
* Klasse [`DbfLoadOptions`](/cells/python-net/de/aspose.cells.loading/dbfloadoptions)
