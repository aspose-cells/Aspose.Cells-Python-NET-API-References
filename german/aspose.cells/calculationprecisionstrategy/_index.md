---
title: CalculationPrecisionStrategy Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1790
url: /de/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy Aufzählung
Listet Strategien für den Umgang mit Berechnungsgenauigkeit auf.
Aufgrund des Präzisionsproblems der Gleitkommaarithmetik nach IEEE 754 werden einige „scheinbar einfache“ Formeln möglicherweise nicht mit dem erwarteten Ergebnis berechnet.
Wie beispielsweise bei der Formel "=-0,45+0,43+0,02", wenn Operanden direkt mit dem Operator '+' berechnet werden, ist das Ergebnis ungleich Null. Bei solchen Genauigkeitsproblemen
Einige spezielle Strategien können möglicherweise das erwartete Ergebnis liefern.



Der Typ CalculationPrecisionStrategy macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| NONE | Bei der Berechnung wurde keine Strategie angewendet.<br/>Verwenden Sie bei der Berechnung einfach den ursprünglichen Double-Wert als Operand und geben Sie das Ergebnis direkt zurück.<br/> Am effizientesten für die Leistung und in den meisten Fällen anwendbar.|
| ROUND | Rundet das Berechnungsergebnis entsprechend der signifikanten Ziffern.|
| DECIMAL | Verwendet wenn möglich Dezimalzahlen als Operanden.<br/> Für die Leistung am ineffizientesten.|



###  Siehe auch
* Modul [`aspose.cells`](..)
