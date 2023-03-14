---
title: DBConnection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells.externalconnections/dbconnection/
is_root: false
---
##  DBConnection klass
Anger alla egenskaper som är associerade med en extern ODBC- eller OLE DB-dataanslutning.



**Arv:** [DBConnection](/cells/python-net/aspose.cells.externalconnections/dbconnection) → 
[ExternalConnection](/cells/python-net/sv/aspose.cells.externalconnections/externalconnection)



Typen DBConnection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [id](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/id) | Får anslutningens ID.|
| [power_query_formula](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/power_query_formula) | Hämtar definitionen av kraftfrågeformel.|
| [type](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/type) | Hämtar eller ställer in den externa anslutningens DataSource-typ.|
| [source_file](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/source_file) | Används när den externa datakällan är filbaserad. När en anslutning till en sådan data<br/> källan misslyckas försöker kalkylarksprogrammet ansluta direkt till den här filen. Kanske<br/> uttryckt i URI eller systemspecifik filsökvägsnotation.|
| [sso_id](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/sso_id) | Identifierare för enkel inloggning (SSO) som används för autentisering mellan en intermediär<br/> kalkylarkML-server och den externa datakällan.|
| [save_password](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/save_password) | True om lösenordet ska sparas som en del av anslutningssträngen; annars, Falskt.|
| [save_data](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/save_data) | Sant om den externa data som hämtas via anslutningen för att fylla i en tabell ska sparas<br/> med arbetsboken; annars falskt.|
| [refresh_on_load](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/refresh_on_load) | Sant om den här anslutningen ska uppdateras när filen öppnas; annars falskt.|
| [reconnection_method_type](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/reconnection_method_type) | Anger vad kalkylarksapplikationen ska göra när en anslutning misslyckas.<br/>Standardvärdet är ReConnectionMethodType.Required.|
| [reconnection_method](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/reconnection_method) | Anger vad kalkylarksapplikationen ska göra när en anslutning misslyckas.<br/>Standardvärdet är ReConnectionMethodType.Required.|
| [only_use_connection_file](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/only_use_connection_file) | Anger om kalkylbladsapplikationen alltid och bara ska använda<br/> anslutningsinformation i den externa anslutningsfilen som anges av odcFile-attributet<br/> när anslutningen uppdateras. Om falskt, då kalkylarksapplikationen<br/> bör följa proceduren som anges av attributet reconnectionMethod|
| [odc_file](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/odc_file) | Anger den fullständiga sökvägen till den externa anslutningsfilen från vilken anslutningen kom<br/> skapat. Om en anslutning misslyckas under ett försök att uppdatera data, och reconnectionMethod=1,<br/> då försöker kalkylarket igen med information från den externa anslutningsfilen<br/> istället för det anslutningsobjekt som är inbäddat i arbetsboken.|
| [is_new](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/is_new) | Sant om anslutningen inte har uppdaterats för första gången; annars falskt.<br/> Detta tillstånd kan inträffa när användaren sparar filen innan en fråga har slutat returnera.|
| [name](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/name) | Anger namnet på anslutningen. Varje anslutning måste ha ett unikt namn.|
| [keep_alive](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/keep_alive) | Sant när kalkylprogrammet ska anstränga sig för att behålla anslutningen<br/>öppen. När det är falskt bör applikationen stänga anslutningen efter att ha hämtat<br/> information.|
| [refresh_internal](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/refresh_internal) | Anger antalet minuter mellan automatiska uppdateringar av anslutningen.|
| [connection_id](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/connection_id) | Anger den unika identifieraren för denna anslutning.|
| [connection_description](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/connection_description) | Anger användarbeskrivningen för denna anslutning|
| [is_deleted](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/is_deleted) |Indikerar om den associerade arbetsboksanslutningen har tagits bort. sant om<br/> anslutningen har tagits bort; annars falskt.|
| [credentials_method_type](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/credentials_method_type) | Anger den autentiseringsmetod som ska användas när anslutningen upprättas (eller återupprättas).|
| [credentials](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/credentials) | Anger den autentiseringsmetod som ska användas när anslutningen upprättas (eller återupprättas).|
| [background_refresh](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/background_refresh) | Indikerar om anslutningen kan uppdateras i bakgrunden (asynkront).<br/>sant om föredragen användning av anslutningen är att uppdatera asynkront i bakgrunden;<br/> false om föredragen användning av anslutningen är att uppdatera synkront i förgrunden.|
| [parameters](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/parameters) | Får [ConnectionParameterCollection](/cells/python-net/sv/aspose.cells.externalconnections/connectionparametercollection) för en ODBC- eller webbfråga.|
| [connection_info](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/connection_info) | Anslutningsinformationssträngen används för att ta kontakt med en OLE DB- eller ODBC-datakälla.|
| [command_type](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/command_type) | Anger kommandotypen OLE DB.<br/>1. Fråga anger ett kubnamn<br/>2. Fråga anger en SQL-sats<br/>3. Fråga anger ett tabellnamn<br/>4. Fråga anger att standardinformation har getts, och det är upp till leverantören hur man ska tolka.<br/> 5. Frågan är mot en webbaserad listdataleverantör.|
| [command](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/command) | Strängen som innehåller databaskommandot att skicka till dataleverantören API som kommer<br/> interagera med den externa källan för att hämta data|
| [sever_command](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection/sever_command) |Anger en andra kommandotextsträng som kvarstår när den är pivottabellserverbaserad<br/> sidfält används.<br/> För ODBC-anslutningar är serverCommand vanligtvis en bredare fråga än kommandot (nr<br/>WHERE-satsen finns i den förra). Baserat på dessa 2 kommandon (Command och ServerCommand),<br/> parameter UI kan fyllas i och parameteriserade frågor kan konstrueras|



###  Se även
* modul [aspose.cells.externalconnections](..)
* klass [ConnectionParameterCollection](/cells/python-net/sv/aspose.cells.externalconnections/connectionparametercollection)
* klass [DBConnection](/cells/python-net/sv/aspose.cells.externalconnections/dbconnection)
* klass [ExternalConnection](/cells/python-net/sv/aspose.cells.externalconnections/externalconnection)
