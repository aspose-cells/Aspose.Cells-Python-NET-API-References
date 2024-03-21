---
title: LoadFilter Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1050
url: /de/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter Klasse
Stellt den Filter dar, der Optionen zum Laden von Daten bereitstellt, wenn eine Arbeitsmappe aus einer Vorlage geladen wird.



Der Typ LoadFilter macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/loadfilter/__init__/#) | Konstruiert einen LoadFilter mit den Standardfilteroptionen LoadDataFilterOptions.All.|
| [__init__](/cells/python-net/de/aspose.cells/loadfilter/__init__/#aspose.cells.LoadDataFilterOptions) | Konstruiert einen LoadFilter mit angegebenen Filteroptionen.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [load_data_filter_options](/cells/python-net/de/aspose.cells/loadfilter/load_data_filter_options) | Die Filteroptionen geben an, welche Daten geladen werden sollen.|
| [sheets_in_loading_order](/cells/python-net/de/aspose.cells/loadfilter/sheets_in_loading_order) | Gibt die zu ladenden Blätter (Indizes) und Reihenfolge an.<br/>Der Standardwert ist null, was bedeutet, dass alle Blätter in der Standardreihenfolge in der Vorlagendatei geladen werden.<br/> Wenn nicht null und der Index eines Blatts nicht im zurückgegebenen Array enthalten ist, wird das Blatt nicht geladen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [start_sheet](/cells/python-net/de/aspose.cells/loadfilter/start_sheet/#aspose.cells.Worksheet) | Bereitet Filteroptionen vor, bevor das angegebene Arbeitsblatt geladen wird.<br/>Die LoadDataFilterOptions können hier durch die Implementierung von LoadFilter durch den Benutzer geändert werden<br/> um anzugeben, wie Daten für dieses Arbeitsblatt geladen werden.|



###  Bemerkungen

Der Benutzer kann die Filteroptionen angeben oder seine eigene LoadFilter implementieren, um anzugeben, wie Daten geladen werden sollen.

###  Siehe auch
* Modul [`aspose.cells`](..)
