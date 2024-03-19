---
title: AccessCacheOptions Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1810
url: /de/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions Aufzählung
Cache-Optionen für den Datenzugriff. Kombinierbar mit | Operator für mehrere Optionen zusammen.



Der Typ AccessCacheOptions macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| NONE | Kein Cache für jeglichen Datenzugriff.|
| ALL | Wenden Sie alle möglichen Optimierungen für alle Arten des Datenzugriffs in der Arbeitsmappe an.<br/> Sämtliche Einstellungen und Daten sollten während des optimierten Zugriffs nicht verändert werden.|
| POSITION_AND_SIZE |Wenden Sie eine mögliche Optimierung an, um die Position und Größe des Objekts (z. B. Form) zu ermitteln.<br/> Die Einstellungen für Zeilenhöhe und Spaltenbreite sollten während des optimierten Zugriffs nicht geändert werden.|
| CELLS_DATA | Wenden Sie eine mögliche Optimierung an, um die Werte der Zellen zu erhalten.<br/>Cells-Daten (Daten und Einstellungen von Cell, Zeile) sollten währenddessen nicht geändert werden<br/>Durch den optimierten Zugriff sollten auch keine neuen Cell/Row-Objekte erstellt werden (z. B<br/> von [Indexer]).|
| CELL_DISPLAY | Wenden Sie eine mögliche Optimierung an, um anzeigebezogene Ergebnisse zu erhalten<br/>Zellen ([`Cell.display_string_value`](/cells/python-net/de/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/de/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style) usw.).<br/>Cells Daten und stilbezogene Objekte (Cell/Zeilen-/Spaltenstile, Spaltenbreite usw.) sollten nicht geändert werden<br/> während des optimierten Zugriffs.|
| GET_FORMULA | Wenden Sie mögliche Optimierungen zum Erhalten von Formeln an.<br/>Alle Daten und Einstellungen, die sich auf den Formelausdruck auswirken können (Name des Arbeitsblatts, Text des Namens,<br/> Tabellenspalte usw.) sollten während des optimierten Zugriffs nicht geändert werden.|
| SET_FORMULA |Wenden Sie mögliche Optimierungen für die Einstellung von Formeln an.<br/>Alle Daten und Einstellungen, die sich auf den Formelausdruck auswirken können (Name des Arbeitsblatts, Text des Namens,<br/> Tabellenspalte usw.) sollten während des optimierten Zugriffs nicht geändert werden.|
| CALCULATE_FORMULA | Wenden Sie mögliche Optimierungen für die Berechnungsformeln an.<br/>Cells Daten sollten während des optimierten Zugriffs nicht geändert werden, keine neuen Objekte (Cell, Zeile usw.)<br/> sollte entweder erstellt werden (z. B. durch [Indexer]).|
| CONDITIONAL_FORMATTING | Wenden Sie eine mögliche Optimierung an, um das Formatierungsergebnis bedingter Formatierungen zu erhalten.<br/>Alle Daten und Einstellungen, die das Ergebnis bedingter Formatierungen beeinflussen können (Einstellungen von<br/> bedingte Formatierungen, abhängige Zellwerte usw.) sollten während des optimierten Zugriffs nicht geändert werden.|
| VALIDATION | Wenden Sie eine mögliche Optimierung an, um das Validierungsergebnis zu erhalten.<br/>Alle Daten und Einstellungen, die das Ergebnis der Validierung beeinflussen können (Einstellungen der Validierung,<br/> abhängige Zellwerte usw.) sollten während des optimierten Zugriffs nicht geändert werden.|



###  Bemerkungen

Bei einigen Funktionen erfordert der Zugriff auf große Datenmengen viele wiederholte und komplizierte Vorgänge
B. Suche, Berechnung usw., und diese Vorgänge nehmen viel zusätzliche Zeit in Anspruch.
In häufigen Situationen bleiben alle abhängigen Daten während des Zugriffs unverändert, sodass einige Caches erstellt und verwendet werden können
Verbesserung der Zugriffsleistung.
Zu diesem Zweck stellen wir diese API zur Verfügung, damit der Benutzer angeben kann, welche Art von Datenzugriff er benötigt
durch einen möglichen Caching-Mechanismus optimiert werden.


Bitte beachten Sie, dass für verschiedene Optionen möglicherweise unterschiedliche Datensätze „schreibgeschützt“ sein müssen.
Und die Leistung des Datenzugriffs hängt von vielen Aspekten ab, der Verwendung des Caching-Mechanismus
garantiert nicht, dass die Leistung verbessert wird. Für einige Situationen,
Da der Datensatz, auf den zugegriffen werden soll, klein ist, kann die Verwendung des Caches noch mehr Zeit in Anspruch nehmen
Auch das Caching selbst erfordert eine gewisse zusätzliche Zeit.

###  Siehe auch
* Modul [`aspose.cells`](..)
