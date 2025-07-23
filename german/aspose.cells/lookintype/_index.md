---
title: LookInType Aufzählung
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 2270
url: /de/aspose.cells/lookintype/
is_root: false
---
##  LookInType Aufzählung
Stellt das Aussehen im Typ dar.



Der Typ LookInType macht die folgenden Member verfügbar:

###  Felder
| Feld| Beschreibung|
| :- | :- |
| FORMULAS | Findet das gesuchte Objekt aus der Formel ([`Cell.formula`](/cells/python-net/de/aspose.cells/cell#formula)), wenn die Zelle eine Formel ist.<br/>andernfalls wird der ursprüngliche Wert der Zelle ermittelt (dasselbe wie bei [`LookInType.ORIGINAL_VALUES`](/cells/python-net/de/aspose.cells/lookintype#ORIGINAL_VALUES)).|
| VALUES | Findet Objekt aus dem ursprünglichen Wert der Zelle ([`Cell.value`](/cells/python-net/de/aspose.cells/cell#value))<br/> und formatierter Wert ([`Cell.string_value`](/cells/python-net/de/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Ignoriert Formelzellen. Für Zellen ohne Formeln gilt:<br/> es ist dasselbe mit [`LookInType.VALUES`](/cells/python-net/de/aspose.cells/lookintype#VALUES).|
| COMMENTS | Sucht nur nach Objekten aus dem Kommentar der Zelle. Ignoriert Zellen ohne Kommentar.|
| ONLY_FORMULAS | Ignoriert Zellen, die keine Formeln sind. Für Zellen, die Formeln sind,<br/> findet das gesuchte Objekt aus der Formel ([`Cell.formula`](/cells/python-net/de/aspose.cells/cell#formula)).|
| ORIGINAL_VALUES | Suchen Sie nur nach Objekten anhand des Originalwerts der Zelle.|
| FORMATTED_VALUES | Suchen Sie nur nach Objekten aus dem formatierten Wert der Zelle ([`Cell.string_value`](/cells/python-net/de/aspose.cells/cell#string_value)).|



###  Siehe auch
* Modul [`aspose.cells`](..)
