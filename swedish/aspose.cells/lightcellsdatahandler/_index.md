---
title: LightCellsDataHandler klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1030
url: /sv/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler klass
Representerar celldatahanterare för att läsa stora kalkylbladsfiler i lättviktsläge.



Typen LightCellsDataHandler avslöjar följande medlemmar:

###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [start_sheet](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Börjar bearbeta ett kalkylblad.|
| [start_row](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_row/#int) | Förbereder bearbetning av en rad.|
| [process_row](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Börjar bearbeta en rad.|
| [start_cell](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_cell/#int) | Förbereder bearbetning av en cell.|
| [process_cell](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Börjar bearbeta en cell.|



###  Anmärkningar

När du läser en arbetsbok med det här läget, kommer [`LightCellsDataHandler.start_sheet`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_sheet) att kontrolleras när du läser alla kalkylblad i arbetsboken.
För ett ark, om [`LightCellsDataHandler.start_sheet`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_sheet) ger sant, kommer alla data och egenskaper för rader/celler i detta ark att kontrolleras
och bearbetas av implementeringen av detta gränssnitt. För varje rad kommer [`LightCellsDataHandler.start_row`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_row) att anropas för att kontrollera om den behöver bearbetas.
Om en rad behöver bearbetas kommer egenskaperna för denna rad att läsas först och användaren kan komma åt dess egenskaper genom [`LightCellsDataHandler.process_row`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/process_row).
om radens celler också behöver bearbetas, så ska [`LightCellsDataHandler.process_row`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/process_row) returnera sant och då kommer [`LightCellsDataHandler.start_cell`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/start_cell) att vara
uppmanade varje befintlig cell i den här raden att kontrollera om en cell behöver bearbetas. Om en cell behöver bearbetas,
då kommer [`LightCellsDataHandler.process_cell`](/cells/python-net/sv/aspose.cells/lightcellsdatahandler/process_cell) att anropas för att behandla cellen genom implementeringen av detta gränssnitt.


Observera att användaren endast bör använda värdena och egenskaperna för det aktuella objektet Row/Cell som tillhandahålls av motsvarande metod.
Eftersom celldata läses från mallfilen på ett strömmande sätt, kan de flesta andra objekt återställas/uppdateras senare
efter att celldata har laddats. Så när användaren använder andra objekt i den här implementeringen,
dessa operationer kanske inte kan påverka objekten som finns i arbetsboken. Eller ännu värre, dessa operationer kan
orsaka inkonsekventa data i arbetsboken och orsaka oväntade problem eller undantag senare.
Så för alla andra objekt som former, kolumnbredd och stilar, villkorliga formateringar, ... etc.,
använd dem inte i några metoder för denna implementering.
Hantera dem istället efter att arbetsboken har konstruerats.

###  Se även
* modul [`aspose.cells`](..)
