---
title: LightCellsDataProvider klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1040
url: /sv/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider klass
Representerar dataleverantör för att spara stora kalkylbladsfiler i lättviktsläge.



Typen LightCellsDataProvider avslöjar följande medlemmar:

###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [start_sheet](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Börjar spara ett kalkylblad.|
| [next_row](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/next_row/#) | Hämtar nästa rad som ska sparas.|
| [start_row](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Börjar spara data på en rad.|
| [next_cell](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/next_cell/#) | Hämtar nästa cell som ska sparas.|
| [start_cell](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Börjar spara data för en cell.|
| [is_gather_string](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Kontrollerar om det aktuella strängvärdet för cellen måste samlas in i en global pool.|



###  Anmärkningar

När du sparar en arbetsbok med det här läget, kommer [`LightCellsDataProvider.start_sheet`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_sheet) att kontrolleras när du sparar varje kalkylblad i arbetsboken.
För ett ark, om [`LightCellsDataProvider.start_sheet`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_sheet) ger sant, ska alla data och egenskaper sparas för rader/celler i detta ark
kommer att tillhandahållas av implementeringen av detta gränssnitt.
I första hand kommer [`LightCellsDataProvider.next_row`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/next_row) att anropas för att få nästa radindex som ska sparas.
Om ett giltigt radindex returneras (radindexet måste vara i stigande ordning för att raderna ska sparas),
sedan kommer ett Row-objekt som representerar denna rad att tillhandahållas av [`LightCellsDataProvider.start_row`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_row) för implementeringen för att ställa in dess egenskaper.
För en rad kommer [`LightCellsDataProvider.next_cell`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/next_cell) att kontrolleras först.
Om ett giltigt kolumnindex returneras (kolumnindexet måste vara i stigande ordning för alla celler i den aktuella raden),
sedan kommer ett Cell-objekt som representerar denna cell att tillhandahållas av [`LightCellsDataProvider.start_cell`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_cell) för implementering för att ställa in dess data och egenskaper.
Efter [`LightCellsDataProvider.start_cell`](/cells/python-net/sv/aspose.cells/lightcellsdataprovider/start_cell) kommer cellen att sparas direkt i den resulterande kalkylarksfilen.
Därefter kommer nästa cell att kontrolleras och bearbetas.


Observera att användaren endast ska uppdatera värden och egenskaper för det aktuella objektet Row/Cell som tillhandahålls med motsvarande metod.
Eftersom celldata skrivs till den resulterande filen på ett strömmande sätt, kan de flesta andra objekt ha skrivits
till den resulterande filen, eller har samlats in och skrivits några globala data för dem. Så när användaren uppdaterar andra objekt
medan du sparar celldata, kanske dessa operationer inte kan påverka den sparade informationen. Eller ännu värre, dessa operationer kan
orsaka att inkonsekventa data sparas till den resulterande filen och slutligen göra filen skadad.
Så för alla andra objekt som former, kolumnbredd och stilar, villkorliga formateringar, ... etc.,
använd dem inte i några metoder för denna implementering.
Hantera dem istället och justera dem till det slutliga tillståndet innan du anropar "Spara"-metoden i arbetsboken.

###  Se även
* modul [`aspose.cells`](..)
