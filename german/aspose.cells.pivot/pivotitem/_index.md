---
title: PivotItem Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 180
url: /de/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem Klasse
Stellt ein Element in einem PivotField-Bericht dar.



Der Typ PivotItem macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_hidden](/cells/python-net/de/aspose.cells.pivot/pivotitem/is_hidden) | Ruft ab und legt fest, ob das Pivot-Element ausgeblendet ist.|
| [position](/cells/python-net/de/aspose.cells.pivot/pivotitem/position) | Angeben des Positionsindex in allen PivotItems, nicht in den PivotItems unter demselben übergeordneten Knoten.|
| [position_in_same_parent_node](/cells/python-net/de/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Angeben des Positionsindex in den PivotItems unter demselben übergeordneten Knoten.|
| [is_hide_detail](/cells/python-net/de/aspose.cells.pivot/pivotitem/is_hide_detail) | Ruft ab und legt fest, ob das Pivot-Element Details ausblendet.|
| [is_detail_hidden](/cells/python-net/de/aspose.cells.pivot/pivotitem/is_detail_hidden) |Ruft ab und legt fest, ob die Details dieses Pivot-Elements ausgeblendet sind.|
| [is_calculated_item](/cells/python-net/de/aspose.cells.pivot/pivotitem/is_calculated_item) | Gibt an, ob dieses Pivot-Element ein berechnetes Formelelement ist.|
| [is_formula](/cells/python-net/de/aspose.cells.pivot/pivotitem/is_formula) | Gibt an, ob dieses Pivot-Element ein berechnetes Formelelement ist.|
| [is_missing](/cells/python-net/de/aspose.cells.pivot/pivotitem/is_missing) | Gibt an, ob das Element aus der Datenquelle entfernt wurde.|
| [value](/cells/python-net/de/aspose.cells.pivot/pivotitem/value) | Ruft den Wert des Pivot-Elements ab|
| [name](/cells/python-net/de/aspose.cells.pivot/pivotitem/name) | Ruft den Namen des Pivot-Elements ab.|
| [index](/cells/python-net/de/aspose.cells.pivot/pivotitem/index) | Ruft den Index des Pivot-Elements im Cache-Feld ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/de/aspose.cells.pivot/pivotitem/move/#int-bool) | Verschiebt das Element nach oben oder unten|
| [`get_formula(self)`](/cells/python-net/de/aspose.cells.pivot/pivotitem/get_formula/#) | Ruft die Formel dieses berechneten Elements ab.<br/> Funktioniert nur, wenn dieser Artikel ein berechneter Artikel ist.|
| [`get_string_value(self)`](/cells/python-net/de/aspose.cells.pivot/pivotitem/get_string_value/#) | Ruft den Stringwert des Pivot-Elements ab<br/> Wenn der Wert null ist, wird "" zurückgegeben.|
| [`get_double_value(self)`](/cells/python-net/de/aspose.cells.pivot/pivotitem/get_double_value/#) | Ruft den doppelten Wert des Pivot-Elements ab<br/> Wenn der Wert null oder keine Zahl ist, wird 0 zurückgegeben.|
| [`get_date_time_value(self)`](/cells/python-net/de/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Ruft den Datums-/Uhrzeitwert des Pivot-Elements ab<br/> Wenn der Wert null ist, wird DateTime.MinValue zurückgegeben.|



###  Siehe auch
* Modul [`aspose.cells.pivot`](..)
