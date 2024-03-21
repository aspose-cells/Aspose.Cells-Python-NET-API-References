---
title: AbstractCalculationEngine Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine Klasse
Stellt die benutzerdefinierte Berechnungs-Engine des Benutzers dar, um die Standard-Berechnungs-Engine von Aspose.Cells zu erweitern.



Der Typ AbstractCalculationEngine macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_param_literal_required](/cells/python-net/de/aspose.cells/abstractcalculationengine/is_param_literal_required) |Gibt an, ob diese Engine während der Berechnung den Literaltext des Parameters benötigt. Der Standardwert ist falsch.|
| [is_param_array_mode_required](/cells/python-net/de/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Gibt an, ob diese Engine die Berechnung des Parameters im Array-Modus benötigt. Der Standardwert ist falsch.<br/>Wenn bei der Berechnung des Zolls [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/de/aspose.cells/calculationdata/get_param_value_in_array_mode) erforderlich ist<br/>Funktionen und der Benutzer hat die Definition für sie nicht aktualisiert<br/>(von [`Workbook.update_custom_function_definition`](/cells/python-net/de/aspose.cells/workbook/update_custom_function_definition)),<br/> Diese Eigenschaft muss auf „true“ gesetzt werden.|
| [process_built_in_functions](/cells/python-net/de/aspose.cells/abstractcalculationengine/process_built_in_functions) | Ob integrierte Funktionen, die von der integrierten Engine unterstützt wurden<br/>sollten von dieser Implementierung überprüft und verarbeitet werden.<br/> Der Standardwert ist falsch.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [calculate](/cells/python-net/de/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Berechnet eine Funktion mit gegebenen Daten.|



###  Bemerkungen

Der Benutzer sollte in dieser Implementierung keinen Teil der Arbeitsmappe direkt ändern (außer
das berechnete Ergebnis der benutzerdefinierten Funktion, das durch die Eigenschaft CalculationData.CalculatedValue festgelegt werden kann.
Andernfalls kann es zu unerwarteten Ergebnissen oder Ausnahmen kommen.
Wenn der Benutzer bei der Implementierung einiger benutzerdefinierter Funktionen andere Daten als das berechnete Ergebnis ändern muss,
Ändern Sie beispielsweise die Formel, den Stil usw. der Zelle usw. Der Benutzer sollte diese Daten in dieser Implementierung erfassen
und ändern Sie sie außerhalb des Rahmens der Formelberechnung.

###  Siehe auch
* Modul [`aspose.cells`](..)
