---
title: memory_setting Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1160
url: /de/aspose.cells/cells/memory_setting/
is_root: false
---
##  memory_setting Eigentum

Ruft die Speichernutzungsoption für diese Zellen ab oder legt sie fest.

###  Bemerkungen

Wichtige Einschränkungen und empfohlene Vorgänge für einige Modi:
| Modus| Bemerkungen| Unterstützt|
| :- | :- | :- |
|
 um den Speicheraufwand zu senken. Andererseits können die kompakten Daten auch
 verursachen einen höheren Zeitaufwand, insbesondere bei der Aktualisierung der Zelldaten,
 oder zufälliger Zugriff auf Zellen/Zeilen | v8.0.0 |
|
 Wenn dieser Modus für ein beliebiges Arbeitsblatt in einer Arbeitsmappe verwendet wird, |
 sollte am Ende der Arbeit aufgerufen werden, um alle Ressourcen wie die temporären Dateien freizugeben.
            | 
 Der zufällige Zugriff auf Zellen führt zu einer schlechten Leistung, da Daten
 zufällig und wiederholt gelesen/aktualisiert werden (der Zeiger in der Datei wird also
entsprechend geändert und IO-Operationen werden wiederholt erforderlich).
 Greifen Sie wenn möglich immer sequenziell (zeilenweise) auf die Daten zu.
            | 
 Wenn die Daten einer Zeile/Zelle geändert werden, werden die Daten anderer Zellen/Zeilen
 kann auch beeinflusst werden (z.B. die Daten werden an andere Orte verschoben/verlegt
 um genügend Speicherplatz für die geänderten Daten bereitzustellen).
 Daher erfordert jede Änderung aller Daten eine Synchronisierung anderer vorhandener Objekte (
 wie z. B. Row oder Cell-Objekt).
 Um eine bessere Leistung zu erzielen, pflegen Sie bitte nicht mehrere Zeilen/Cells
 gleichzeitig. Die Verarbeitung der einzelnen Schritte reduziert die Datensynchronisation
 für sie, damit die Leistung etwas verbessert werden kann.
 | Version 25.7 |
###  Definition:
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
* Klasse [`MemorySetting`](/cells/python-net/de/aspose.cells/memorysetting)
