---
title: GridAbstractCalculationEngine Klasse
second_title: Aspose.Cells.GridJs for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
##  GridAbstractCalculationEngine Klasse

Stellt die benutzerdefinierte Berechnungs-Engine des Benutzers dar, um die Standard-Berechnungs-Engine von Aspose.Cells zu erweitern.



Der Typ GridAbstractCalculationEngine macht die folgenden Member verfügbar:

###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [calculate](/cells/python-net/de/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) | Berechnet eine Funktion mit gegebenen Daten.|



###  Bemerkungen


Der Benutzer sollte in dieser Implementierung keinen Teil der Arbeitsmappe direkt ändern (mit Ausnahme des berechneten Ergebnisses der benutzerdefinierten Funktion, das durch die Eigenschaft „GridCalculationData.CalculatedValue“ festgelegt werden kann).
Andernfalls kann es zu unerwarteten Ergebnissen oder Ausnahmen kommen.
Wenn der Benutzer bei der Implementierung einiger benutzerdefinierter Funktionen andere Daten als das berechnete Ergebnis ändern muss,
Wenn Sie beispielsweise die Formel, den Stil usw. einer Zelle ändern, sollte der Benutzer diese Daten in dieser Implementierung sammeln und sie außerhalb des Bereichs der Formelberechnung ändern.

###  Siehe auch
* Modul [`aspose.cellsgridjs`](..)
