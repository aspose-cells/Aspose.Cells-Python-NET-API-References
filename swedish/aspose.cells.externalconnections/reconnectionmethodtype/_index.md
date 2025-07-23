---
title: ReConnectionMethodType uppräkning
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 130
url: /sv/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
##  ReConnectionMethodType uppräkning
Anger vad kalkylprogrammet ska göra när en anslutning misslyckas.



Typen ReConnectionMethodType avslöjar följande medlemmar:

###  Fält
| Fält| Beskrivning|
| :- | :- |
| REQUIRED | Använd den befintliga anslutningsinformationen vid uppdatering, och om den visar sig vara ogiltig<br/> hämta sedan uppdaterad anslutningsinformation, om tillgänglig från den externa anslutningsfilen.|
| ALWAYS | Hämta uppdaterad anslutningsinformation från den externa anslutningsfilen vid varje uppdatering.<br/> om tillgängligt, och använd det istället för den befintliga anslutningsinformationen.<br/> det här fallet kommer datauppdateringen att misslyckas om den externa anslutningsfilen inte är tillgänglig.|
| NEVER | Hämta aldrig uppdaterad anslutningsinformation från den externa anslutningsfilen<br/> även om den är tillgänglig och även om den befintliga anslutningsinformationen är ogiltig|



###  Se även
* modul [`aspose.cells.externalconnections`](..)
