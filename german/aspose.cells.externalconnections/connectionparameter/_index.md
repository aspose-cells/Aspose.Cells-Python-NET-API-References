---
title: ConnectionParameter Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter Klasse
Gibt Eigenschaften zu allen Parametern an, die mit externen Datenverbindungen verwendet werden
Parameter sind für ODBC- und Webabfragen gültig.



Der Typ ConnectionParameter macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [sql_type](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/sql_type) | SQL-Datentyp des Parameters. Nur gültig für ODBC-Quellen.|
| [refresh_on_change](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Flag, das angibt, ob die Abfrage automatisch aktualisiert werden soll, wenn der Inhalt einer<br/> Zelle, die die Parameterwertänderungen bereitstellt. Wenn true, werden externe Daten aktualisiert<br/> mit dem neuen Parameterwert bei jeder Änderung. Wenn false, dann externe Daten<br/> wird nur aktualisiert, wenn dies vom Benutzer angefordert wird oder ein anderes Ereignis die Aktualisierung auslöst (z. B. wenn eine Arbeitsmappe geöffnet wird).|
| [prompt](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/prompt) | Eingabeaufforderung für den Parameter. Wird dem Tabellenkalkulationsbenutzer zusammen mit der Eingabe-Benutzeroberfläche angezeigt.<br/> um den Parameterwert vor der Aktualisierung der externen Daten zu erfassen. Wird nur verwendet, wenn<br/>Parametertyp = Eingabeaufforderung.|
| [type](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/type) | Typ des verwendeten Parameters.<br/> Wenn der Parametertyp = Wert ist, dann ist der Wert von Boolean, Double, Integer,<br/> oder Zeichenfolge verwendet. In diesem Fall wird erwartet, dass nur einer der<br/> Es wird {Boolean, Double, Integer oder String} angegeben.|
| [name](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/name) | Der Name des Parameters.|
| [cell_reference](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/cell_reference) | Cell Referenz, die angibt, welcher Zellenwert für den Abfrageparameter verwendet werden soll. Wird nur verwendet, wenn der Parametertyp „Zelle“ ist.|
| [value](/cells/python-net/de/aspose.cells.externalconnections/connectionparameter/value) | Nicht ganzzahliger numerischer Wert, ganzzahliger Wert, Zeichenfolgenwert oder Boolescher Wert<br/> zur Verwendung als Abfrageparameter. Wird nur verwendet, wenn der Parametertyp „value“ ist.|



###  Siehe auch
* Modul [`aspose.cells.externalconnections`](..)
