---
title: PivotFilterCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 150
url: /de/aspose.cells.pivot/pivotfiltercollection/
is_root: false
---
##  PivotFilterCollection Klasse
Stellt eine Sammlung aller PivotFilter-Objekte dar



Der Typ PivotFilterCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`add(self, field_index, type)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/add/#int-aspose.cells.pivot.pivotfiltertype) | Fügt dem spezifischen Typ ein PivotFilter-Objekt hinzu|
| [`add_top_10_filter(self, base_field_index, value_field_index, type, is_top, item_count)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/add_top_10_filter/#int-int-aspose.cells.pivot.pivotfiltertype-bool-int) | Filtert nach Werten des Daten-Pivotfelds.|
| [`add_value_filter(self, base_field_index, value_field_index, type, value1, value2)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/add_value_filter/#int-int-aspose.cells.pivot.pivotfiltertype-float-float) | Filtert nach Werten des Daten-Pivotfelds.|
| [`add_label_filter(self, base_field_index, type, label1, label2)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/add_label_filter/#int-aspose.cells.pivot.pivotfiltertype-str-str) | Filtert nach Überschriften von Zeilen- oder Spalten-Pivotfeldern.|
| [`add_date_filter(self, base_field_index, type, date_time1, date_time2)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/add_date_filter/#int-aspose.cells.pivot.pivotfiltertype-datetime-datetime) | Filtert nach Datumseinstellung des Zeilen- oder Spalten-Pivotfelds.|
| [`clear_filter(self, field_index)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/clear_filter/#int) | PivotFilter aus dem spezifischen PivotField löschen|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.pivot/pivotfiltercollection/binary_search/#aspose.cells.pivot.pivotfilter) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Siehe auch
* Modul [`aspose.cells.pivot`](..)
