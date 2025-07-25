---
title: CalculationData klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells/calculationdata/
is_root: false
---
##  CalculationData klass
Representerar de data som krävs vid beräkning av en funktion, såsom funktionsnamn, parametrar, ... etc.



Typen CalculationData avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [calculated_value](/cells/python-net/sv/aspose.cells/calculationdata/calculated_value) | Hämtar eller ställer in det beräknade värdet för den här funktionen.|
| [workbook](/cells/python-net/sv/aspose.cells/calculationdata/workbook) | Hämtar arbetsboksobjektet där funktionen finns.|
| [worksheet](/cells/python-net/sv/aspose.cells/calculationdata/worksheet) | Hämtar arbetsbladsobjektet där funktionen finns.|
| [cell_row](/cells/python-net/sv/aspose.cells/calculationdata/cell_row) | Hämtar radindexet för cellen där funktionen finns.|
| [cell_column](/cells/python-net/sv/aspose.cells/calculationdata/cell_column) | Hämtar kolumnindexet för cellen där funktionen finns.|
| [cell](/cells/python-net/sv/aspose.cells/calculationdata/cell) |Hämtar Cell-objektet där funktionen finns.|
| [function_name](/cells/python-net/sv/aspose.cells/calculationdata/function_name) | Hämtar funktionsnamnet som ska beräknas.|
| [param_count](/cells/python-net/sv/aspose.cells/calculationdata/param_count) | Hämtar antalet parametrar|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_param_value(self, index)`](/cells/python-net/sv/aspose.cells/calculationdata/get_param_value/#int) |Hämtar det representerade värdeobjektet för parametern vid ett givet index.|
| [`get_param_value_in_array_mode(self, index, max_row_count, max_column_count)`](/cells/python-net/sv/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | Hämtar värdet/värdena för parametern vid givet index.<br/>Om parametern är någon form av uttryck som behöver beräknas,<br/> då kommer den att beräknas i arrayläge.|
| [`get_param_text(self, index)`](/cells/python-net/sv/aspose.cells/calculationdata/get_param_text/#int) | Hämtar den bokstavliga texten för parametern vid ett givet index.|



###  Anmärkningar

Alla objekt som tillhandahålls av denna klass är endast för "läs" syfte.
Användaren ska inte ändra några data i arbetsboken under formelberäkningsprocessen,
Annars kan oväntade resultat eller undantag orsakas.

###  Se även
* modul [`aspose.cells`](..)
