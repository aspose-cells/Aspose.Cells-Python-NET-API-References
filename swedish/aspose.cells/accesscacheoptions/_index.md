---
title: AccessCacheOptions uppräkning
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1710
url: /sv/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions uppräkning
Cachealternativ för dataåtkomst. Kan kombineras med |-operatorn för flera alternativ tillsammans.



Typen AccessCacheOptions avslöjar följande medlemmar:

###  Fält
| Fält| Beskrivning|
| :- | :- |
| NONE | Ingen cache för någon dataåtkomst.|
| ALL | Tillämpa alla möjliga optimeringar för alla typer av dataåtkomst i arbetsboken.<br/> Inga inställningar och data bör ändras under den optimerade åtkomsten.|
| POSITION_AND_SIZE | Tillämpa möjlig optimering för att hämta objektets (t.ex. form) position och storlek.<br/> Inställningar för radhöjd och kolumnbredd bör inte ändras under den optimerade åtkomsten.|
| CELLS_DATA | Tillämpa möjlig optimering för att hämta cellernas värden.<br/>Cells-data (data och inställningar för Cell, rad) bör inte ändras under<br/>den optimerade åtkomsten, inga nya Cell/Row-objekt ska heller skapas (t.ex.<br/> av [indexerare]).|
| CELL_DISPLAY | Tillämpa möjlig optimering för att få visningsrelaterade resultat av<br/>celler ([`Cell.display_string_value`](/cells/python-net/sv/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/sv/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/sv/aspose.cells/cell/get_display_style), etc.).<br/>Cells data och stilrelaterade objekt (Cell/Rad-/Kolumnstilar, kolumnbredd etc.) ska inte ändras<br/> under den optimerade åtkomsten.|
| GET_FORMULA | Tillämpa möjlig optimering för att hämta formler.<br/>Alla data och inställningar som kan påverka formeluttrycket (arbetsbladets namn, namnets text,<br/> tabellens kolumn, etc.) bör inte ändras under den optimerade åtkomsten.|
| SET_FORMULA | Tillämpa möjlig optimering för att ställa in formler.<br/>Alla data och inställningar som kan påverka formeluttrycket (arbetsbladets namn, namnets text,<br/> tabellens kolumn, etc.) bör inte ändras under den optimerade åtkomsten.|
| CALCULATE_FORMULA | Tillämpa möjlig optimering för att beräkna formler.<br/>Cells-data ska inte ändras under den optimerade åtkomsten, inga nya objekt (Cell, rad, etc.)<br/> bör skapas antingen (t.ex. av [indexer]).|
| CONDITIONAL_FORMATTING | Tillämpa möjlig optimering för att hämta formateringsresultat från villkorlig formatering.<br/>All data och inställningar som kan påverka resultatet av villkorlig formatering (inställningar för<br/> villkorsstyrd formatering, beroende cellvärden etc.) bör inte ändras under den optimerade åtkomsten.|
| VALIDATION | Tillämpa möjlig optimering för att få valideringsresultat.<br/>All data och inställningar som kan påverka resultatet av valideringen (inställningar för valideringen,<br/> beroende cellvärden etc.) bör inte ändras under den optimerade åtkomsten.|



###  Anmärkningar

För vissa funktioner kräver åtkomst till stora datamängder många upprepade och komplicerade operationer
såsom sökning, beräkning, ...etc. och de operationerna kommer att ta mycket extra tid.
I vanliga fall förblir all beroende data oförändrad under åtkomsten, så vissa cacher kan byggas och användas för att
förbättra åtkomstprestandan.
För detta ändamål tillhandahåller vi denna API så att användaren kan ange vilken typ av dataåtkomst som behövs.
att optimeras genom eventuell cachningsmekanism.


Observera att olika datamängder kan krävas att de är "skrivskyddade" för olika alternativ.
Och prestandan för åtkomst till data beror på många aspekter, användningen av cachningsmekanismen
garanterar inte att prestandan förbättras. I vissa situationer,
till exempel om datamängden som ska nås är liten, kan användning av cache orsaka ännu mer tid eftersom
Själva cachningen behöver också viss extra tid.

###  Se även
* modul [`aspose.cells`](..)
