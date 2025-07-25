---
title: PivotFilterCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 150
url: /sv/aspose.cells.pivot/pivotfiltercollection/
is_root: false
---
##  PivotFilterCollection klass
Representerar en samling av alla PivotFilter-objekt



Typen PivotFilterCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`add(self, field_index, type)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/add/#int-aspose.cells.pivot.pivotfiltertype) | Lägger till ett PivotFilter-objekt till den specifika typen|
| [`add_top_10_filter(self, base_field_index, value_field_index, type, is_top, item_count)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/add_top_10_filter/#int-int-aspose.cells.pivot.pivotfiltertype-bool-int) | Filtrerar efter värden i datapivotfältet.|
| [`add_value_filter(self, base_field_index, value_field_index, type, value1, value2)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/add_value_filter/#int-int-aspose.cells.pivot.pivotfiltertype-float-float) | Filtrerar efter värden i datapivotfältet.|
| [`add_label_filter(self, base_field_index, type, label1, label2)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/add_label_filter/#int-aspose.cells.pivot.pivotfiltertype-str-str) | Filtrerar efter bildtexter för pivotfält för rad eller kolumn.|
| [`add_date_filter(self, base_field_index, type, date_time1, date_time2)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/add_date_filter/#int-aspose.cells.pivot.pivotfiltertype-datetime-datetime) | Filtrerar efter datuminställning för pivotfält för rad eller kolumn.|
| [`clear_filter(self, field_index)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/clear_filter/#int) | Rensa PivotFilter från det specifika PivotField|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.pivot/pivotfiltercollection/binary_search/#aspose.cells.pivot.pivotfilter) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Se även
* modul [`aspose.cells.pivot`](..)
