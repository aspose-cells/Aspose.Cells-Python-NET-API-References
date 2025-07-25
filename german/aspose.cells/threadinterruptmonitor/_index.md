---
title: ThreadInterruptMonitor Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1410
url: /de/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor Klasse
Einfache Implementierung von AbstractInterruptMonitor durch Starten eines weiteren Threads, um die Unterbrechung nach dem vom Benutzer angegebenen Ruhezeitlimit zu erfordern.



**Nachlass:** [`ThreadInterruptMonitor`](/cells/python-net/de/aspose.cells/threadinterruptmonitor)



Der Typ ThreadInterruptMonitor macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/de/aspose.cells/threadinterruptmonitor/__init__/#bool) | Konstruiert einen Unterbrechungsmonitor.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_interruption_requested](/cells/python-net/de/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Diese Implementierung prüft lediglich, ob der Zeitaufwand (vom Start dieses Monitors bis jetzt) größer als das vom Benutzer angegebene Limit ist.|
| [terminate_without_exception](/cells/python-net/de/aspose.cells/threadinterruptmonitor/terminate_without_exception) |Siehe TerminateWithoutException.<br/> Diese Eigenschaft wird vom Benutzer beim Erstellen dieser Monitorinstanz angegeben.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/de/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Startet den Monitor mit dem angegebenen Zeitlimit. Der Startzeitpunkt für die Berechnung der Zeitkosten ist der Aufruf dieser Methode.<br/> Daher sollte der zu überwachende Vorgang unmittelbar nach diesem Anruf gestartet werden.|
| [`finish_monitor(self)`](/cells/python-net/de/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Beendet den Monitor für einen Vorgang.|



###  Bemerkungen

Eine Monitorinstanz kann wiederholt verwendet werden, solange Sie jeden Prozess der Reihe nach überwachen.
Es sollte nicht verwendet werden, um mehrere Prozeduren gleichzeitig in mehreren Threads zu überwachen.

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`ThreadInterruptMonitor`](/cells/python-net/de/aspose.cells/threadinterruptmonitor)
