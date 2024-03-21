---
title: CalculationPrecisionStrategy Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1890
url: /de/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy Aufzählung
Listet Strategien für den Umgang mit der Berechnungsgenauigkeit auf.
Aufgrund des Präzisionsproblems der IEEE 754-Gleitkomma-Arithmetik werden einige „scheinbar einfache“ Formeln möglicherweise nicht als erwartetes Ergebnis berechnet.
Wenn beispielsweise die Formel „=-0,45+0,43+0,02“ den Operanden direkt mit dem „+“-Operator berechnet, ist das Ergebnis nicht Null. Für eine solche Präzisionsfrage:
Einige spezielle Strategien können zum erwarteten Ergebnis führen.



Der Typ CalculationPrecisionStrategy macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| NONE | Bei der Berechnung wurde keine Strategie angewendet.<br/>Verwenden Sie bei der Berechnung einfach den ursprünglichen Double-Wert als Operanden und geben Sie das Ergebnis direkt zurück.<br/> Am effizientesten für die Leistung und für die meisten Fälle anwendbar.|
| ROUND | Rundet das Berechnungsergebnis entsprechend den signifikanten Stellen.|
| DECIMAL |Verwendet nach Möglichkeit Dezimalzahlen als Operanden.<br/> Am ineffizientesten für die Leistung.|



###  Siehe auch
* Modul [`aspose.cells`](..)
