---
title: get_dependents Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
Holen Sie sich alle Zellen, deren Formel direkt auf diese Zelle verweist.



```python

def get_dependents(self, is_all):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| is_all | bool |Gibt an, ob Prüfformeln in anderen Arbeitsblättern|
###  Bemerkungen

* Wenn eine Referenz, die diese Zelle enthält, in der Formel einer Zelle erscheint, wird diese Zelle als

die Abhängigkeit dieser Zelle, unabhängig davon, ob die Referenz oder diese Zelle während der Berechnung verwendet wird oder nicht.
Obwohl beispielsweise die Zelle A2 in der Formel "=WENN(WAHR;A1;A2)" bei der Berechnung nicht verwendet wird,
Diese Formel ist immer noch als von A2 abhängig anzusehen.
Um die Formeln zu erhalten, deren berechnete Ergebnisse von dieser Zelle abhängen, verwenden Sie bitte [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation). Beim Aufspüren abhängiger Ergebnisse für eine Zelle werden alle Formeln in der Arbeitsmappe oder dem Arbeitsblatt analysiert und überprüft.
Es handelt sich also um einen zeitaufwändigen Prozess. Wenn der Benutzer abhängige Elemente für viele Zellen verfolgen muss, wird diese Methode
kann zu Leistungseinbußen führen. Aus Leistungsgründen sollte der Benutzer stattdessen [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation) verwenden.
Oder der Benutzer kann zunächst eine Präzedenzfallkarte aller Zellen von [`Cell.get_precedents`](/cells/python-net/de/aspose.cells/cell/get_precedents) sammeln,
und erstellen Sie dann die Abhängigkeitskarte entsprechend der Präzedenzfallkarte.

* Wenn eine Referenz, die diese Zelle enthält, in der Formel einer Zelle erscheint, wird diese Zelle als
die Abhängigkeit dieser Zelle, unabhängig davon, ob die Referenz oder diese Zelle während der Berechnung verwendet wird oder nicht.
Obwohl beispielsweise die Zelle A2 in der Formel "=WENN(WAHR;A1;A2)" bei der Berechnung nicht verwendet wird,
Diese Formel ist immer noch als von A2 abhängig anzusehen.
Um die Formeln zu erhalten, deren berechnete Ergebnisse von dieser Zelle abhängen, verwenden Sie bitte [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation). Beim Aufspüren abhängiger Ergebnisse für eine Zelle werden alle Formeln in der Arbeitsmappe oder dem Arbeitsblatt analysiert und überprüft.
Es handelt sich also um einen zeitaufwändigen Prozess. Wenn der Benutzer abhängige Elemente für viele Zellen verfolgen muss, wird diese Methode
kann zu Leistungseinbußen führen. Aus Leistungsgründen sollte der Benutzer stattdessen [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation) verwenden.
Oder der Benutzer kann zunächst eine Präzedenzfallkarte aller Zellen von [`Cell.get_precedents`](/cells/python-net/de/aspose.cells/cell/get_precedents) sammeln,
und erstellen Sie dann die Abhängigkeitskarte entsprechend der Präzedenzfallkarte.

* Wenn eine Referenz, die diese Zelle enthält, in der Formel einer Zelle erscheint, wird diese Zelle als
die Abhängigkeit dieser Zelle, unabhängig davon, ob die Referenz oder diese Zelle während der Berechnung verwendet wird oder nicht.
Obwohl beispielsweise die Zelle A2 in der Formel "=WENN(WAHR;A1;A2)" bei der Berechnung nicht verwendet wird,
Diese Formel ist immer noch als von A2 abhängig anzusehen.
Um die Formeln zu erhalten, deren berechnete Ergebnisse von dieser Zelle abhängen, verwenden Sie bitte [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation). Beim Aufspüren abhängiger Ergebnisse für eine Zelle werden alle Formeln in der Arbeitsmappe oder dem Arbeitsblatt analysiert und überprüft.
Es handelt sich also um einen zeitaufwändigen Prozess. Wenn der Benutzer abhängige Elemente für viele Zellen verfolgen muss, wird diese Methode
kann zu Leistungseinbußen führen. Aus Leistungsgründen sollte der Benutzer stattdessen [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation) verwenden.
Oder der Benutzer kann zunächst eine Präzedenzfallkarte aller Zellen von [`Cell.get_precedents`](/cells/python-net/de/aspose.cells/cell/get_precedents) sammeln,
und erstellen Sie dann die Abhängigkeitskarte entsprechend der Präzedenzfallkarte.
###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
