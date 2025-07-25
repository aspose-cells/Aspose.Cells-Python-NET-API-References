---
title: ReConnectionMethodType Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 130
url: /de/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
##  ReConnectionMethodType Aufzählung
Gibt an, was die Tabellenkalkulationsanwendung tun soll, wenn eine Verbindung fehlschlägt.



Der Typ ReConnectionMethodType macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| REQUIRED | Beim Aktualisieren werden die vorhandenen Verbindungsinformationen verwendet. Wenn diese ungültig sind,<br/> Rufen Sie dann aktualisierte Verbindungsinformationen ab, sofern diese aus der externen Verbindungsdatei verfügbar sind.|
| ALWAYS | Bei jeder Aktualisierung werden die Verbindungsinformationen aus der externen Verbindungsdatei aktualisiert.<br/> falls verfügbar, und verwenden Sie diese anstelle der vorhandenen Verbindungsinformationen.<br/>In diesem Fall schlägt die Datenaktualisierung fehl, wenn die externe Verbindungsdatei nicht verfügbar ist.|
| NEVER | Holen Sie sich niemals aktualisierte Verbindungsinformationen aus der externen Verbindungsdatei<br/> auch wenn es verfügbar ist und auch wenn die vorhandenen Verbindungsinformationen ungültig sind|



###  Siehe auch
* Modul [`aspose.cells.externalconnections`](..)
