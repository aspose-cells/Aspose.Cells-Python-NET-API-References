---
title: FormatConditionType Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 2170
url: /de/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType Aufzählung
Regeltyp für bedingtes Format.



Der Typ FormatConditionType macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| CELL_VALUE | Diese bedingte Formatierungsregel vergleicht einen Zellenwert<br/> mithilfe eines Operators in ein mit einer Formel berechnetes Ergebnis umwandeln.|
| EXPRESSION | Diese bedingte Formatierungsregel enthält eine Formel für<br/>auswerten. Wenn das Formelergebnis wahr ist, ist die Zelle wahr<br/> hervorgehoben.|
| TOP10 | Diese bedingte Formatierungsregel hebt Zellen hervor, deren<br/>Werte fallen in die obere N- oder untere N-Klammer, als<br/> angegeben.|
| UNIQUE_VALUES |Diese bedingte Formatierungsregel hebt Einzigartigkeit hervor<br/> Werte im Bereich.|
| DUPLICATE_VALUES | Diese bedingte Formatierungsregel hebt Duplikate hervor<br/> Werte.|
| CONTAINS_TEXT | Diese bedingte Formatierungsregel hebt Zellen hervor<br/>enthält den angegebenen Text. Entspricht der Verwendung von SEARCH()<br/>Sheet-Funktion, um zu bestimmen, ob die Zelle enthält<br/> der Text.|
| NOT_CONTAINS_TEXT | Diese bedingte Formatierungsregel hebt Zellen hervor, die<br/>enthalten keinen vorgegebenen Text. Äquivalent zur Verwendung von SEARCH()<br/>Sheet-Funktion, um zu bestimmen, ob die Zelle enthält<br/> der Text oder nicht.|
| BEGINS_WITH | Diese bedingte Formatierungsregel hebt Zellen in hervor<br/>Bereich, der mit dem angegebenen Text beginnt. Gleichwertig<br/> Verwenden der Blattfunktion LEFT() und Vergleichen von Werten.|
| ENDS_WITH | Diese bedingte Formatierungsregel hebt Zellenenden hervor<br/>mit vorgegebenem Text. Entspricht der Verwendung des RIGHT()-Blatts<br/> Funktion und Vergleich von Werten.|
| CONTAINS_BLANKS | Diese bedingte Formatierungsregel hebt Zellen hervor, die<br/>sind völlig leer. Entspricht der Verwendung von LEN(TRIM()).<br/>Dies bedeutet, dass die Zelle nur Zeichen enthält<br/>dass TRIM() entfernen würde, dann wird es als leer betrachtet.<br/> Eine leere Zelle gilt ebenfalls als leer.|
| NOT_CONTAINS_BLANKS | Diese bedingte Formatierungsregel hebt Zellen hervor, die<br/>sind nicht leer. Entspricht der Verwendung von LEN(TRIM()). Das<br/>bedeutet, dass, wenn die Zelle nur Zeichen enthält, das<br/>Wenn TRIM() entfernt wird, gilt es als leer. Ein<br/> Eine leere Zelle gilt ebenfalls als leer.|
| CONTAINS_ERRORS | Diese bedingte Formatierungsregel hebt Zellen mit hervor<br/>Formelfehler. Entspricht der Verwendung des ISERROR()-Blatts<br/> Funktion, um festzustellen, ob ein Formelfehler vorliegt.|
| NOT_CONTAINS_ERRORS | Diese bedingte Formatierungsregel hebt Zellen hervor<br/>ohne Formelfehler. Entspricht der Verwendung von ISERROR()<br/> Tabellenfunktion, um festzustellen, ob ein Formelfehler vorliegt.|
| TIME_PERIOD | Diese bedingte Formatierungsregel hebt Zellen hervor<br/>Enthält Daten im angegebenen Zeitraum. Der<br/>Der zugrunde liegende Wert der Zelle wird ausgewertet, also der<br/>Die Zelle muss dafür nicht als Datum formatiert werden<br/>ausgewertet. Zum Beispiel mit einer Zelle, die das enthält<br/>Wert 38913 Das bedingte Format soll angewendet werden, wenn<br/> Die Regel erfordert einen Wert vom 14.07.2006.|
| ABOVE_AVERAGE | Diese bedingte Formatierungsregel hebt Zellen hervor, die<br/>liegen über oder unter dem Durchschnitt aller Werte im<br/> Reichweite.|
| COLOR_SCALE | Diese bedingte Formatierungsregel erstellt eine abgestufte<br/> Farbskala auf den Zellen.|
| DATA_BAR | Diese bedingte Formatierungsregel zeigt eine abgestufte Darstellung an<br/> Datenleiste im Zellbereich.|
| ICON_SET | Diese bedingte Formatierungsregel wendet Symbole auf Zellen an<br/> nach ihren Werten.|



###  Siehe auch
* Modul [`aspose.cells`](..)
