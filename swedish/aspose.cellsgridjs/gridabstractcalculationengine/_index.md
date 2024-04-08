---
title: GridAbstractCalculationEngine klass
second_title: Aspose.Cells.GridJs for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
##  GridAbstractCalculationEngine klass

Representerar användarens anpassade beräkningsmotor för att utöka standardberäkningsmotorn Aspose.Cells.



Typen GridAbstractCalculationEngine avslöjar följande medlemmar:

###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [calculate](/cells/python-net/sv/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) | Beräknar en funktion med givna data.|



###  Anmärkningar


Användaren ska inte modifiera någon del av arbetsboken direkt i den här implementeringen (förutom det beräknade resultatet av den anpassade funktionen, som kan ställas in av egenskapen GridCalculationData.CalculatedValue).
Annars kan oväntade resultat eller undantag orsakas.
Om användaren behöver ändra andra data än det beräknade resultatet i implementeringen av vissa anpassade funktioner,
Till exempel, ändra cells formel, stil, ... etc., användaren ska samla in dessa data i den här implementeringen och ändra dem utanför ramen för formelberäkningen.

###  Se även
* modul [`aspose.cellsgridjs`](..)
