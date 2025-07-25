---
title: SystemTimeInterruptMonitor Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1390
url: /de/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor Klasse
Einfache Implementierung von AbstractInterruptMonitor durch Überprüfen und Vergleichen der aktuellen Systemzeit mit dem vom Benutzer angegebenen Limit.



**Nachlass:** [`SystemTimeInterruptMonitor`](/cells/python-net/de/aspose.cells/systemtimeinterruptmonitor)



Der Typ SystemTimeInterruptMonitor macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/de/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Konstruiert einen Unterbrechungsmonitor.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_interruption_requested](/cells/python-net/de/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | Diese Implementierung prüft lediglich, ob der Zeitaufwand (vom Start dieses Monitors bis jetzt) größer als das vom Benutzer angegebene Limit ist.|
| [terminate_without_exception](/cells/python-net/de/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |Siehe TerminateWithoutException.<br/> Diese Eigenschaft wird vom Benutzer beim Erstellen dieser Monitorinstanz angegeben.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/de/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Startet den Monitor mit dem angegebenen Zeitlimit. Der Startzeitpunkt für die Berechnung der Zeitkosten ist der Aufruf dieser Methode.<br/> Daher sollte der zu überwachende Vorgang unmittelbar nach diesem Anruf gestartet werden.|



###  Bemerkungen

Diese Implementierung ist nur eine einfache Lösung für einfache Szenarien.
Es muss die Systemzeit häufig abrufen und überprüfen, was sich in gewissem Maße negativ auf die Leistung auswirken kann.

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`SystemTimeInterruptMonitor`](/cells/python-net/de/aspose.cells/systemtimeinterruptmonitor)
