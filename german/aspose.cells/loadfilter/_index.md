---
title: LoadFilter Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 940
url: /de/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter Klasse
Stellt den Filter dar, der Optionen zum Laden von Daten beim Laden einer Arbeitsmappe aus einer Vorlage bereitstellt.



Der Typ LoadFilter macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/loadfilter/__init__/#) | Erstellt einen LoadFilter mit den Standardfilteroptionen LoadDataFilterOptions.All.|
| [`__init__(self, opts)`](/cells/python-net/de/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) | Erstellt einen LoadFilter mit den angegebenen Filteroptionen.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_data_filter_options](/cells/python-net/de/aspose.cells/loadfilter/load_data_filter_options) |Die Filteroptionen geben an, welche Daten geladen werden sollen.|
| [sheets_in_loading_order](/cells/python-net/de/aspose.cells/loadfilter/sheets_in_loading_order) | Gibt die zu ladenden Blätter (Indizes) und die Reihenfolge an.<br/>Der Standardwert ist null, was bedeutet, dass alle Blätter in der Standardreihenfolge in der Vorlagendatei geladen werden.<br/> Wenn nicht null und der Index eines Blatts nicht im zurückgegebenen Array enthalten ist, wird das Blatt nicht geladen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/de/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) | Bereitet Filteroptionen vor, bevor das angegebene Arbeitsblatt geladen wird.<br/>Die Implementierung von LoadFilter durch den Benutzer kann die LoadDataFilterOptions hier ändern<br/> um anzugeben, wie Daten für dieses Arbeitsblatt geladen werden.|



###  Bemerkungen

Der Benutzer kann die Filteroptionen angeben oder seine eigenen LoadFilter implementieren, um anzugeben, wie die Daten geladen werden sollen.

###  Siehe auch
* Modul [`aspose.cells`](..)
