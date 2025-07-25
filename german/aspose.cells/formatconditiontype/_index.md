---
title: FormatConditionType Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 2110
url: /de/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType Aufzählung
Regeltyp für bedingtes Format.



Der Typ FormatConditionType macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| CELL_VALUE | Diese Regel der bedingten Formatierung vergleicht einen Zellwert<br/> zu einem durch eine Formel berechneten Ergebnis, unter Verwendung eines Operators.|
| EXPRESSION | Diese Regel für die bedingte Formatierung enthält eine Formel zum<br/>auswerten. Wenn das Formelergebnis wahr ist, wird die Zelle<br/> hervorgehoben.|
| TOP10 | Diese Regel der bedingten Formatierung hebt Zellen hervor, deren<br/>Werte fallen in die obere N- oder untere N-Klammer, wie<br/> angegeben.|
| UNIQUE_VALUES | Diese Regel der bedingten Formatierung hebt einzigartige<br/> Werte im Bereich.|
| DUPLICATE_VALUES | Diese Regel der bedingten Formatierung hebt doppelte<br/> Werte.|
| CONTAINS_TEXT | Diese Regel der bedingten Formatierung hebt Zellen hervor<br/>enthält den angegebenen Text. Entspricht der Verwendung von SEARCH()<br/>Blattfunktion, um festzustellen, ob die Zelle enthält<br/> der Text.|
| NOT_CONTAINS_TEXT | Diese Regel der bedingten Formatierung hebt Zellen hervor, die<br/>enthalten keinen angegebenen Text. Entspricht der Verwendung von SEARCH()<br/>Blattfunktion, um festzustellen, ob die Zelle enthält<br/> den Text oder nicht.|
| BEGINS_WITH | Diese Regel für die bedingte Formatierung hebt Zellen in der<br/>Bereich, der mit dem angegebenen Text beginnt. Äquivalent zu<br/> Verwenden der Tabellenfunktion LEFT() und Vergleichen von Werten.|
| ENDS_WITH | Diese Regel der bedingten Formatierung hebt Zellen hervor, die enden<br/>mit gegebenem Text. Entspricht der Verwendung des RIGHT()-Blattes<br/> Funktion und Wertevergleich.|
| CONTAINS_BLANKS | Diese Regel der bedingten Formatierung hebt Zellen hervor, die<br/>sind komplett leer. Entspricht der Verwendung von LEN(TRIM()).<br/>Das bedeutet, dass, wenn die Zelle nur Zeichen enthält<br/>das TRIM() entfernen würde, dann wird es als leer betrachtet.<br/> Eine leere Zelle wird ebenfalls als leer betrachtet.|
| NOT_CONTAINS_BLANKS | Diese Regel der bedingten Formatierung hebt Zellen hervor, die<br/>sind nicht leer. Entspricht der Verwendung von LEN(TRIM()). Dies<br/>bedeutet, dass, wenn die Zelle nur Zeichen enthält,<br/>TRIM() entfernen würde, dann wird es als leer betrachtet. Ein<br/> Eine leere Zelle wird ebenfalls als leer betrachtet.|
| CONTAINS_ERRORS | Diese Regel für die bedingte Formatierung hebt Zellen mit<br/>Formelfehler. Entspricht der Verwendung von ISERROR() Blatt<br/> Funktion, um festzustellen, ob ein Formelfehler vorliegt.|
| NOT_CONTAINS_ERRORS | Diese Regel der bedingten Formatierung hebt Zellen hervor<br/>ohne Formelfehler. Entspricht der Verwendung von ISERROR()<br/> Blattfunktion, um festzustellen, ob ein Formelfehler vorliegt.|
| TIME_PERIOD | Diese Regel der bedingten Formatierung hebt Zellen hervor<br/>mit Daten im angegebenen Zeitraum. Die<br/>Der zugrunde liegende Wert der Zelle wird ausgewertet, daher<br/>Zelle muss nicht als Datum formatiert sein, um<br/>ausgewertet. Beispielsweise mit einer Zelle, die die<br/>Wert 38913 Das bedingte Format wird angewendet, wenn<br/> die Regel erfordert einen Wert vom 14.07.2006.|
| ABOVE_AVERAGE | Diese Regel der bedingten Formatierung hebt Zellen hervor, die<br/>liegen über oder unter dem Durchschnitt aller Werte in der<br/> Reichweite.|
| COLOR_SCALE | Diese Regel der bedingten Formatierung erzeugt eine abgestufte<br/> Farbskala auf den Zellen.|
| DATA_BAR | Diese Regel zur bedingten Formatierung zeigt eine abgestufte<br/> Datenbalken im Zellbereich.|
| ICON_SET |Diese Regel für die bedingte Formatierung wendet Symbole auf Zellen an<br/> entsprechend ihren Werten.|



###  Siehe auch
* Modul [`aspose.cells`](..)
