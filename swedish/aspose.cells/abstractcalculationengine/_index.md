---
title: AbstractCalculationEngine klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine klass
Representerar användarens anpassade beräkningsmotor för att utöka standardberäkningsmotorn Aspose.Cells.



Typen AbstractCalculationEngine avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_param_literal_required](/cells/python-net/sv/aspose.cells/abstractcalculationengine/is_param_literal_required) |Indikerar om denna motor behöver den bokstavliga texten av parametern när den gör beräkningar. Standardvärdet är falskt.|
| [is_param_array_mode_required](/cells/python-net/sv/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Indikerar om denna motor behöver parametern för att beräknas i arrayläge. Standardvärdet är falskt.<br/>Om [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/sv/aspose.cells/calculationdata/get_param_value_in_array_mode) krävs vid beräkning av custom<br/>funktioner och användaren har inte uppdaterat definitionen för dem<br/>(av [`Workbook.update_custom_function_definition`](/cells/python-net/sv/aspose.cells/workbook/update_custom_function_definition)),<br/> den här egenskapen måste anges som sann.|
| [process_built_in_functions](/cells/python-net/sv/aspose.cells/abstractcalculationengine/process_built_in_functions) | Oavsett om inbyggda funktioner som har stöds av den inbyggda motorn<br/>bör kontrolleras och bearbetas av denna implementering.<br/> Standard är falskt.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [calculate](/cells/python-net/sv/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Beräknar en funktion med givna data.|



###  Anmärkningar

Användaren ska inte ändra någon del av arbetsboken direkt i den här implementeringen (förutom
det beräknade resultatet av den anpassade funktionen, som kan ställas in med egenskapen CalculationData.CalculatedValue).
Annars kan oväntade resultat eller undantag orsakas.
Om användaren behöver ändra andra data än det beräknade resultatet i implementeringen av vissa anpassade funktioner,
till exempel ändra cells formel, stil, ... etc., användaren ska samla in dessa data i den här implementeringen
och ändra dem utanför ramen för formelberäkningen.

###  Se även
* modul [`aspose.cells`](..)
