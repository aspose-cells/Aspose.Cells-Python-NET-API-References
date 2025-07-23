---
title: FormatConditionType uppräkning
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 2110
url: /sv/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType uppräkning
Regeltyp för villkorsstyrd formatering.



Typen FormatConditionType avslöjar följande medlemmar:

###  Fält
| Fält| Beskrivning|
| :- | :- |
| CELL_VALUE | Denna regel för villkorlig formatering jämför ett cellvärde<br/> till ett formelberäknat resultat med hjälp av en operator.|
| EXPRESSION | Denna regel för villkorlig formatering innehåller en formel för att<br/>utvärdera. När formelresultatet är sant, är cellen<br/> markerad.|
| TOP10 | Denna regel för villkorlig formatering markerar celler vars<br/>värdena faller i den övre N- eller nedre N-parentesen, eftersom<br/> specificerad.|
| UNIQUE_VALUES | Denna regel för villkorlig formatering markerar unika<br/> värden i intervallet.|
| DUPLICATE_VALUES | Denna regel för villkorlig formatering markerar duplicerade<br/> värden.|
| CONTAINS_TEXT | Denna regel för villkorlig formatering markerar celler<br/>innehåller given text. Motsvarar att använda SEARCH()<br/>arkfunktionen för att avgöra om cellen innehåller<br/> texten.|
| NOT_CONTAINS_TEXT | Denna regel för villkorlig formatering markerar celler som<br/>innehåller inte given text. Motsvarar att använda SEARCH()<br/>arkfunktionen för att avgöra om cellen innehåller<br/> texten eller inte.|
| BEGINS_WITH | Denna regel för villkorlig formatering markerar celler i<br/>intervall som börjar med den angivna texten. Motsvarande<br/> med hjälp av LEFT()-arkfunktionen och jämförande värden.|
| ENDS_WITH | Denna regel för villkorlig formatering markerar celler som slutar<br/>med given text. Motsvarar att använda RIGHT()-arket<br/> funktion och jämförelse av värden.|
| CONTAINS_BLANKS | Denna regel för villkorlig formatering markerar celler som<br/>är helt tomma. Motsvarar att använda LEN(TRIM()).<br/>Det betyder att om cellen bara innehåller tecken<br/>som TRIM() skulle ta bort, då anses den vara tom.<br/> En tom cell betraktas också som tom.|
| NOT_CONTAINS_BLANKS | Denna regel för villkorlig formatering markerar celler som<br/>är inte tomma. Motsvarar att använda LEN(TRIM()). Detta<br/>betyder att om cellen bara innehåller tecken som<br/>TRIM() skulle ta bort, då anses den vara tom.<br/> en tom cell anses också vara tom.|
| CONTAINS_ERRORS | Denna regel för villkorlig formatering markerar celler med<br/>formelfel. Motsvarar att använda ISERROR()-arket<br/> funktion för att avgöra om det finns ett formelfel.|
| NOT_CONTAINS_ERRORS | Denna regel för villkorlig formatering markerar celler<br/>utan formelfel. Motsvarar att använda ISERROR()<br/> arkfunktionen för att avgöra om det finns ett formelfel.|
| TIME_PERIOD | Denna regel för villkorlig formatering markerar celler<br/>som innehåller datum inom den angivna tidsperioden. Den<br/>cellens underliggande värde utvärderas, därför<br/>cellen behöver inte formateras som ett datum för att vara<br/>utvärderad. Till exempel, med en cell som innehåller<br/>värde 38913 ska det villkorliga formatet tillämpas om<br/> Regeln kräver ett värde på 14/7/2006.|
| ABOVE_AVERAGE | Denna regel för villkorlig formatering markerar celler som<br/>är över eller under genomsnittet för alla värden i<br/> räckvidd.|
| COLOR_SCALE | Denna regel för villkorlig formatering skapar en graderad<br/> färgskalan på cellerna.|
| DATA_BAR | Denna regel för villkorlig formatering visar en graderad<br/> datafältet i cellområdet.|
| ICON_SET |Denna regel för villkorlig formatering tillämpar ikoner på celler<br/> enligt deras värderingar.|



###  Se även
* modul [`aspose.cells`](..)
