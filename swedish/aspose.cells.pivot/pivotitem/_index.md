---
title: PivotItem klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 180
url: /sv/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem klass
Representerar ett objekt i en PivotField-rapport.



Typen PivotItem avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_hidden](/cells/python-net/sv/aspose.cells.pivot/pivotitem/is_hidden) | Hämtar och anger om pivotobjektet är dolt.|
| [position](/cells/python-net/sv/aspose.cells.pivot/pivotitem/position) | Anger positionsindex i alla PivotItems, inte PivotItems under samma överordnade nod.|
| [position_in_same_parent_node](/cells/python-net/sv/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Ange positionsindex i PivotItems under samma överordnade nod.|
| [is_hide_detail](/cells/python-net/sv/aspose.cells.pivot/pivotitem/is_hide_detail) | Hämtar och anger om pivotobjektet döljer detaljer.|
| [is_detail_hidden](/cells/python-net/sv/aspose.cells.pivot/pivotitem/is_detail_hidden) |Hämtar och anger om detaljerna för detta pivotobjekt är dolda.|
| [is_calculated_item](/cells/python-net/sv/aspose.cells.pivot/pivotitem/is_calculated_item) | Anger om detta pivotobjekt är ett beräknat formelobjekt.|
| [is_formula](/cells/python-net/sv/aspose.cells.pivot/pivotitem/is_formula) | Anger om detta pivotobjekt är ett beräknat formelobjekt.|
| [is_missing](/cells/python-net/sv/aspose.cells.pivot/pivotitem/is_missing) | Anger om objektet har tagits bort från datakällan.|
| [value](/cells/python-net/sv/aspose.cells.pivot/pivotitem/value) | Hämtar värdet på pivotobjektet|
| [name](/cells/python-net/sv/aspose.cells.pivot/pivotitem/name) | Hämtar namnet på pivotobjektet.|
| [index](/cells/python-net/sv/aspose.cells.pivot/pivotitem/index) | Hämtar indexet för pivotobjektet i cachefältet.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/sv/aspose.cells.pivot/pivotitem/move/#int-bool) | Flyttar objektet uppåt eller nedåt|
| [`get_formula(self)`](/cells/python-net/sv/aspose.cells.pivot/pivotitem/get_formula/#) | Hämtar formeln för detta beräknade objekt.<br/> Fungerar endast när det här objektet är ett beräknat objekt.|
| [`get_string_value(self)`](/cells/python-net/sv/aspose.cells.pivot/pivotitem/get_string_value/#) | Hämtar strängvärdet för pivotobjektet<br/> Om värdet är null returneras ""|
| [`get_double_value(self)`](/cells/python-net/sv/aspose.cells.pivot/pivotitem/get_double_value/#) | Hämtar det dubbla värdet av pivotobjektet<br/> Om värdet är null eller inte ett tal, returnerar det 0|
| [`get_date_time_value(self)`](/cells/python-net/sv/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Hämtar datum- och tidsvärdet för pivotobjektet<br/> Om värdet är null returneras DateTime.MinValue|



###  Se även
* modul [`aspose.cells.pivot`](..)
