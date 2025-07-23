---
title: AccessCacheOptions Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1710
url: /de/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions Aufzählung
Cache-Optionen für den Datenzugriff. Kann mit dem Operator | für mehrere Optionen kombiniert werden.



Der Typ AccessCacheOptions macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| NONE | Kein Cache für Datenzugriffe.|
| ALL | Wenden Sie alle möglichen Optimierungen für alle Arten des Datenzugriffs in der Arbeitsmappe an.<br/> Sämtliche Einstellungen und Daten sollten während des optimierten Zugriffs nicht verändert werden.|
| POSITION_AND_SIZE | Wenden Sie mögliche Optimierungen an, um die Position und Größe von Objekten (z. B. Formen) zu ermitteln.<br/> Die Einstellungen für Zeilenhöhe und Spaltenbreite sollten während des optimierten Zugriffs nicht geändert werden.|
| CELLS_DATA | Wenden Sie mögliche Optimierungen zum Abrufen der Zellwerte an.<br/>Cells Daten (Daten und Einstellungen von Cell, Zeile) sollten während<br/>Beim optimierten Zugriff sollten auch keine neuen Cell/Row-Objekte angelegt werden (z.B.<br/> von [indexer]).|
| CELL_DISPLAY | Wenden Sie mögliche Optimierungen an, um anzeigebezogene Ergebnisse zu erhalten von<br/>Zellen ([`Cell.display_string_value`](/cells/python-net/de/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/de/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style) usw.).<br/>Cells Daten und stilbezogene Objekte (Cell/Zeilen-/Spaltenstile, Spaltenbreite usw.) sollten nicht geändert werden<br/> während des optimierten Zugriffs.|
| GET_FORMULA | Wenden Sie mögliche Optimierungen zum Erhalten von Formeln an.<br/>Alle Daten und Einstellungen, die den Formelausdruck beeinflussen können (Name des Arbeitsblatts, Text des Namens,<br/> Tabellenspalten usw.) sollten während des optimierten Zugriffs nicht geändert werden.|
| SET_FORMULA | Wenden Sie mögliche Optimierungen für die Einstellung von Formeln an.<br/>Alle Daten und Einstellungen, die den Formelausdruck beeinflussen können (Name des Arbeitsblatts, Text des Namens,<br/> Tabellenspalten usw.) sollten während des optimierten Zugriffs nicht geändert werden.|
| CALCULATE_FORMULA | Wenden Sie mögliche Optimierungen für die Berechnung von Formeln an.<br/>Cells Daten sollen beim optimierten Zugriff nicht verändert werden, keine neuen Objekte (Cell, Row, etc.)<br/> sollte entweder erstellt werden (z. B. von [Indexer]).|
| CONDITIONAL_FORMATTING | Wenden Sie mögliche Optimierungen an, um das Formatierungsergebnis bedingter Formatierungen zu erhalten.<br/>Alle Daten und Einstellungen, die das Ergebnis bedingter Formatierungen beeinflussen können (Einstellungen von<br/> Bedingte Formatierungen, abhängige Zellwerte etc.) sollten während des optimierten Zugriffs nicht verändert werden.|
| VALIDATION | Wenden Sie mögliche Optimierungen an, um ein Validierungsergebnis zu erhalten.<br/>Alle Daten und Einstellungen, die das Ergebnis der Validierung beeinflussen können (Einstellungen der Validierung,<br/> abhängige Zellwerte etc.) sollten während des optimierten Zugriffs nicht verändert werden.|



###  Bemerkungen

Für einige Funktionen erfordert der Zugriff auf große Datensätze viele wiederholte und komplizierte Vorgänge
wie Suche, Berechnung usw. und diese Vorgänge nehmen viel zusätzliche Zeit in Anspruch.
In den meisten Fällen bleiben alle abhängigen Daten während des Zugriffs unverändert, sodass einige Caches erstellt und verwendet werden können, um
Verbessern Sie die Zugriffsleistung.
Zu diesem Zweck stellen wir diese API zur Verfügung, damit der Benutzer angeben kann, welche Art von Datenzugriff benötigt wird
durch mögliche Caching-Mechanismen zu optimieren.


Bitte beachten Sie, dass für verschiedene Optionen möglicherweise unterschiedliche Datensätze schreibgeschützt sein müssen.
Und die Leistung des Datenzugriffs hängt von vielen Aspekten ab, der Verwendung von Caching-Mechanismen
garantiert nicht, dass die Leistung verbessert wird. In einigen Situationen
Wenn beispielsweise der Datensatz, auf den zugegriffen werden soll, klein ist, kann die Verwendung des Caches noch mehr Zeit verursachen, weil
Auch das Caching selbst benötigt eine gewisse zusätzliche Zeit.

###  Siehe auch
* Modul [`aspose.cells`](..)
